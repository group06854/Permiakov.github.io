

<header class="container">
	<span class="logo">Lev Permiakov</span>
	<nav>
		<ul>
			<li><a id="nav" href="/">About Me</a></li>
			<li><a id="nav" href="/project">Portfolio</a></li>
			<li><a id="nav" href="/contact">Contact Me</a></li>
			<li><a id="nav" href="/сomic">Homework</a></li>
		</ul>   
	</nav>
</header>

<style>
	
	a {
		text-decoration: none;
		color: aliceblue;
	}
	.container {
		margin-top: 1px;
		width: 98%;
		margin-left: 0.5%;
		margin-right: 0.5%;
	}
	header {
		padding: 10px;
		margin-bottom: 40px;
	}
	header .logo {
		width: 10%;
		font-weight: 800;
		text-transform: uppercase;
		color: white;
	}
	header ul {
		list-style: none;
		display: flex;
		justify-content: space-between;
	}

	header nav {
		float: right;
		width: 50%;
	}
	header nav ul {
		list-style: none;
		display: flex;
		justify-content: space-between;
	}
	header ul li {
		display: inline-block;
	}
	#nav {
		color: white;
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
