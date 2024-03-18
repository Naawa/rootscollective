<script lang="ts">
    interface Partner {
        logo: string,
        href: string,
    }
    const partners: Partner[] = [
        {
            logo: "/assets/ccg.png",
            href: "https://vancouverchinesegarden.com/"
        },
        {
            logo: "/assets/hn.png",
            href: "https://hungsnoodles.com/"
        },
        {
            logo: "/assets/sov.png",
            href: "https://www.streetsofvancity.com/"
        },
        {
            logo: "/assets/ms.png",
            href: ""
        },
        {
            logo: "/assets/tf.png",
            href: ""
        },
        {
            logo: "/assets/bb.png",
            href: ""
        },
        {
            logo: "/assets/tt.png",
            href: ""
        },
        {
            logo: "/assets/ip.png",
            href: ""
        }
    ]
</script>

<section>
    <h3>Our Partners</h3>
    <span>
        {#each partners as partner}
           <a href="{partner.href}"><img src="{partner.logo}" alt="Partner icon."></a> 
        {/each}
    </span>
</section>

<style lang="scss">
    section {
        padding: 2em;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        gap: 2em;

        h3 {
            text-align: center;
            font-weight: 500;
            font-family: "Aleo", sans-serif;
        }

        span {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-wrap: wrap;

            a {
                img {
                    height: 5em;
                }
            }
        }
    }
</style>