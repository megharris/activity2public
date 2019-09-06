<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">

    <title>Activity 2 Meg Harris</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.4/css/bootstrap.min.css">
    <link rel="stylesheet" href="Activity2css.css" type="text/css" media="screen,projection" >
</head>
<body>

<br>
<br>

<header>
<h1>Activity 2: Meg Harris</h1>
</header>


<br>
<br>
  <div id="introduction">
      <section>
            <br>
              <img class="myimage" src="familypic.jpg"/ id=familypic>
              <p>

	I am a CPA (certified public accountant) and Accounting Instructor at 
	UNO. I currently teach introductory and intermediate managerial accounting 
	as well as Accounting Information Systems. Previously, I worked as a CPA in
	a variety of areas including tax, audit, public, private, retail, financial
	services, non-profit, energy, etc. My goal is to obtain a PhD in Information
	Technology/MIS and a tenure track position in the School of Accounting. 
	Additionally, I have two children and a third on the way. 

            </p>
            <br>
            <br>
	    <hr>




      </section>
  </div>

            <br>
            <br>
  <div id="racing">
      <section>
            <br>
              <img class="myimage" src="cobalt.jpg" id=cobalt/>
	    <p>
	For fun, our family is into drag racing. My husband races a Chevy Cobalt 
	and we are up for a championship this year! Drag racing is sometimes confused with 
	Nascar but in Nascar, the racers drive in circles whereas drag racing is on a straight
	track and is much shorter. The cars use a lot of power and the sport overall requires a
	lot of strategic preparation.
	    </p>
            <br>
            <br>


      </section>
  </div>

            <br>
            <br>
            <br>
            <br>






</body>
</html>


/*************************************
GENERAL
**************************************/
body {
   font-family: calibri;
 }


 #introduction {
   float: center;
   max-width: 940px;
   margin: 0 auto;
   padding: 0;

 }

 #racing {
   float: center;
   max-width: 940px;
   margin: 0 auto;
   padding: 0;

 }

/*************************************
HEADING
**************************************/
header {
  float: left;
  margin: 0 0 75px 0;
  padding: 3px 0 0 0;
  width: 100%;
  height: 100%;

}

 h1  {
 font-family: 'Changa One', calibri;
 margin: 8px;
 font-size: 50px;
 font-weight: normal;
 line-height: 0.5;
 text-align: center;

 }


 
/*************************************
PAGE:
**************************************/

.myimage{
    float: left;
    width:180px;
    height:175px;
    margin:20px;
    border-radius: 20px;
}






/*************************************
COLORS
**************************************/


 /* red header*/
header {
   background: #ff355e;
   border-color: #080808;
 }

 /* logo text*/

h1  {
    color: #080808;
}


/* site body*/
body {
    background-color: #18e5e0;
    color: #020fc3;
}
