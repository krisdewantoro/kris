<head> 
 
<style type="text/css">body{cursor: url("http://cursor.com/images/12a.gif"), auto;}body a:hover{cursor: url("http://cursor.com/images/12a.gif"), auto;}</style> 
 

<meta name="robots" content="NOINDEX, NOFOLLOW"> 
 
 
<meta name="description" content="Love You Liaa"> 
 
 
<meta name="keyword" content=" sahabat-keyboard"> 
 
<link rel="shortcut icon" href="http://1.bp.blogspot.com/_f6lBtRRQnaQ/S2t_zr0Jc-I/AAAAAAAAAFM/fZM1Hu8zezM/s320/TransLoveLogo.jpg" /> 
 
 
<script language="JavaScript"> 
 
 
var txt=" Just For You Nurul ";
 
 
var kecepatan=75;var segarkan=null;function bergerak() { document.title=txt;
 
 
txt=txt.substring(1,txt.length)+txt.charAt(0);
 
 
segarkan=setTimeout("bergerak()",kecepatan);}bergerak();
 
 
</script> 
 
 
 
 
 
<style type="text/css"> 
 
 
body {background:#000000 url() repeat scroll center 0;
 
 
</style> 
 
 
<link href="http://png-3.findicons.com/files//icons/376/the_blacy/128/black_heart.png"> 
 
<script type="text/javascript"> 
 
 
TypingText = function(element, interval, cursor, finishedCallback) {
 
 
  if((typeof document.getElementById == "undefined") || (typeof element.innerHTML == "undefined")) {
 
 
    this.running = true;	// Never run.
 
 
    return;
 
 
  }
 
 
  this.element = element;
 
 
  this.finishedCallback = (finishedCallback ? finishedCallback : function() { return; });
 
 
  this.interval = (typeof interval == "undefined" ? 20 : interval);
 
 
  this.origText = this.element.innerHTML;
 
 
  this.unparsedOrigText = this.origText;
 
 
  this.cursor = (cursor ? cursor : "");
 
 
  this.currentText = "";
 
 
  this.currentChar = 0;
 
 
  this.element.typingText = this;
 
 
  if(this.element.id == "") this.element.id = "typingtext" + TypingText.currentIndex++;
 
 
  TypingText.all.push(this);
 
 
  this.running = false;
 
 
  this.inTag = false;
 
 
  this.tagBuffer = "";
 
 
  this.inHTMLEntity = false;
 
 
  this.HTMLEntityBuffer = "";
 
 
}
 
 
TypingText.all = new Array();
 
 
TypingText.currentIndex = 0;
 
 
TypingText.runAll = function() {
 
 
  for(var i = 0; i < TypingText.all.length; i++) TypingText.all[i].run();
 
 
}
 
 
TypingText.prototype.run = function() {
 
 
  if(this.running) return;
 
 
  if(typeof this.origText == "undefined") {
 
 
    setTimeout("document.getElementById('" + this.element.id + "').typingText.run()", this.interval);	// We haven't finished loading yet.  Have patience.
 
 
    return;
 
 
  }
 
 
  if(this.currentText == "") this.element.innerHTML = "";
 
 
//  this.origText = this.origText.replace(/<([^<])*>/, "");     // Strip HTML from text.
 
 
  if(this.currentChar < this.origText.length) {
 
 
    if(this.origText.charAt(this.currentChar) == "<" && !this.inTag) {
 
 
      this.tagBuffer = "<";
 
 
      this.inTag = true;
 
 
      this.currentChar++;
 
 
      this.run();
 
 
      return;
 
 
    } else if(this.origText.charAt(this.currentChar) == ">" && this.inTag) {
 
 
      this.tagBuffer += ">";
 
 
      this.inTag = false;
 
 
      this.currentText += this.tagBuffer;
 
 
      this.currentChar++;
 
 
      this.run();
 
 
      return;
 
 
    } else if(this.inTag) {
 
 
      this.tagBuffer += this.origText.charAt(this.currentChar);
 
 
      this.currentChar++;
 
 
      this.run();
 
 
      return;
 
 
    } else if(this.origText.charAt(this.currentChar) == "&" && !this.inHTMLEntity) {
 
 
      this.HTMLEntityBuffer = "&";
 
 
      this.inHTMLEntity = true;
 
 
      this.currentChar++;
 
 
      this.run();
 
 
      return;
 
 
    } else if(this.origText.charAt(this.currentChar) == ";" && this.inHTMLEntity) {
 
 
      this.HTMLEntityBuffer += ";";
 
 
      this.inHTMLEntity = false;
 
 
      this.currentText += this.HTMLEntityBuffer;
 
 
      this.currentChar++;
 
 
      this.run();
 
 
      return;
 
 
    } else if(this.inHTMLEntity) {
 
 
      this.HTMLEntityBuffer += this.origText.charAt(this.currentChar);
 
 
      this.currentChar++;
 
 
      this.run();
 
 
      return;
 
 
    } else {
 
 
      this.currentText += this.origText.charAt(this.currentChar);
 
 
    }
 
 
    this.element.innerHTML = this.currentText;
 
 
    this.element.innerHTML += (this.currentChar < this.origText.length - 1 ? (typeof this.cursor == "function" ? this.cursor(this.currentText) : this.cursor) : "");
 
 
    this.currentChar++;
 
 
    setTimeout("document.getElementById('" + this.element.id + "').typingText.run()", this.interval);
 
 
  } else {
 
 
	this.currentText = "";
 
 
	this.currentChar = 0;
 
 
        this.running = false;
 
 
        this.finishedCallback();
 
 
  }
 
 
}
 
 
</script> 
 
 
 
 
 
 
 
 
</head> 
<script src='http://misbahudin-dcaesga.googlecode.com/files/efek-salju.js'/> 
<script src='http://misbahudin.googlecode.com/files/daun%20gugur.js'/>
 
 
 
 
<body oncontextmenu='return false;' onkeydown='return false;' onmousedown='return false;'>
 
 
<script type='text/javascript'>
 
 
//<![CDATA[
 
 
var message="Hacker Newbie Was Here";
 
 
function clickIE() {if (document.all) {(message);return false;}}
 
 
function clickNS(e) {if (document.layers||(document.getElementById&&!document.all)) {
 
 
if (e.which==2||e.which==3) {(message);return false;}}}
 
 
if (document.layers)
 
 
{document.captureEvents(Event.MOUSEDOWN);document.onmousedown=clickNS;}
 
 
else{document.onmouseup=clickNS;document.oncontextmenu=clickIE;}
 
 
document.oncontextmenu=new Function("return false")
 
 
//]]>
 
 
</script> 
 
 
 
 
 
<script type="text/javascript"> 
<script language="javascript" src="http://zianxfly.250free.com/js/saljucursorfuchsia.js
"></script> 
 
 
 
 
 
 
 
</SCRIPT> 
 
 
 
 
 
<h1>
<center>
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
 
 
document.write("<span id='a"+i+"' class='a"+i+"'>"+Buchstabe[i] + "</span>"); 
 
 
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
 
 
// 
 
 
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
 
 
text= "For You Nurul Septiani"; //h 
 
 
string2array(text);
 
 
divserzeugen(); 
 
 
//document.write(text); 
 
 
</SCRIPT></center>
</h1>
<table border="5" width="100%" height="300" cellpadding="5" bgcolor="black">
<tr> 
 
 
	<td width="30%" align="center" valign="center"> 
 
 
	<img src="IMG-20200629-WA0018.jpg"  align="middle" border="0" width="300" height="400" /><br />
 
 
 
 
	</td> 
 
 
 
	<td width="70%" align="center"> 
 
 
 
 
 
	<font color="#00BFFF" size="3"><code> 
 
 
<div id="example1">
</div>
<p id="example2">
:: <blink>Assalamu'alaikum Warahmatullahi Wabarakatuh</blink> :: <br /><br />  
 
 
===========================================<br /> 
Bagaimana kabarmu hari ini?.., <br>
semoga baik-baik saja<br>
selalu diberi kesehatan oleh Allah SWT<br>
jangan lupa minum air putih ya <br>
aku buat ini sebenarnya karena suatu hal<br>
<br> 
<br> 
sebenarnya udah sejak lama aku mau ngmong ini ke km<br>
tapi aku gak berani mengungkapkannya<br>
sebenernya udah sejak lama aku pengen bilang<br>
aku pen bilang kalau aku....<br>
AKU SUKA SAMA KAMU<br> 
AKU SAYANG SAMA KAMU<br>
<br>
<br>
mau nggk jd pacarku?<br>
please mau ya??<br>
yaa,,,<br>
ya ya ya........<br>
walaupun jauh aku gak akan nakal kok...<br>
aku sayang banget sama kamu Nurul<br>
bls ny lewat wa aja ya ^_^ <br>
<br>
<br>
aku tunggu ya nurul ^_^<br>
===========================================<br /> 
 
 
</p>
</object><object data="http://flash-mp3-player.net/medias/player_mp3.swf" width="0" height="0" type="application/x-shockwave-flash"><param value="#ffffff" name="bgcolor" /><center>
</object><object data="http://flash-mp3-player.net/medias/player_mp3.swf" width="0" height="0" type="application/x-shockwave-flash"><param value="#ffffff" name="bgcolor" /><param value="mp3=http://liaavaillere.esy.es/Hatsune%20Miku%20-%20Our%20Let%20it%20Be.mp3
&loop=1&autoplay=1&volume=125" name="FlashVars" /></object>
 
 
 
<script type="text/javascript"> 
 
 
//Define first typing example:
 
 
new TypingText(document.getElementById("example1"));
 
 
//Define second typing example (use "slashing" cursor at the end):
 
 
new TypingText(document.getElementById("example2"), 50, function(i){
 
 
var ar = new Array("_"," ","_","_"); return " " + ar[i.length %
 
 
ar.length]; });
 
 
//Type out examples:
 
 
TypingText.runAll();
 
 
</script></div>
</code></font> 
 
</td> 
 
 
 
 
 
</tr>
</table>
<table width="100%" border="5" bgcolor="pink">
<tr><td align="center"> 
 
 
 
 
 
</td></tr>
</table>
<br /> 
 
 
<br /> 
 
 
 
 
<table width="100%" border="2">
<tr> 
 
 
	<td width="15%" align="center"> 
 
 
	<font color="Gold"><code><blink>Pesan :<blink></code></font> 
 
 
 
 
 
	</td> 
 
 
 
 
 
	
 
 
	<td width="80%"> 
 
 
 
 
 
	<font color="Violet"> 
 
 
 
 
	<marquee><code> 
 
 
 
 
           <BR/> Jangan lupa balas yaaa??? aku tunggu loh ^_^ </blink><BR/> 
 
 
	</code></marquee> 
 
 
			  
 
 
	</font> 
 
 
 
 
	</td> 
 
 
 
 
</tr>
</html>    
 
</script> 
 
<script language="javascript" src="http://zianxfly.250free.com/js/saljucursoraqua.js"></script> 
 
<body background = "http://lh5.ggpht.com/_O3Mkjo7Ekyo/SjF22CmjbjI/AAAAAAAAA3o/yByfvwhYwuw/_br04.gif" style="cursor: crosshair">
//-->
</Script> 
 
<!-- Hosting24 Analytics Code --> 
 
<script type="text/javascript" src="http://stats.hosting24.com/count.php"></script> 
 
<!-- End Of Analytics Code -->
