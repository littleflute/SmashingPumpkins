[v0.0.7](https://github.com/littleflute/SmashingPumpkins/edit/master/Gish%20%5BLP%5D/readme.md)
 
 
[Gish (Deluxe Edition CD-DVD) Disc 2](Gish [Deluxe Edition CD-DVD] Disc 2)

[Gish (LP)](Gish [LP])


<audio controls id="player"> 
  <source src="https://littleflute.github.io/SmashingPumpkins/Gish [LP]/01 I Am One.mp3" type="audio/mpeg">
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
    var s = "https://littleflute.github.io/SmashingPumpkins/Gish [LP]/";
    if(i==1)
    {
    	s += "01 I Am One";
    }
    else if(i==2)
    {
    	s += "02 Siva";
    }
    else if(i==3)
    {
    	s += "03 Rhinoceros";
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

