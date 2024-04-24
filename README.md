# Video_player

This Python script allows you to play a video file and view its frames using OpenCV. Additionally, it provides instructions on how to include sound playback alongside video display.

Prerequisites
 1) Before running the script, make sure you have the following installed:

    Python (version 3.x recommended)
    OpenCV library (cv2)
    You can install OpenCV using pip: pip install opencv-python

Usage
 1) Clone or download this repository to your local machine.
 2) Navigate to the directory containing the script and the video file you want to play.
 3) Run the script using Python, passing the video file as an argument: python video_player.py 
 4) Replace "python_project.mp4" with the path to your video file.
 5) The script will display the video frames in a window. Press the 'q' key to exit.

Code Explanation
 1) The script uses OpenCV (cv2) to open the video file specified as the command-line argument.
 2) It checks if the video file is opened successfully.
 3) It reads each frame from the video file and displays it in a window using cv2.imshow.
 4) Pressing the 'q' key closes the window and exits the script.

Additional Notes
 1) Make sure the video file exists and is accessible from the script's location.
 2) The script currently does not include sound playback. For adding sound, you might need to use additional libraries or tools like moviepy or ffmpeg.
 3) Feel free to modify the script according to your requirements.
