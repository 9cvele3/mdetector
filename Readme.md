* IMX219-77IR Camera
    * https://www.waveshare.com/wiki/IMX219-77IR_Camera

* Encode video with large GOP and low FPS.
    * Keyframes take most of the space
    * If I only need video, do I need the container format or is the bitstream enough ? 
	* mp4: [mov,mp4,m4a,3gp,3g2,mj2 @ 0x33cc75e0] moov atom not found; output.mp4: Invalid data found when processing input
	* mpegts - ugly plugins group


* How large will the video be ? 
    * Store a table: duration vs disk size
    * Maybe store a sequence of files
    * Delete some of them

