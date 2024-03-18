<section>
    <div>
        <span>
            <h1>Unity through</h1>
            <h1>Asian Pop Culture</h1>
        </span>
        <p>Spark new connections by celebrating Asian Pop Culture and empowering <br> Asian minoroties and local businesses.</p>
    </div>
    <button>Join Our Next Event</button>
    <svg width="581" height="607" viewBox="-2 -2 581 607" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path fill-rule="evenodd" clip-rule="evenodd" d="M369.604 11.9499C437.93 31.4902 466.196 105.945 507.372 163.865C538.233 207.277 570.605 248.598 575.539 301.633C581.021 360.551 569.079 418.85 535.638 467.667C493.782 528.767 443.342 609.167 369.604 602.251C296.003 595.347 289.036 486.275 232.045 439.191C161.294 380.739 31.0195 389.853 5.72812 301.633C-20.4184 210.43 47.247 112.596 121.475 53.5032C189.68 -0.795303 285.785 -12.0215 369.604 11.9499Z" stroke="#93471B" stroke-width="3"/>
    </svg>
    <svg width="581" height="607" viewBox="-2 -2 581 607" fill="rgb(241,116,45)" xmlns="http://www.w3.org/2000/svg">
        <path fill-rule="evenodd" clip-rule="evenodd" d="M369.604 11.9499C437.93 31.4902 466.196 105.945 507.372 163.865C538.233 207.277 570.605 248.598 575.539 301.633C581.021 360.551 569.079 418.85 535.638 467.667C493.782 528.767 443.342 609.167 369.604 602.251C296.003 595.347 289.036 486.275 232.045 439.191C161.294 380.739 31.0195 389.853 5.72812 301.633C-20.4184 210.43 47.247 112.596 121.475 53.5032C189.68 -0.795303 285.785 -12.0215 369.604 11.9499Z" stroke="none" stroke-width="3"/>
    </svg>
    <svg width="561" height="593" viewBox="-2 -2 561 593" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path fill-rule="evenodd" clip-rule="evenodd" d="M205.39 0.563373C279.552 -5.60613 330.454 66.6514 387.373 114.591C453.283 170.102 561.305 210.517 556.848 296.574C552.384 382.765 435.83 405.474 369.45 460.633C313.994 506.716 277.403 584.989 205.39 588.625C131.841 592.337 65.3092 538.966 23.8866 478.077C-11.6489 425.843 1.55086 359.539 6.70652 296.574C11.2417 241.187 20.3895 188.686 51.3604 142.544C91.8158 82.271 133.049 6.58143 205.39 0.563373Z" stroke="#F5B6B7" stroke-width="3"/>
    </svg>  
    <svg width="559" height="591" viewBox="-1 -1 559 591" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path fill-rule="evenodd" clip-rule="evenodd" d="M205.39 0.563373C279.552 -5.60613 330.454 66.6514 387.373 114.591C453.283 170.102 561.305 210.517 556.848 296.574C552.384 382.765 435.83 405.474 369.45 460.633C313.994 506.716 277.403 584.989 205.39 588.625C131.841 592.337 65.3092 538.966 23.8866 478.077C-11.6489 425.843 1.55086 359.539 6.70652 296.574C11.2417 241.187 20.3895 188.686 51.3604 142.544C91.8158 82.271 133.049 6.58143 205.39 0.563373Z" fill="#E74E4F"/>
        </svg>              
</section>

<style lang="scss">
    section {
        display: flex;
        flex-direction: column;
        justify-content: center;
        padding: 8em 10vw;
        gap: 3em;
        background-color: #fdf1ea;
        position: relative;
        overflow: hidden;

        div {
            display: flex;
            flex-direction: column;
            gap: 1em;
            background-color: transparent;
            z-index: 3;
            
            span {
                background-color: transparent;
                h1 {
                    background-color: transparent;
                    font-weight: 500;
                    
                    &:last-of-type {
                        background-color: #f38c51;
                        width: fit-content;
                        padding: 0 0.05em;
                        border-radius: 0.1em;
                    }
                }
            }

            p {
                background-color: transparent;
            }
        }

        svg {
            background-color: transparent;
            position: absolute;
            height: 100%;
            width: 110%;
            z-index: 2;
            left: 30vw;
            top: 33%;

            &:nth-last-of-type(3) {
                top: 20%;
                left: 35vw;
                z-index: 1;
            }

            &:nth-last-of-type(2) {
                top: -80%;
                left: -45vw;
                z-index: 2;
            }
            &:nth-last-of-type(1) {
                top: -80%;
                left: -40vw;
                z-index: 1;
            }
        }
    }

    @media (width < 1600px) {
        section {
            svg {
                left: 40vw;

                &:nth-last-of-type(3) {
                    left: 47vw;
                }
                &:nth-last-of-type(2) {
                    top: -80%;
                    left: -40vw;
                }
                &:nth-last-of-type(1) {
                    top: -80%;
                    left: -30vw;
                }
            }
        }
    }
</style>

