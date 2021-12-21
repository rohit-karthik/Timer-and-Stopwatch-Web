<parent>
	<img
		style="padding: 0.5em"
		src="icon.png"
		alt="Timer and Stopwatch Icon"
		width="200px"
		height="200px"
	/>
	<h1
		style="
			color:#C0D5FB; 
			font-family:-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
			font-size: 100px;
			text-align: center;"
	>
		The best timer and stopwatch app out there.
	</h1>
	<main>
		<a
			class="downloadLink"
			href="Timer and Stopwatch-1.0.0-arm64.dmg"
			download>Download for Apple Silicon</a
		>
		<a
			class="downloadLinkWin"
			href="Timer and Stopwatch Setup 1.0.0.exe"
			download>Download for Windows</a
		>
	</main>
	<main style="padding-top: 8rem;">
		<h1
			style="
			color:#C0D5FB; 
			font-family:-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
			font-size: 75px;
			width: 400px;
			margin: 0;"
		>
			A <u>beautiful</u> looking UI. 
		</h1>
		<img
			style="padding: 2em"
			src="screenshot1.png"
			alt="Timer and Stopwatch Icon"
			width="768"
			height="475"
		/>
	</main>
</parent>

<style>
	parent {
		padding: 0;
		margin: 0;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
	}
	main {
		display: flex;
		flex-direction: row;
		justify-content: center;
		align-items: center;
	}
	.downloadLink {
		color: white;
		background-color: cornflowerblue;
		padding: 0.9em;
		border-radius: 0.4em;
		margin: 0.4em;
		transition: all 0.15s;
	}
	.downloadLinkWin {
		color: white;
		background-color: red;
		padding: 0.9em;
		border-radius: 0.4em;
		margin: 0.4em;
		transition: all 0.15s;
	}
	.downloadLink:hover {
		text-decoration: none;
		background-color: transparent;
		padding: 0.825em 0.9em;
		border: 1px solid cornflowerblue;
		color: cornflowerblue;
	}
	.downloadLinkWin:hover {
		text-decoration: none;
		background-color: transparent;
		padding: 0.825em 0.9em;
		border: 1px solid red;
		color: red;
	}
</style>
