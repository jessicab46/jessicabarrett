body {
    background: #67B26F;  /* fallback for old browsers */
    background: -webkit-linear-gradient(to right, #4ca2cd, #67B26F);  /* Chrome 10-25, Safari 5.1-6 */
    background: linear-gradient(to right, #4ca2cd, #67B26F); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
    padding: 0;
    margin: 0;
    font-family: 'Lato', sans-serif;
    color: #000;
}

.student-profile .card {
    border-radius: 10px;
}

.student-profile .card .card-header .profile_img {
    width: 150px;
    height: 150px;
    object-fit: cover;
    margin: 10px auto;
    border: 10px solid #ccc;
    border-radius: 50%;
}

.student-profile .card h3 {
    font-size: 20px;
    font-weight: 700;
}

.student-profile .card p {
    font-size: 16px;
    color: #000;
}

.student-profile .table th,
.student-profile .table td {
    font-size: 14px;
    padding: 5px 10px;
    color: #000;
}

/* ******************************************************
	Author URI: https://codeconvey.com/
	Demo Purpose Only - May not require to add.
	font-family: "Raleway",sans-serif;
*********************************************************/

@import url('https://fonts.googleapis.com/css?family=Raleway:400,500,600,700,800,900');



html {
  box-sizing: border-box;
}
*, *:before, *:after {
  box-sizing: inherit;
}

article, header, section, aside, details, figcaption, figure, footer, header, hgroup, main, nav, section, summary {
    display: block;
}
body {
    color: #222;
    font-size: 100%;
    line-height: 24px;
    margin: 0;
	padding:0;
	font-family: "Raleway",sans-serif;
}
a{
	font-family: "Raleway",sans-serif;
	text-decoration: none;
	outline: none;
}
a:hover, a:focus {
	color: #373e18;
}
section {
    float: left;
    width: 100%;
	padding-bottom:3em;
}
h2 {
    color: #1a0e0e;
    font-size: 26px;
    font-weight: 700;
    margin: 0;
    line-height: normal;
	text-transform:uppercase;
}
h2 span {
    display: block;
    padding: 0;
    font-size: 18px;
    opacity: 0.7;
    margin-top: 5px;
	text-transform:uppercase;
}

#float-right{
	float:right;	
}

/* ******************************************************
	Script Top
*********************************************************/

.ScriptTop {
    background: #fff none repeat scroll 0 0;
    float: left;
    font-size: 0.69em;
    font-weight: 600;
    line-height: 2.2;
    padding: 12px 0;
    text-transform: uppercase;
    width: 100%;
}

/* To Navigation Style 1*/
.ScriptTop ul {
    margin: 24px 0;
    padding: 0;
    text-align: left;
}
.ScriptTop li{
	list-style:none;	
	display:inline-block;
}
.ScriptTop li a {
    background: #6a4aed none repeat scroll 0 0;
    color: #fff;
    display: inline-block;
    font-size: 14px;
    font-weight: 600;
    padding: 5px 18px;
    text-decoration: none;
    text-transform: capitalize;
}
.ScriptTop li a:hover{
	background:#000;
	color:#fff;
}


/* ******************************************************
	Script Header
*********************************************************/

.ScriptHeader {
    float: left;
    width: 100%;
    padding: 2em 0;
}
.rt-heading {
    margin: 0 auto;
	text-align:center;
}
.Scriptcontent{
	line-height:28px;	
}
.ScriptHeader h1{
	font-family: "brandon-grotesque", "Brandon Grotesque", "Source Sans Pro", "Segoe UI", Frutiger, "Frutiger Linotype", "Dejavu Sans", "Helvetica Neue", Arial, sans-serif;
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
    color: #6a4aed;
    font-size: 26px;
    font-weight: 700;
    margin: 0;
    line-height: normal;

}
.ScriptHeader h2 {
    color: #312c8f;
    font-size: 20px;
    font-weight: 400;
    margin: 5px 0 0;
    line-height: normal;

}
.ScriptHeader h1 span {
    display: block;
    padding: 0;
    font-size: 22px;
    opacity: 0.7;
    margin-top: 5px;

}
.ScriptHeader span {
    display: block;
    padding: 0;
    font-size: 22px;
    opacity: 0.7;
    margin-top: 5px;
}




/* ******************************************************
	Live Demo
*********************************************************/





/* ******************************************************
	Responsive Grids
*********************************************************/

.rt-container {
	margin: 0 auto;
	padding-left:12px;
	padding-right:12px;
}
.rt-row:before, .rt-row:after {
  display: table;
  line-height: 0;
  content: "";
}

.rt-row:after {
  clear: both;
}
[class^="col-rt-"] {
  box-sizing: border-box;
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  -o-box-sizing: border-box;
  -ms-box-sizing: border-box;
  padding: 0 15px;
  min-height: 1px;
  position: relative;
}


@media (min-width: 768px) {
  .rt-container {
    width: 750px;
  }
  [class^="col-rt-"] {
    float: left;
    width: 49.9999999999%;
  }
  .col-rt-6, .col-rt-12 {
    width: 100%;
  }
  
}

@media (min-width: 1200px) {
	.rt-container {
		width: 1170px;
	}
	.col-rt-1 {
		width:16.6%;
	}
	.col-rt-2 {
		width:30.33%;
	}
	.col-rt-3 {
		width:50%;
	}
	.col-rt-4 {
		width: 67.664%;
	}
	.col-rt-5 {
		width: 83.33%;
	}
	

}

@media only screen and (min-width:240px) and (max-width: 768px){
	 .ScriptTop h1, .ScriptTop ul {
		text-align: center;
	}
	.ScriptTop h1{
		margin-top:0;
		margin-bottom:15px;
	}
	.ScriptTop ul{
		 margin-top:12px;		
	}
	
	.ScriptHeader h1,
	.ScriptHeader h2, 
	.scriptnav ul{
		text-align:center;	
	}
	.scriptnav ul{
		 margin-top:12px;		
	}
	#float-right{
		float:none;	
	}
	
}


