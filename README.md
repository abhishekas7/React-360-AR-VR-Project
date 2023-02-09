# React-360-AR-VR-Project
AR - VR Environment using React 360 Framework

Install React-360
------------------------------------
1 . npm install -g react-360-cli
2 . react-360 init Hello360

 Replace the variable declaration named sharedBlacklist
 .....

 var sharedBlacklist = [
        /node_modules[\/\\]react[\/\\]dist[\/\\].*/,
	/website\/node_modules\/.*/,
	/heapCapture\/bundle\.js/,
	/.*\/__tests__\/.*/
     ];


