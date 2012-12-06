
Added new methods to lock or unlock scrolling on the X/Y axis
Added methods to go to previous or next page
<pre>
function loaded() {
	myScroll = new TWIS('#wrapper',{upDownOn:0});
	myScroll.blockUpDown();
	myScroll.unblockUpDown();
	myScroll.blockLeftRight();
	myScroll.unblockLeftRight();
	myScroll.blockLeft();
	myScroll.unblockLeft();
	myScroll.blockRight();
	myScroll.unblockRight();
	myScroll.nextPage(300);
	myScroll.prevPage(300);
}

When you create a new instance of TWIS you can set the axis locking using these parameters and setting them to 1 or 0

<pre>
	myScroll = new TWIS('#wrapper',{
		upDownOn:1,
		leftOn:0,
		rightOn:0
	});
</pre>


