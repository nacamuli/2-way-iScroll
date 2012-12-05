Added new methods to lock or unlock scrolling on the X/Y axis

twis.blockUpDown()
twis.unblockUpDown()
twis.blockLeftRight()
twis.unblockLeftRight()
twis.blockLeft()
twis.unblockLeft()
twis.blockRight()
twis.unblockRight()

Adds new contruction parameers, set 0 or 1 to turn the axis on or off

	myScroll = new TWIS('#wrapper',{
		upDownOn:0,
		leftOn:0,
		rightOn:0,
	});



