
<!-- PROJECT LOGO -->
<br />
<p align="center">
  
  <img src="https://img.icons8.com/color/80/000000/data-encryption.png"/>
  <h1 align="center">Steganography</h1>

  <p align="center">
    A Steganography Tool
  </p>
</p>

<!-- ABOUT THE PROJECT -->
## 1. About The Project

*Steganography* can also be referred as the technique of hiding secret data within an ordinary, non secret, file or message in order to avoid detection; the secret data is then extracted at its destination. 

**Stega** is a Python-Flask based Web App ehich serves the purpose of a Steganograhy tool which includes the functionality of following techniques in a single application:
- 📃 | 🖼️ Image Steganography
- 🎵 | Audio Steganography 
- 📹 | Video Steganography

## 2. Resources
1. **Framework** : Flask
- [Flask Documentation (1.1.x)](https://flask.palletsprojects.com/en/1.1.x/)
2. **Image Steganography** : *opencv-python, stepic*
- [OpenCV documentation](https://docs.opencv.org/master/)
- [Stepic](https://pypi.org/project/stepic/)
3. **Audio Steganography** : *wave*
- [Wave Read & Write files](https://docs.python.org/3/library/wave.html)
4. **Video Steganography** : *stegano, subprocess, ffmpeg*



<!-- GETTING STARTED -->
## 3. Getting Started
#### Clone the Repo
```
git clone https://github.com/Gaurav-153/Digital-Steganography.git

````

####  Python 3 
Install Python 3 in your system. [click here](https://www.python.org/downloads/)

#### Create a Virtual Environment.
- Create a Virtual Environment using **Anaconda Navigator** with Python version 3.7+ 
- Open Terminal with the activated environment.

#### Installing Dependencies in Virtual Environment
- Make sure environment is activated. 
- Using Requirements File. **(Recommended)**
```
pip install -r requirements.txt
```
- Individually installing packages.
	##### ***Flask | OpenCv | Stepic | Wave | Stegano***
```
pip install Flask opencv-python stepic wave stegano
```

#### 4 .Running Application
Make sure environment is activated, Now run:
```
python main.py
```
Open the localhost link - [http://127.0.0.1:5000/](http://127.0.0.1:5000/),this will open the App on your browser.



  


