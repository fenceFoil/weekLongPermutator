Look: sharply minimal, black background, no transition changes to imitate best parts of my favorite led clock. more lights == more patterns though.

Get 6x4 marble svgs into a html file under a div.
Write css classes to hide one and show one. 
- NO TRANSITIONS IN AND OUT
Write css to add bloom around each one
Arrange into a 6x4 grid

Write script to:
- depict a counter upon the grid
- increment the counter at an appropriate frequency (10x update speed?) to go along with the clock
- calculate the counter value given the time within the current week and the length of the current week
	- tinker with this effect; maybe week is too long/short? maybe could make work with different sized grid?
		- consider changing grid by making it ragged at top like my binary clock

Scale nicely for phones, tablets

Upload and send address to work for idle screens
Set up at home on kiosk screen

---

Next up: make an attractive epoch clock.

:class="lit = ((2**(light.position+1)) % currCount) == 0"