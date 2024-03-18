<section>
    <span>
        <h3>Want to get involved?</h3>
        <p>Are you passionate about giving back to the community and making a positive impact? Join our dedicated team of volunteers to turn more ideas into reality! Whether you’re a creative, organizer, or a charmer, we have a variety of opportunities.</p>
    </span>
    <button>Join Now</button>
</section>

<style lang="scss">
    section {
        display: flex;
        justify-content: center;
        flex-direction: column;
        padding: 8em;
        gap: 2em;
        background-color: #fdf1ea;

        span {
            display: flex;
            flex-direction: column;
            gap: 1em;
            background-color: transparent;
            max-width: 80vw;

            h3 {
                font-weight: 500;
                font-family: "Aleo", sans-serif;
            }
        }
    }

    @media (width < 800px) {
		section {
			padding: 2em;
		}
	}
</style>