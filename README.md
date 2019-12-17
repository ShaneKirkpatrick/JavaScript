<!DOCTYPE html>
<html>
/*
Variables cannot start w/ numbers, only use letters, numbers, or underscores
Variable types: numbers, strings, true and false, null
*/
<head>
</head>
<body>

<script type="text/javascript">
  
  var x = 23;
  var pasion = "text string here \"this is in quotes\"";
  var love = 30;
  
  function funky (){
	  alert ("alert box");}
  
  document.write("  This is all I should see! ");
  document.write( x );
  document.write( love );
  
  function todaysAmbassadors (x){
   	alert ("Today We are featuring: " + x);}

todaysAmbassadors ("Ben");
todaysAmbassadors ("Teri");
todaysAmbassadors ("Mohamad");

function calculate(a,b) {
		var c = a+b;
		return c;
	}
  
document.write(calculate(4,7));
  
 function doFirst(){
		document.write("I am first YO!");
	}
function doSecond(){
		document.write("second friggin one you wak arsonal of 			deep knowlege!");
	}
function start () {
		doFirst ();
		doSecond ();
	}
start();

</script>

<form>
<input type="button" value="Click Here" onclick="funky();">
</form>
</body>

</html>
