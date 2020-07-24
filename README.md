## Welcome to GitHub (Jigar Vakil)


### RESUME USING HTML AND CSS



```markdown
PHP FILE :

<!DOCTYPE html>
<html>
<head>
<title>Jigar Vakil-Resume</title>


<link type="text/css" rel="stylesheet" href="style.css">

</head>
<body id="top">
<div id="cv" class="instaFade">
	<div class="mainDetails">
		<div id="headshot">
			<img src="1.jpg" alt="Jigar Vakil" />
		</div>
		
		<div id="name">
			<h1>Jigar Vakil</h1> <p>Address: 48, Silver Park,Barbodhan Village, Surat</p>
			
		</div>
		
		<div id="contactDetails">
            <ul>
				<li>email: <a href="mailto:jigarvakil011@gmail.com" target="_blank">Jigarvakil011@gmail.com</a></li>
				<li>mobile: 9824619885</li>
				<li>Birth Date: 11-04-1999</li>
			</ul>
		</div>
		<div class="clear"></div> 
	</div>
	
	<div id="mainArea">
		
		
		
		<section>
			<div class="sectionTitle">
				<h1>Work Experience</h1>
			</div>
			
			<div class="sectionContent">
				<div>
					<h2>PhP Devloper</h2>
					<p class="subDetails">April 2019 - April 2020</p>
					<p>At :CloudZsoft, Netx-iit, 1st floor ,balaji market, balaji road,near lalgate, surat </p>
				</div>				
			</div>
			<div class="clear"></div>
		</section>
		
		
		<section>
			<div class="sectionTitle">
				<h1>Key Skills</h1>
			</div>
			
			<div class="sectionContent">
				<ul class="keySkills">
					<li>HTML</li>
					<li>CSS</li>
					<li>JAVASCRIPT</li>
					<li>PHP</li>
					<li>CodeIgniter</li>
				</ul>
			</div>
			<div class="clear"></div>
		</section>
		
		
		<section>
			<div class="sectionTitle">
				<h1>Education</h1>
			</div>
			
			<div class="sectionContent">
				<div>
					<h3>SSC (GSEB) </h3>
					<p>School: L.P.Savani Vidhyabhavan</p>
					<p>Year- 2014 <br> Percantage: 66%</p>
				</div>
                
                <div>
					<h3>HHC (GSHEB) </h3>
					<p>School: Sanskar Bharti Vidhyala</p>
					<p>Year- 2016 <br> Percantage: 66%</p>
                </div>
                
                <div>
					<h3>BCA (VNSGU) </h3>
					<p>College: C.B.Paltel Computer College</p>
					<p>Year- 2019 <br> CGPA: 7.74 </p>
				</div>
				
			</div>
			<div class="clear"></div>
		</section>
		
    </div>
    <hr>
    <div style="margin-left:20px">

    <h3>Declaration</h3>
            <p>
            I hereby declare that the details furnished above are true and correct to the best of my knowledge and belief.</p>
<br>
<br>
    </div>
</div>
</body>
</html>


```

```markdown
CSS File:



html, body {background: #181818; font-family: 'Lato', helvetica, arial, sans-serif; font-size: 16px; color: #222;}

.clear {clear: both;} /*Do not allow element to float both side*/


#cv {
	width: 90%;
	max-width: 800px;
	background: #f3f3f3;
	margin: 30px auto;
}

.mainDetails {
	padding: 25px 35px;
	border-bottom: 2px solid #cf8a05;
	background: #ededed;
	
}

#name h1 {
	font-size: 36px;
	font-weight: 700;
	font-family: 'Rokkitt', Helvetica, Arial, sans-serif;
	margin-top:  -10px ;
}

#name h2 {
	font-size: 2em;
	margin-left: 2px;
	font-family: 'Rokkitt', Helvetica, Arial, sans-serif;
}

#mainArea {
	padding: 0 40px;
}

#headshot {
	width: 12.5%;
	float: left;
	margin-right: 30px;
}

#headshot img {
	width: 100%;
	height: 100%;
	border-radius: 50px;
}

#name {
	float: left;
}

#contactDetails {
	float: right;
}

#contactDetails ul {
	list-style-type: none;
	font-size: 15px;
	margin-top: 15px;
}

#contactDetails li {
	margin-top: 15px;
}
#contactDetails ul li {
	margin-bottom: 3px;
	color: #444;
}


#contactDetails ul li a:hover { 
	color: #cf8a05;
}


section {
	border-top: 1px solid #dedede;
	padding: 20px 0 0;
}

section:first-child {
	border-top: 0;
}

section:last-child {
	padding: 20px 0 10px;
}

.sectionTitle {
	float: left;
	width: 25%;
}

.sectionContent {
	float: right;
	width: 72.5%;
}

.sectionTitle h1 {
	font-family: 'Rokkitt', Helvetica, Arial, sans-serif;
	font-style: italic;
	font-size: 20px;
	color: #cf8a05;
}

.sectionContent h2 {
	font-family: 'Rokkitt', Helvetica, Arial, sans-serif;
	font-size: 20px;
	margin-bottom: -2px;
}



.keySkills {
	list-style-type: none;
	column-count:3;
	margin-bottom: 40px;
	font-size: 18px;
	margin-left: -50px;
	color: #444;
}

.keySkills li {
	margin: 10px;
}

```


### Devloper Information
Email : jigarvakil9200@gmail.com
