<section>
	<div>
		<h1 class="biggest">Lorem ipsum</h1>
		<p class="bigger">Dolor sit amet!</p>
	</div>
</section>
  <section>
	<div>
		<h2 class="big">Entering a new linguistic space with SMOL T2Hue</h2>
		<p class="big">SMOL T2Hue is an Open Typefont</p>
	</div>
</section>
	<div>
		<h4 class="smaller">"Make it simple, but not simpler." – Albert Einstein</h4>
		<p class="smaller">"Keep it SMOL, but do it better. – Jens T. Hinrichs</p>	
	</div>
<section>
	<div>
		<h4 class="smaller">Alphabet</h4>
		<p class="smaller">a b c d e f g h i j k l m n o p q r s t u v w x y z</p>
		<p class="smaller">A B C D E F G H I J K L M N O P Q R S T U V W X Y Z</p>
		<p class="smaller">A B C D E F G H I J K L M N O P Q R S T U V W X Y Z</p>
		<p class="smaller">0 1 2 3 4 5 6 7 8 9</p>
	</div>
</section>
<h1 class="biggest">How to use SMOL T2Hue in the Internet</h1>
<p>Make sure the fonts are uploaded in the same html-directory. Then copy the code for css directly between the head-section:</p>

	<style type="text/css">

		body {
			text-rendering: optimizeLegibility;
			font-feature-settings: "kern";
			-moz-font-feature-settings: "kern=1";
			-ms-font-feature-settings: "kern";
			-webkit-font-feature-settings: "kern";
			-o-font-feature-settings: "kern";
			
			margin: 0 0 0 0;
			padding: 0 0 0 0;
		}

		@font-face {
			font-family: "SMOL T2HueSVG";
			src: url("SMOL T2Hue.svg#SMOL T2Hue") format('svg');
		}

		@font-face {
			font-family: "SMOL T2HueOTF";
			src: url("SMOL T2Hue.otf") format('opentype');
		}

		@font-face {
			font-family: "SMOL T2HueTTF";
			src: url("SMOL T2Hue.ttf") format('truetype');
		}

		@font-face {
			font-family: "SMOL T2HueEOT"
	 		src: url("SMOL T2Hue.eot");
		}

	
		h1 {
			font-weight:normal;
			margin: 10px 0 5px 0;
			color: #afafaf;
		}

		h2 {
			font-weight:normal;
			margin: 0 0 5px 0;
			color: #afafaf;
		}
		
		h3 {
			font-weight:normal;
			margin: 0 0 5px 0;
			color: #afafaf;
		}
		
		h4 {
			font-weight:normal;
			margin: 0 0 5px 0;
			color: #afafaf;
		}
		
		p {
			margin: 0 0 5px 0;
			color: #000000;
		}
		
		div {
			font-family: "SMOL T2HueEOT", "SMOL T2HueOTF", "SMOL T2HueTTF", "SMOL T2HueSVG";
			margin: 0 0 30px 0;
		}
		
		section {
			padding-left: 25px;
		}

		h1.biggest {
			font-size: 72pt;
		}
		
		h1.bigger {
			font-size: 58pt;
		}

		h2.big {
			font-size: 40pt;
		}
		
		h3.small {
			font-size: 32pt;
		}

		h4.smaller {
			font-size: 18pt;
		}

		p.bigger {
			font-size: 32pt;
		}

		p.big {
			font-size: 24pt;
		}
		
		p.small {
			font-size: 18pt;
		}

		p.smaller {
			font-size: 12pt;
		}

		span.swashes {
			font-feature-settings: "swsh";	
		}
		
		span.alternates {	
			font-feature-settings: "salt" 1;
		}
		
		span.smallcaps {
			font-variant-caps: small-caps;
			font-feature-settings: "smcp";
		}

		span.capstosmallcaps {
			font-variant-caps: all-small-caps;
			font-feature-settings: "c2sc", "smcp";
		}
		
		span.stylisticset01 {
			font-feature-settings: "ss01";
		}
	</style>
