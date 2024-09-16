<div class="page-header-block">
	<h1 class="header-1 centered greeting">hello</h1>
</div>
<div class="container">
	<div class="centered flex-column">
		<p>
			Welcome to my personal site. I&apos;m Fred and I am a web developer, which means I made this!
			Pretty crazy right?
		</p>
		<p>
			I&apos;ve been doing web development for a while and really love frontend development. As you
			can tell, my website is the epitome of design. If you don&apos;t like it, that&apos;s ok. Its
			art. Or something. Really that&apos;s just an excuse for these garish colors.
		</p>
	</div>
</div>
<div class="container"></div>

<style>
	@property --gradient-angle {
		syntax: '<angle>';
		initial-value: 0deg;
		inherits: false;
	}

	@keyframes rotate-gradient {
		to {
			--gradient-angle: 360deg;
		}
	}

	.page-header-block {
		width: 100%;
		height: 24rem;
		background: black;
		background: linear-gradient(
			90deg,
			var(--bittersweet) 0%,
			var(--wine) 50%,
			var(--van-dyke) 100%
		);
	}
	.greeting {
		background: linear-gradient(
			var(--gradient-angle),
			var(--verdigris) 0%,
			var(--peach-yellow) 91%
		);
		background-clip: text;
		-webkit-text-stroke: 1rem transparent;
		color: white;
		animation: rotate-gradient 5s linear infinite;
	}
</style>
