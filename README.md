Added new methods to lock or unlock scrolling on the X/Y axis
Added methods to go to previous or next page
-<code>
function loaded() {
	myScroll = new TWIS('#wrapper',{upDownOn:0});
	myScroll.blockUpDown()
	myScroll.unblockUpDown()
	myScroll.blockLeftRight()
	myScroll.unblockLeftRight()
	myScroll.blockLeft()
	myScroll.unblockLeft()
	myScroll.blockRight()
	myScroll.unblockRight()
	myScroll.nextPage(300);
	myScroll.prevPage(300);
}
-</code>
Adds new contruction parameetrs, set 0 or 1 to turn the axis on or off

-<code>
	myScroll = new TWIS('#wrapper',{
		upDownOn:0,
		leftOn:0,
		rightOn:0
	});
-</code>


