# Tech4City2024 Coding Challenge
## Team: GuideTheDark
### Team Members
- Joel Tan
- Samuel Yeo
- Huan Shi Yu

---

### Project Overview
Object detection allows us to identify and locate objects within images or video frames, making it invaluable for applications like autoomous driving, surveillance, and image analysis. 

Explore the capabilities of object detection by uploading an image

---
### File allocation 
1. Backend:
- yolov3.weight
- yolov3.config
- coco.names
- requirements
- app.py
- model.py

2. Frontend:
- javascript
- CSS
- HTML

3. Dockerfile
---
### Downloading yoloV3 weight file
wget https://pjreddie.com/media/files/yolov3.weights

---

### Steps to run smoothly
1. Download: yolov3.weights , yolov3.cfg, coco.names
2. Set up virtual environment by typing this 
- python -m venv venv
- venv\Scripts\activate 
- pip install Flask opencv-python numpy
3. Run python using command 
- python app.py
4. Proceed to  http://localhost:8000/
---

### Contact Information
- Huan Shi Yu: [shiyu99@gmail.com](mailto:shiyu99@gmail.com)
