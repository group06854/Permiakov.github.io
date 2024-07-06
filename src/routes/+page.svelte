<script lang="ts">
	import Heade from './__layout.svelte';
	import Portimg from './../img/portfolio.png';
</script>

<main>
	<Heade />
	<div class="container">
		<div class="About_me">
			<h3 id="head_st">About me</h3>
			<p id="information">
				As a first-year student at Innopolis University, I came from Glazov, Udmurtia, after
				studying at the Physics and Mathematics Lyceum (FML), where I laid a solid foundation in
				mathematics and computer science. My lifelong love of strategy games has ignited my passion
				for programming and software development. Having mastered Python, C, C++, Java, HTML and
				CSS, I honed these skills through projects in FML, applying theory in practice and
				developing a deep understanding of software development. In addition to academic work, I
				have worked on personal projects, improving my programming, problem solving and creativity
				skills. At Innopolis, I strive to expand my technical knowledge, immerse myself in new
				technologies and contribute to cutting-edge projects, using my passion for technology and
				strategic mindset to influence computer science and more.
			</p>
			<div>
				<img id="portfolio" alt="" src={Portimg} />
			</div>
		</div>
	</div>
</main>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
	* {
		margin: 0;
		padding: 0;
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

	#head_st {
		color: white;
		text-align: center;
		font-weight: 800;
		margin-bottom: 40px;
	}

	img {
		max-width: 100%;
	}
	.container {
		margin-top: 1px;
		width: 98%;
		margin-left: 0.5%;
		margin-right: 0.5%;
	}
	#information {
		width: 50%;
		margin-left: 5%;
		margin-top: 40px;
		height: 400px;
		text-align: center;
	}
	#portfolio {
		position: absolute;
		top: 135px;
		right: 5%;
	}
</style>
