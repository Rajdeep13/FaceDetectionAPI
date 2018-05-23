## Python Work
Create a simple Face Detection API using 

## Key Files
- **cv_api/cv_api/urls.py**			File defines the end point url pattern of our API
- **cv_api/face_detector/view.py**	Files have all the logic basically cv2 function for face detection
- **cv_api/manage.py**				File is used to run Python API server.Run below command to run the server This will sart your API server endpoint at "http://127.0.0.1:8000/face_detection/detect/"	
```python manage.py runserver```
- **cv_api/test.py** 				File use to test the API. Run below command to test this API.
```python test.py```

#### Refer this [URL](https://www.pyimagesearch.com/2015/05/11/creating-a-face-detection-api-with-python-and-opencv-in-just-5-minutes/) for more details.