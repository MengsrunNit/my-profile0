<div>
	<header id="header">
		<div id="top">
			<img src="image/FurmanLogo.png" />
			<h1 id="welcome">
            <b>
                Welcome to my Page !!
            </b>
        </h1>
		</div>
		<div id="navigate-bar">
			<!-- <img src="image/FurmanLogo.png"/> -->
			<a id="home" href="/">Home</a>
			<a id="about" href="/about">About</a>
			<a id="contact">contact</a>
			<a id="furman" href="https://www.furman.edu/">Furman Page</a>
		</div>
	</header>
</div>

<div id="logo-box">hello</div>

<slot />

<style>
    #navigate-bar{
        display:flex; 
        justify-content: flex-start;
    }
	img {
		flex-basic: 200px;
		height: 80px;
		width: 200px;
        margin-right: 100px;
	}
	#header {
		display: flex;
		flex-direction: column;
        justify-content: flex-start;
	}
	#top {
		display: flex;
		flex-direction: row;
        justify-content:first baseline;
        margin: 10px 40px 10px 10px;
	}
	#logo-box {
		border: 200px;
		width: 100%;
		height: 20px;
		background-color: black;
	}

	#welcome {
		padding: 2px 5px;
		margin-left: 200px;
        color: brown;
	}
	#header {
		display: flex;
		flex-direction: column;
		width: 1300px;
		height: 150px;
		background: #82e0aa;
		border: 20px;
		padding: 3px 5px;
		text-align: center;
		margin-left: auto;
		margin-right: auto;
        
	}
	#home,
	#about,
	#furman,
	#contact {
		border: 2px solid black;
		color: white;
		padding: 7px 6px;
		text-align: center;
		text-decoration: none;
		display: inline-block;
		font-size: 16px;
		margin: 2px 1px;
		transition-duration: 0.4s;
		cursor: pointer;
		width: 90px;
		height: 30px;
		align: left;
	}
	#home {
		background-color: red;
	}
	#furman {
		background-color: purple;
	}
	#about {
		background-color: blue;
	}
	#contact {
		background-color: midnightblue;
	}
</style>
