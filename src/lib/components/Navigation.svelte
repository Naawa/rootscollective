<nav>
    <a class="hidden" href="/"><img src="/assets/Logo.png" alt="Logo"></a>
    <a class="hidden" href="/about">About Us</a>
</nav>

<style lang="scss">
    nav {
        display: flex;
        align-items: center;
        justify-content: space-between;
        height: 4em;
        width: 100%;
        padding: 0 15vw;
        margin: auto;
        overflow: hidden;

        a {
            line-height: 1;
            font-weight: 700;

            img {
                scale: 1.2;
                max-width: 40vw;
            }

            &:last-of-type {
                font-family: "Montserrat";
                font-weight: 500;
            }
        }
    }

    @media (width < 800px) {
        nav {
            padding: 0 1em;
        }
    }
</style>