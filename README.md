<html><head>
<title>Hacked By Robin Tr!gon </title>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<meta name="keywords" content="Hacked By Tr!gon ">
<meta name="description" content="Hacked By Alian warrioR ">
<link href="http://oi68.tinypic.com/2wemcs8.jpg" rel="SHORTCUT ICON">
<html>
<head>
</head>
<center>
<font style="color:aqua;text-shadow:0px 1px 5px #000;font-size:85px" face="Iceland"><span class="blink_text">HACKED BY ROBIN TR!GON </span></font>
<style type="text/css">



  body {

    height: 100%;

    width: 100%;

    padding: 0;

    margin: 0;

    background-image: url('https://images7.alphacoders.com/718/718427.png');

    background-repeat: no-repeat;

    background-color: #000000;

    color: #FFFFFF;

    font-family: "Special Elite";

    font-size: 14pt;

    text-decoration: none;





</style>
</head>
<body bgcolor="#000000">
<script type="text/javascript" src="http://htmlfreecodes.com/codes/rain.js"></script>
<table height="20%" width="100%"><tbody><tr><td align="center">
<div align="center">
<script>

farbbibliothek = new Array(); 

farbbibliothek[0] = new Array("#FF0000","#FF1100","#FF2200","#FF3300","#FF4400","#FF5500","#FF6600","#FF7700","#FF8800","#FF9900","#FFaa00","#FFbb00","#FFcc00","#FFdd00","#FFee00","#FFff00","#FFee00","#FFdd00","#FFcc00","#FFbb00","#FFaa00","#FF9900","#FF8800","#FF7700","#FF6600","#FF5500","#FF4400","#FF3300","#FF2200","#FF1100"); 

farbbibliothek[1] = new Array("#00FF00","#000000","#00FF00","#00FF00"); 

farbbibliothek[2] = new Array("#00FF00","#FF0000","#00FF00","#00FF00","#00FF00","#00FF00","#00FF00","#00FF00","#00FF00","#00FF00","#00FF00","#00FF00","#00FF00","#00FF00","#00FF00","#00FF00","#00FF00","#00FF00","#00FF00","#00FF00","#00FF00","#00FF00","#00FF00","#00FF00","#00FF00","#00FF00","#00FF00","#00FF00","#00FF00","#00FF00","#00FF00","#00FF00","#00FF00","#00FF00","#00FF00","#00FF00"); 

farbbibliothek[3] = new Array("#FF0000","#FF4000","#FF8000","#FFC000","#FFFF00","#C0FF00","#80FF00","#40FF00","#00FF00","#00FF40","#00FF80","#00FFC0","#00FFFF","#00C0FF","#0080FF","#0040FF","#0000FF","#4000FF","#8000FF","#C000FF","#FF00FF","#FF00C0","#FF0080","#FF0040"); 

farbbibliothek[4] = new Array("#FF0000","#EE0000","#DD0000","#CC0000","#BB0000","#AA0000","#990000","#880000","#770000","#660000","#550000","#440000","#330000","#220000","#110000","#000000","#110000","#220000","#330000","#440000","#550000","#660000","#770000","#880000","#990000","#AA0000","#BB0000","#CC0000","#DD0000","#EE0000"); 

farbbibliothek[5] = new Array("#000000","#000000","#000000","#FFFFFF","#FFFFFF","#FFFFFF"); 

farbbibliothek[6] = new Array("#0000FF","#FFFF00"); 

farben = farbbibliothek[4];

function farbschrift() 

{ 

for(var i=0 ; i<Buchstabe.length; i++) 

{ 

document.all["a"+i].style.color=farben[i]; 

} 

farbverlauf(); 

} 

function string2array(text) 

{ 

Buchstabe = new Array(); 

while(farben.length<text.length) 

{ 

farben = farben.concat(farben); 

} 

k=0; 

while(k<=text.length) 

{ 

Buchstabe[k] = text.charAt(k); 

k++; 

} 

} 

function divserzeugen() 

{ 

for(var i=0 ; i<Buchstabe.length; i++) 

{ 

document.write("<font face='monotype corsiva' size=30><span id='a"+i+"' class='a"+i+"'>"+Buchstabe[i] + "</span></font>"); 

} 

farbschrift(); 

} 

var a=1; 

function farbverlauf() 

{ 

for(var i=0 ; i<farben.length; i++) 

{ 

farben[i-1]=farben[i]; 

} 

farben[farben.length-1]=farben[-1]; 



setTimeout("farbschrift()",30); 

} 

// Zu Demonstrationszwecken***************** 

var farbsatz=1; 

function farbtauscher() 

{ 

farben = farbbibliothek[farbsatz]; 

while(farben.length<text.length) 

{ 

farben = farben.concat(farben); 

} 

farbsatz=Math.floor(Math.random()*(farbbibliothek.length-0.0001)); 

} 

setInterval("farbtauscher()",5000); 

text= "#WE ARE BANGLADESHI ETHICAL HACKER";

string2array(text); 

divserzeugen();

//document.write(text); 

</script>
</td></table>

<script type="text/javascript">

    // <![CDATA[

    var sparks=75;

    var speed=33;

    var bangs=5;

    var colours=new Array('#03f', '#f03', '#0e0', '#93f', '#0cf', '#f93', '#f0c');

     

    var intensity=new Array();

    var Xpos=new Array();

    var Ypos=new Array();

    var dX=new Array();

    var dY=new Array();

    var stars=new Array();

    var decay=new Array();

    var timers=new Array();

    var swide=800;

    var shigh=600;

    var sleft=sdown=0;

    var count=0;

     

    function addLoadEvent(funky) {

      var oldonload=window.onload;

      if (typeof(oldonload)!='function') window.onload=funky;

      else window.onload=function() {

        if (oldonload) oldonload();

        funky();

      }

    }

     

    addLoadEvent(clicksplode);

     

    function clicksplode() { if (document.getElementById) {

      var i, j;

      window.onscroll=set_scroll;

      window.onresize=set_width;

      document.onclick=eksplode;

      set_width();

      set_scroll();

      for (i=0; i<bangs; i++) for (j=sparks*i; j<sparks+sparks*i; j++) {

        stars[j]=createDiv('*', 13);

        document.body.appendChild(stars[j]);

      }

    }}

     

    function createDiv(char, size) {

      var div, sty;

      div=document.createElement('div');

      sty=div.style;

      sty.font=size+'px monospace';

      sty.position='absolute';

      sty.backgroundColor='transparent';

      sty.visibility='hidden';

      sty.zIndex='101';

      div.appendChild(document.createTextNode(char));

      return (div);

    }

     

    function bang(N) {

      var i, Z, A=0;

      for (i=sparks*N; i<sparks*(N+1); i++) {

        if (decay[i]) {

          Z=stars[i].style;

          Xpos[i]+=dX[i];

          Ypos[i]+=(dY[i]+=1.25/intensity[N]);

          if (Xpos[i]>=swide || Xpos[i]<0 || Ypos[i]>=shigh+sdown || Ypos[i]<0) decay[i]=1;

          else {

            Z.left=Xpos[i]+'px';

            Z.top=Ypos[i]+'px';

          }

          if (decay[i]==15) Z.fontSize='7px';

          else if (decay[i]==7) Z.fontSize='2px';

          else if (decay[i]==1) Z.visibility='hidden';

          decay[i]--;

        }

            else A++;

      }

      if (A!=sparks) timers[N]=setTimeout('bang('+N+')', speed);

    }

     

    function eksplode(e) {

      var x, y, i, M, Z, N;

      set_scroll();

      y=(e)?e.pageY:event.y+sdown;

      x=(e)?e.pageX:event.x+sleft;

      N=++count%bangs;

      M=Math.floor(Math.random()*3*colours.length);

      intensity[N]=5+Math.random()*4;

      for (i=N*sparks; i<(N+1)*sparks; i++) {

        Xpos[i]=x;

        Ypos[i]=y-5;

        dY[i]=(Math.random()-0.5)*intensity[N];

        dX[i]=(Math.random()-0.5)*(intensity[N]-Math.abs(dY[i]))*1.25;

        decay[i]=16+Math.floor(Math.random()*16);

        Z=stars[i].style;

        if (M<colours.length) Z.color=colours[i%2?count%colours.length:M];

        else if (M<2*colours.length) Z.color=colours[count%colours.length];

        else Z.color=colours[i%colours.length];

        Z.fontSize='13px';

        Z.visibility='visible';

      }

      clearTimeout(timers[N]);

      bang(N);

    }

     

    function set_width() {

      var sw_min=999999;

      var sh_min=999999;

      if (document.documentElement && document.documentElement.clientWidth) {

        if (document.documentElement.clientWidth>0) sw_min=document.documentElement.clientWidth;

        if (document.documentElement.clientHeight>0) sh_min=document.documentElement.clientHeight;

      }

      if (typeof(self.innerWidth)=='number' && self.innerWidth) {

        if (self.innerWidth>0 && self.innerWidth<sw_min) sw_min=self.innerWidth;

        if (self.innerHeight>0 && self.innerHeight<sh_min) sh_min=self.innerHeight;

      }

      if (document.body.clientWidth) {

        if (document.body.clientWidth>0 && document.body.clientWidth<sw_min) sw_min=document.body.clientWidth;

        if (document.body.clientHeight>0 && document.body.clientHeight<sh_min) sh_min=document.body.clientHeight;

      }

      if (sw_min==999999 || sh_min==999999) {

        sw_min=800;

        sh_min=600;

      }

      swide=sw_min-7;

      shigh=sh_min-7;

    }

     

    function set_scroll() {

      if (typeof(self.pageYOffset)=='number') {

        sdown=self.pageYOffset;

        sleft=self.pageXOffset;

      }

      else if (document.body && (document.body.scrollTop || document.body.scrollLeft)) {

        sdown=document.body.scrollTop;

        sleft=document.body.scrollLeft;

      }

      else if (document.documentElement && (document.documentElement.scrollTop || document.documentElement.scrollLeft)) {

        sleft=document.documentElement.scrollLeft;

        sdown=document.documentElement.scrollTop;

      }

      else {

        sdown=0;

        sleft=0;

      }

    }

    // ]]>

    </script>

<script language="JavaScript"> 

<!-- Disable 

function disableselect(e){ 

return false 

} 



function reEnable(){ 

return true 

} 



//if IE4+ a Function ("return false") 

//if NS6 

if (window.sidebar){ 

document.onmousedown=disableselect 

document.onclick=reEnable 

} 

//--> 

</script>
<head>
<meta http-equiv="Content-Language" content="en-us">
<meta http-equiv="Content-Type" content="text/html; charset=windows-1252">
<meta content="#Operation Hexolz WolF | " name="description" />
<meta content="#Operation Hexolz WolF | " name="keywords" />
<meta content="#Hexloz wolF: |" name="Abstract" />
<meta name="#Operation Hexloz wolF " />
<link rel="icon" href="http://oi68.tinypic.com/2wemcs8.jpg">
<title>#Operation Hexolz WolF | </title>
<style type="text/css">

h1 {color: #333;font-size: 100px;margin: 1px auto;text-align:center;text-transform:uppercase; font-family:Orbitron;}

.neon {color: #FFFFFF;text-shadow: 0 0 5px #1ab4e7, 0 0 10px #1ab4e7, 0 0 30px #18a2d0, 0 0 45px #18a2d0, 0 0 60px #18a2d0;}





h2 {color: #333;font-size: 50px;margin: 1px auto;text-align:center;text-transform:uppercase; font-family:Audiowide;}

.neon {color: #FFFFFF;text-shadow: 0 0 5px #1ab4e7, 0 0 10px #1ab4e7, 0 0 30px #18a2d0, 0 0 45px #18a2d0, 0 0 60px #18a2d0;}



h3 {color: #333;font-size: 50px;margin: 1px auto;text-align:center;text-transform:uppercase; font-family:Audiowide;}

.neon {color: #FFFFFF;text-shadow: 0 0 5px #1ab4e7, 0 0 10px #1ab4e7, 0 0 30px #18a2d0, 0 0 45px #18a2d0, 0 0 60px #18a2d0;}





.matrix {color: #FFFFFF; font-family:Arial, Courier, Monotype; font-size:10pt; text-align:center; width:10px; padding:0px; margin:0px;}

.jokitz1{

	text-align : center;

	}

.jokitz2{

	text-align : center;

	font-family : Courier;

	}

</style>
</head>
<body bgcolor=black lang=EN-US style='tab-interval:36.0pt; text-align:center'> <onload=type_text() onclick='alert("Use your brain don' t copy code ?? ")'>
<style>body{cursor:url("http://www.rw-designer.com/cursor-extern.php?id=125977=.swf"),auto;}html{display:table;height:100%;width:100%;}body{display:table-row;}body{display:table-cell;vertical-align:middle;text-align:center;}a:link{text-decoration:none;}</style><link href='http://fonts.googleapis.com/css?family=Iceland' rel='stylesheet' type='text/css'>
<link href='http://fonts.googleapis.com/css?family=Orbitron:700' rel='stylesheet' type='text/css'>
<link href='http://fonts.googleapis.com/css?family=Audiowide' rel='stylesheet' type='text/css'>
<link href='http://fonts.googleapis.com/css?family=Iceland' rel='stylesheet' type='text/css'>
<p align="center" dir="ltr"></p>
<script type="text/javascript">



<!--



//Disable right click script



//visit http://www.rainbow.arch.scriptmania.com/scripts/



var message="Operation Hexolz WolF!! ?? ";



///////////////////////////////////



function clickIE() {if (document.all) {(message);return false;}}



function clickNS(e) {if



(document.layers||(document.getElementById&&!document.all)) {



if (e.which==2||e.which==3) {(message);return false;}}}



if (document.layers)



{document.captureEvents(Event.MOUSEDOWN);document.onmousedown=clickNS;}



else{document.onmouseup=clickNS;document.oncontextmenu=clickIE;}



document.oncontextmenu=new Function("return false")



// -->



</script>

<center>
<font face="Iceland" style="color:white;text-shadow:0px 1px 5px #000;font-size:60px">Your system</font><font face="Iceland" style="color:green;text-shadow:0px 1px 5px #000;font-size:60px"> H4CK3D By</font><br>
<font style="font-size:90px;text-shadow: 0 0 3px red, 0px 0px 5px red">HexolZ wolF</font>
<font style="font-size:55px;text-shadow: 0 0 50px red, 0px 0px 5px red">.</font>
<br><img src="http://www6.0zz0.com/2011/03/14/06/269205957.gif" id="button1" name="button1" border="0" height="7" width="502"></center><br>
<font face="Iceland" style="color:#00FFFF;text-shadow:0px 1px 5px #000;font-size:30px">"TIGER KING OF ANIMAL,</font>
<font face="Iceland" style="color:#00FFFF;text-shadow:0px 1px 5px #000;font-size:30px">WE ARE NOT A CRIMINAL,</font>
<font face="Iceland" style="color:#00FCFF;text-shadow:0px 1px 5px #000;font-size:30px">WE ARE NOT A TERRORIST"<font color=#0051FF></font></a><br>
<font face="Iceland" style="color:#00FCFF;text-shadow:0px 1px 5px #000;font-size:30px">[#] <a href="https://www.facebook.com/MDrabiulhossenshahrouf786"><font color="Red"><font color="White"><font color="Red">:::#HexolZWolF Hacker Society!!!:::</font> </font> </font> </a>
<br>
<font color="Red">Mess</font><font color="White">age:</font>
<br>
<iframe width="0" height="0" scrolling="no" frameborder="no" src="https://www.youtube.com/embed/zI9vJOMEvZ0?rel=0;&autoplay=1" frameborder="0" allowfullscreen></iframe>
</body>
</html>
<center>
<font face="Comic Sans MS" size="4" color="Red">Hello Admin secure your website OtherWise We Come Back Again</font>
<font face="Comic Sans MS" size="4" color="White">YOUR ALL DATABASE ARE SAFE<br>..::Remember::..<br> </font> <font face="Comic Sans MS" size="4" color="Red">HexolzWolF king Of BANGLADESH Cyber World </font>
<br>
<audio autoplay="" controls>
  <source src="https://audiohunter.ru/getmp3/0/MzkyMjcwNzE5XzQ1NjIzOTM2MF9mNTExOWUwZjE5YWJlYjRmMzhfZDAzMmNmMDVjZjVjZWNmYTkyLzwhfCE-WyJncyIsMCwiUGxhaW4rSmFuZSslRTIlODAlOTMrUm9iZXJ0bytrYW4rUmVtaXgiLDEsbnVsbCwwLDUwLDBd/A+AP+Ferg+-+Plain+Jane+%28Remix+Roberto+Kan%29_(audiohunter.ru)/A+AP+Ferg+%E2%80%93+Plain+Jane+%28Remix+Roberto+Kan%29_(audiohunter.ru)?s=vk" type="audio/mp3">
 
Your browser does not support the audio element.
</audio>
</center>
<img src="http://www6.0zz0.com/2011/03/14/06/269205957.gif" id="button1" name="button1" border="0" height="7" width="502"></center>
<font size="5" color="WHITE"><center><marquee> Greetz[#]:-: <font size="5" color="green">: || R1KU5 V1RU5 || C4LV1N 8RUC3m || JON ROO7 COD3R ||GLnZO GbZaX61 TT || ALiaN Warrior ||<font size="5" color="red">|| Haxor N1l0y || CR45H COD3 || R5.70M || Fu B4B4 || D4RK ANON ||<font size="5" color="blue">|| BL41K 5P1D3R || Ack3rl3y 84rr0W || 3TH0 D053R TT || ADAAM HEXTOR || R4G3 F14M3 ||<font size="5" color="yellow">|| R00T W0LF Ju571n || R4PL15H M1KND0 || 3RROR C0D3R || M4TR1X 5P1D3R || Hidden Dna ||<font size="5" color="orange">|| R00t S0u1 || Wh17e W4lk3R || 70x1c 807 || M3CH0 8h007 || D474 GL17ch3R || & ALL BD HACKER </font><br>

</html>

