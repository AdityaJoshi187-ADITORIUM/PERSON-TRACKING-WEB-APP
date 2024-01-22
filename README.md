🕵️PERSON-TRACKING-WEB-APP🕵️



This Flask web application leverages the face_recognition library to annotate faces in a video based on a provided target image. 
It can be used to identify and mark faces within video frames, creating a new video with labeled faces.

User-friendly Interface: The application provides a simple web interface for users to upload a target image and a video file.👀

Face Recognition: Using face_recognition library, 
the application detects and compares faces in each video frame with the target image, marking matches with rectangles and labels.
Result Visualization: The annotated video with labeled faces is generated and made available for download.

for getting started you'll have to:
Install Python on your machine.
Install required Python packages using the following command:
pip install Flask imageio face_recognition Pillow numpy

first and foremost is you need to Clone this repository or download this repository as zip.

then after navigating yourself to the app's folder youll need to create 3 more folders
1.result
2.uploaded images🏞️
3.uploaded videos🎬

Navigate to the project directory:
cd PERSON-TRACKING-WEB-APP

Run the Flask application:
python app.py

Open your browser and go to the IP address that you can see in the terminal by simply clicking on it while pressing the ctrl on yoour keyboard.
you'll see an interactive interface on the browser screen.

Upload a target image and a video file, then click on the "upload" button.
after you have uploaded the images and a video they'll automatically get stored in the uploaded images, uploaded videos folder according to their file types.
suppose the web app gets deployed server can have all the information about the original (raw) innput data with the annotated video data 

Once processing is complete, The annotated video will be saved on the result folder.
The application uses Flask to handle HTTP requests and templates. Configuration settings for image upload, 
video upload, and result folders can be adjusted in the app.py file.
Allowed file formats for upload include JPG, JPEG, PNG, GIF, and MP4. 
You can modify the ALLOWED_EXTENSIONS set in app.py to include additional formats if needed.

Issues and Contributions😊:
If you encounter any issues or have suggestions for improvements, feel free to open an issue. Contributions are welcome!!
