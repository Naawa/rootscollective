<section>
    <div>
        <img src="/assets/LandingAbout.png" alt="">
    </div>
    <div>
        <span>
            <h3>About Us</h3>
            <p>Roots Collective is a non-profit events organization with a mission to spark new connections and interests through celebrating Asian pop culture and empowering Asian minorities in North America.</p>
        </span>
        <a href="/about">Learn more about us</a>
    </div>
</section>

<style lang="scss">
    section {
        display: flex;
        flex-direction: row;
        justify-content: center;
        gap: 2em;
        padding: 2em;

        div {
            display: flex;
            flex-direction: column;
            justify-content: center;
            gap: 2em;
            background-color: #efeeee;
            padding: 2em;
            border-radius: 1em;
            min-height: 100%;
            width: 100%;

            &:first-of-type {
                padding: 0;
            }

            img {
                border-radius: 1em;
                height: 100%;
            }

            span {
                display: flex;
                flex-direction: column;
                justify-content: center;
                gap: 1em;
                background-color: transparent;

                h3 {
                    font-weight: 500;
                    border-bottom: solid 0.05em #d7743a;
                    width: fit-content;
                    background-color: transparent;
                }
                p {
                    display: flex;
                    background-color: transparent;
                    max-width: 30em;
                }
            }

            a {
                background-color: transparent;
                color: #995229;
            }
        }
    }

    @media (width < 1200px) {
        section {
            flex-direction: column;
            align-items: center;
            padding: 1em;

            div {
                width: 100%;
                padding: 2em 1em;
                width: calc(100% - 2em);

                &:first-of-type {
                    min-height: fit-content;
                }

                img {
                    height: 100%;
                    width: 100%;
                }
            }
        }
    }
</style>