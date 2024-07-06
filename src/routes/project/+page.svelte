<script>
import Insimg from './../../img/insects.jpg';
import Herosimg from './../../img/Hero.jpg';
import Heade from './../__layout.svelte';
</script>
<Heade />
<div class="container">
<div class="Portfolio-information">
    <h3 id="head">Projects</h3>
    <ul>
        <div class="window">
            <li>
                <img alt="" src={Herosimg} />
                <p>
                    <a
                        id="github"
                        href="https://github.com/group06854/projectforlab/blob/main/Mysterious%20Legends"
                        >Mysterious Legends</a
                    >
                </p>
                <p>
                    In the exciting world of "Mysterious Legends", where magic and technology are closely
                    intertwined, open up for a new adventure In this epic RPG, where every step can change
                    the course of history, you take the role of a hero ready to explore mysterious
                    lands...
                </p>
            </li>
        </div>
        <div class="window">
            <li>
                <a
                    id="github"
                    href="https://github.com/group06854/projectforlab/blob/main/Insect%20Battle"
                    ><img alt="" src={Insimg} /></a
                >
                <p>
                    <a
                        id="github"
                        href="https://github.com/group06854/projectforlab/blob/main/Insect%20Battle"
                        >Insect Battle</a
                    >
                </p>
                <p>
                    In a world where strategy and tactics become key qualities, open up for Insect Battle,
                    an exciting game in the genre of strategic chess board combat. Here, every move can
                    decide the outcome of the battle, and only the most skillful strategist will be able
                    to dominate.
                </p>
            </li>
        </div>
    </ul>
</div>
</div>

<style>
    p{
        margin-left: 4px;
    }
    img {
		max-width: 98%;
        margin: 0.5%;
	}
    .container {
		margin-top: 1px;
		width: 98%;
		margin-left: 0.5%;
		margin-right: 0.5%;
	}
    #head {
		color: white;
		text-align: center;
		font-weight: 800;
		margin-bottom: 40px;
	}
    a {
		text-decoration: none;
		color: aliceblue;
	}
    .window {
		width: 48%;
		display: inline-block;
		padding: 0px;
		border-width: 1px;
		border-color: grey;
		border-style: solid;
		border-radius: 5%;
		margin: 0 auto;
		margin-bottom: 40px;
	}
	.window img {
		border-radius: 5%;
	}
    #github {
		text-align: right;
		font-weight: 800;
	}
	.Portfolio-information ul {
		list-style: none;
		display: flex;
		justify-content: space-between;
	}
    :root {
		font-family: Inter, system-ui, Avenir, Helvetica, Arial, sans-serif;
		line-height: 1.5;
		font-weight: 400;

		font-family: 'Poppins', sans-serif;
		font-weight: 400;
		color: white;
		background: rgb(0, 0, 0);
		background: linear-gradient(90deg, rgba(0, 0, 0, 1) 0%, rgba(26, 14, 1, 1) 100%);

		font-synthesis: none;
		text-rendering: optimizeLegibility;
		-webkit-font-smoothing: antialiased;
		-moz-osx-font-smoothing: grayscale;
	}
</style>