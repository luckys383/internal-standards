## Wrapper Class

Create a new class check isTrue, isDefined and etc. Which help you in future one chamage for in APP and if any exception is you can manage from one place.

eg.
```
var a = "false";


<!-- bad  -->
if( a ) {
	console.log("Work");
}

<!-- Good -->
if( ClassName.isTrue(a) ) {
	console.log("Work");
}

<!-- ClassName.isTrue -->
 ClassName.isTrue = function(val) {
	if( val === true || val == "true" || val == 1 ) {
		return true
	}

	return false
}
```