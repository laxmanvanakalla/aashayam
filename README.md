<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8"> 
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
  <link href="https://fonts.googleapis.com/css?family=Exo" rel="stylesheet">
<link href="https://fonts.googleapis.com/css?family=Share+Tech+Mono" rel="stylesheet">
    <style type="text/css">
    	.bord{

    		height: 100%;

    	}
    	.bor{
    		display:block;
    		font-family: 'Share Tech Mono', monospace;
    		letter-spacing: 3px;
    	    font-size: 1vw;
    		height: 20px;
    	}
    	.logo{
    		height: 150px;
    		padding: 0;
    	}
    	.ko{
    		max-height: 100%;
    		max-width: 100%;
    		display: block;
    		margin-left: auto;
    		margin-right: auto;
    
    	}
    	.po{
    		max-height: 100%;
    		min-width: 100%;
    		max-width: 100%;
    	}
    	.fn{
    		font-family: 'Exo', sans-serif;
            letter-spacing: 12px;
            text-align: center;
            font-size: 30px;
            color: #ffffff;
            font-weight: bold;
            background: #eb4f07;
            padding-left: 0px;
    	}
    	#sin,#pin{
    		display: inline;
    		font-size: 30px;
    		text-align: right;
    	}
    	a{
    		   color: #000000; 
    	}
    	a:hover{
    		color: #eb4f07;
    	}
    	.slide{
    		padding: 0;
    	
    	}
    	.image{
    		display: none;
    	}
    	p{
    		font-size: 25px;
    	}
    	.bot{
    		height: 200px;
    		background: #eb4f07;
    	}
    	.about{
    		text-align: center;
    		font-family: 'Exo', sans-serif;
    	}
    </style>
</head>
<body onload="putone()">
<div class="row">
	<div class="col-lg-8 bord" >
		<p> </p>

	</div>
	<div class="col-lg-4 bord" >
		<nav ><p id="sin">         </p><a>sign</a><p id="sin">     </p><a href="">register</a>  </nav>  
	</div>
</div>
<div class="col-lg-12 logo">
	<img   class="img-fluid ko"  src="C:\Users\RAMAN VANAKALLA\Desktop\AASHAYAM POSTERS\thisone.png">
</div>
<div class="row">
<div class="col-lg-12" style="padding: 0">
	<p class="fn">TO LITERATE INDIA</p>
</div>
</div>
<div class="row zom">
<div class="col-lg-3">
	
</div>
<div class="col-lg-6 ">
<nav class="lo">
	<div class="row">
	<div class="col-lg-3 bor"><a>EVENTS</a></div>
	<div class="col-lg-3 bor"><a>OCCASIONS</a></div>
	<div class="col-lg-3 bor"><a>SCHOOLS</a></div>
	<div class="col-lg-3 bor"><a>ORPHANAGES</a></div>
	</div>
</nav>
 </div>
 <div class="col-lg-3">
	
</div>
</div>
<p>   </p>
<div class="row">
<div class="col-lg-12 slide" >
	<div class="image" onclick="move(1)">
	<img   class="img-fluid po"  src="C:\Users\RAMAN VANAKALLA\Desktop\AASHAYAM POSTERS\123.jpg">
	</div>
	<div class="image" onclick="move(2)">
	<img  class="img-fluid po" src="C:\Users\RAMAN VANAKALLA\Desktop\AASHAYAM POSTERS\12.jpg">
	</div>
	<div class="image" onclick="move(0)">
	<img  class="img-fluid po " src="C:\Users\RAMAN VANAKALLA\Desktop\AASHAYAM POSTERS\13.jpg">
    </div>
</div>
</div>
<div class="row">
<div class="col-lg-3">
	
</div>
<div class="col-lg-6 about">
	<H1>
		ABOUT
	</H1>
	<p>
		Aashayam is a brainchild of the B.tech students of National Institute of Technology Warangal. Aimed at spreading the fruits of education to the grass root level and eradicating illiteracy ,Aashayam was born in January 2012 and is still talking baby steps in realizing its aim.
As its first step, Team Aashayam has taken Govt High School Kazipet into its domain and tried their best to achieve the maximum pass percentage in SSC Board Exams 2012.
Team Aashayam Reached about 300 students on the way of it's project "Melody of the Future" which involves Guiding them in choosing their future options and Team Aashayam is 53 members now and we hope to grow further. Our future road map, apart from bringing more and more schools into our domain and thus more and more number of students also includes spreading awareness about higher education and trying to make rural India realize the importance and value of education. We also wish to improve the strength in Government schools and decrease the number of dropouts through various counseling and mentoring sessions and activities for students as well as their family members.

The main aims of this venture can be summarized as:
1) teach students and their parents the importance of education.
2) reduce the number of dropouts from schools
3) improve pass percentage of school
4) interact with students, know their areas of interest and suggest them which course suits them
5) And finally encourage and train them so that they reach their goals
The ultimate aim is to help India achieve 100% LITERACY and to STOP CHILD LABOR

“Together lets contribute for a developed India”
	</p>
</div>
<div col-lg-3>
	
</div>
</div>

<div class="row bot">
	
</div>
</body>
<script type="text/javascript">
	function putone()
	{
		var slides=document.getElementsByClassName("image");
		slides[0].style.display="block";	
	}
	function move(movto)
	{
		var slides=document.getElementsByClassName("image");
		var i;
		for(i=0;i<slides.length;i++)
		{
			slides[i].style.display="none";
		}
		slides[movto].style.display="block";
	}
</script>
</html>
