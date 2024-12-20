**Gender and Age Detection using OpenCV**
  This project builds a gender and age detector to approximate a person's gender and age from a face image or webcam feed.

⁕Additional Python Libraries Required :
  OpenCV
     pip install opencv-python
  argparse
     pip install argparse

⁕About the project:
                  This Python project uses deep learning to predict the gender and age of a person from a single face image. The models, trained by Tal Hassner and Gil Levi, classify gender as either 'Male' or 'Female' and age into one of eight ranges: (0–2), (4–6), (8–12), (15–20), (25–32), (38–43), (48–53), and (60–100). Instead of predicting exact ages, it frames the problem as classification, addressing challenges like lighting, makeup, and facial expressions.

⁕Dataset:
          https://www.kaggle.com/datasets/ttungl/adience-benchmark-gender-and-age-classification

⁕Usage:

  ⁕Detecting Gender and Age of face in Image Use Command :
          python detect.py --image <image_name>   [Note: The Image should be present in same folder where all the files are present]

          Ex: >python detect.py --image man1.jpg
      
  ⁕Detecting Gender and Age of face through webcam Use Command :
          python detect.py

  Press Ctrl + C to stop the program execution.




