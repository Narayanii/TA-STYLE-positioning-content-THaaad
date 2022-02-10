<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
 <meta http-equiv="X-UA-Compatible" content="IE=edge">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>Assignment</title>
 <link rel="stylesheet" href="style.css">
</head>

<body>

<header>
<section class="section-1">
<p class="para">blue & black</p>
<nav class="nav"> about us</nav>
<footer>instagram</footer>
</section>
<section>
<main>
<article>
<div class="row">
<div class="column">Lorem ipsum
<div class="detail">Lorem ipsum dolor sit amet consectetur adipisicing elit. Esse dolorum enim labore explicabo possimus quod. Adipisci, accusantium. Optio dolore deserunt perferendis vel deleniti, modi quibusdam doloremque aut accusantium inventore unde.</div>
</div>
<div class="column">
<img src="max.jpg" alt="blueandblack">
</div>

</div>
</article>
</main>
</section>
  
 /* http://meyerweb.com/eric/tools/css/reset/ 
   v2.0 | 20110126
   License: none (public domain)
*/

html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure, 
footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;
	border-spacing: 0;
}
/* Custome Styles */

.section-1{ display: flex;
text-transform: uppercase;
padding: 20px 20px;
color: rgb(138, 122, 102);
background-color: rgb(7, 7, 80);
height: 80px;
}

.para {  margin-left: 20px ;
display: inline-block;
}
.nav { margin-left: 75%;
display: inline-block;
}
footer {
margin-left: 15px;
}
/* main section*/
.row { display: flex;
padding: 10px;

}
.column{ display: inline-block;
width: 30%;
height: 500px;
padding: 20px;
border: 2px solid black;
margin: 30px 90px 30px ;
}
.column { text-align: center;
text-transform: uppercase;
color: black;
font-style: italic;

}
.detail { margin: 80px 0 0;
line-height: 1.5;
}
img { 
width: 100%;
height: 500px;
}
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          
