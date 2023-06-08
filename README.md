
# OPTICAL CHARACTER RECOGNITION
 ORC is a process to convert an image of text into machine readable text format.
So, In this project I used pytesseract to convert an image full of paragraphs to words and I used YOLOv8 for object detection in an image.


## Author

- [@punamcancodee](https://github.com/punamcancodee)



## 🛠 Skills
Numpy, pytesseract, OpenCV, YOLOv8, PyTorch, Convolutional Neural Network


## Screenshots

The Real Image used for object detection


![App Screenshot](https://github.com/punamcancodee/Optical_character_Recognition/blob/main/images/textfile_original.png?raw=true)


Converted to Gray using cv2.cvtColor(img, cv2.COLOR_BGR2RGB)

![App Screenshot](https://github.com/punamcancodee/Optical_character_Recognition/blob/main/images/togray.png?raw=true)


And then words detected from an image using  pytesseract.image_to_string(img)


![App Screenshot](https://github.com/punamcancodee/Optical_character_Recognition/blob/main/images/towords.png?raw=true)


Using YOLOv8 for detection of object in an image


![App Screenshot](https://github.com/punamcancodee/Optical_character_Recognition/blob/main/images/detected_image.png?raw=true)


## License

[MIT](https://choosealicense.com/licenses/mit/)


## Installation

For running the code properly, openCV, pytesseract, yoloV8 should be installed properly

```bash
  !pip install opencv-python
  !pip install pytesseract
  !pip install ultralytics

```
    
