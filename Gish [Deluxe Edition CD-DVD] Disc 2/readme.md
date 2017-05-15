[v0.0.5](https://github.com/littleflute/SmashingPumpkins/edit/master/Gish%20%5BDeluxe%20Edition%20CD-DVD%5D%20Disc%202/readme.md)
 
 
[Gish (Deluxe Edition CD-DVD) Disc 2](Gish [Deluxe Edition CD-DVD] Disc 2)

<audio controls id="player"> 
  <source src="https://littleflute.github.io/SmashingPumpkins/Gish [Deluxe Edition CD-DVD] Disc 2/01 Starla [#][2011 Mix].mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
<div id="xd"> 
</div>
<script>
var d = document.getElementById("xd"); 
var html = d.innerHTML; 
html += " acdc<br>Highway To Hell [REMST]<br>CD:<br>";
for(var n=1; n<=19; n++)
{	
 	html += fNewBtn(n);

} 
d.innerHTML = html;

var p = document.getElementById("player");
function f(i)
{
    var s = "https://littleflute.github.io/SmashingPumpkins/Gish [Deluxe Edition CD-DVD] Disc 2/";
    if(i==1)
    {
    	s += "01 Starla [#][2011 Mix]";
    }
    else if(i==2)
    {
    	s += "02 Siva [Peel Session]";
    }
    else if(i==3)
    {
    	s += "03 Honeyspider [Demo Version][Reel Time Demos-2011 Mix]";
    }
    else
    {
    	if(i<10) 
    	{
    		s += "0";
    	} 
    	s += i;
    	s += "_曲目 ";
    	s += i;
    }
    s += ".mp3";
    
    p.src = s; 
    p.play();
}
function fNewBtn(i)
{
	var rHTML = "";
    rHTML = "<button onclick='f(";
    rHTML += i;
    rHTML += ");'>";
    rHTML += i;
    rHTML += "</button>";
    return rHTML;
}
</script>
