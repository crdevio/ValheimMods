# WARNING
PLEASE USE BUILDSHARE (= v1.4)

# CHANGELOG:
	+ Added: ab undo : removes last placed building
	+ Added ab buildhelp : Displays more Text and examples of using ab build command
	+ Updated ab build [buildname] [x][y][z] [yRot] : yRot rotates building around player - changing its pivot and forward facing
	+ Updated ab save [radius] [buildname] [optional: save landscape? true/false] default to false - if false build save doesnt bring over any landscape data
	+ Updated Commands List to display ab share command which worked but wasn't on List
	+ Updated ab build functionality to use more optimized loop when placing building
	+ Updated ab build functionality to parent building to a single new gameObject for better handling and future improvements
	+ Updated ab save to limit number of decimals save data can go to, fixing rare bug when saving builds
