
# K9 (AI Face Recognisation)

We are presenting a facial recognition algorithm and API (Application Programming Interface) which will integrate live databases and Social Media Platforms to detect the face of a missing person by scanning through the databases as well as internet/social media platforms.
One of the main benefits of using AI face detection mechanisms for searching missing people is its speed and accuracy. AI algorithms can quickly scan large datasets of images and videos, identify faces, and match them against known databases of missing persons. This can help law enforcement agencies and other organizations to identify potential leads and locate missing individuals more efficiently.


## Goal of the project

-  To improve the speed and accuracy of identifying individuals who have gone missing and to increase the chances of locating them.


-  To search for individuals in large databases of images, such as social media profiles or security camera footage, and quickly identify matches.
## Roadmap


- We provide the system with the FIR ID of the case. 
     
- The algorithm processes the input through web/social media(API’s & web scraping) and live camera feeds.

- The system detects the faces using YOLO (CNN).

- Detected faces are compared using face_recogntion library. Deep learning algorithms use neural networks with multiple layers to learn complex patterns and features in images. It has shown impressive results in face detection tasks .

- If similarity is found, it extracts the username, location, time/date, etc. from social media and live camera feeds.

- Alerts the authority concerned via mail (smtp lib) or a popup message.

- Predicted route map is generated.

- Our app uses complex algorithms to analyze facial features, such as the distance between eyes, nose shape, and jawline to identify and recognize individuals. It works with a high accuracy, even in challenging lighting conditions, and can match images quickly, making it an efficient tool for many applications.


## Tech Stack used

- YOLO (You Only Look Once) : It is a state-of-the-art object detection algorithm that uses a Convolutional Neural Network (CNN) for real-time object detection.

 - Face_recognition :This library can detect faces in an image, and return the coordinates of the bounding boxes around each detected face.

- Tkinter : It is a standard Python library that provides a GUI (Graphical User Interface) toolkit for creating desktop applications with Python.

- PyAutoGUI : It provides cross-platform support for controlling the mouse, keyboard, and screen of a computer to automate tasks that involve GUI interactions.

- PIL (Python Imaging Library) : It provides tools for working with images in tkinter GUI applications.

- Mysql.connector : It allows you to connect and interact with MySQL databases.

- csv : It is a library that provides functionality for working with comma-separated value (CSV) files.

- BeautifulSoup : It is a popular Python library used for web scraping and parsing HTML and XML documents. 

## Screenshots and Logo

![Logo](https://raw.githubusercontent.com/sumanyu-sharma-mk42/K9/main/TEST%20%20IMAGES/k9_final-removebg-preview.png)
![Logo](https://raw.githubusercontent.com/sumanyu-sharma-mk42/K9/main/WhatsApp%20Image%202023-03-17%20at%2011.58.31%20AM.jpeg)
![Logo](https://raw.githubusercontent.com/sumanyu-sharma-mk42/K9/main/WhatsApp%20Image%202023-03-17%20at%2011.58.31%20AM%20(1).jpeg)
![Logo](https://raw.githubusercontent.com/sumanyu-sharma-mk42/K9/main/WhatsApp%20Image%202023-03-17%20at%2011.58.32%20AM.jpeg)
![Logo](https://raw.githubusercontent.com/sumanyu-sharma-mk42/K9/main/WhatsApp%20Image%202023-03-17%20at%2011.58.32%20AM%20(1).jpeg)
![Logo](https://raw.githubusercontent.com/sumanyu-sharma-mk42/K9/main/WhatsApp%20Image%202023-03-17%20at%2011.58.32%20AM%20(2).jpeg)
![Logo](https://raw.githubusercontent.com/sumanyu-sharma-mk42/K9/main/WhatsApp%20Image%202023-03-17%20at%2011.58.33%20AM.jpeg)
![Logo](https://raw.githubusercontent.com/sumanyu-sharma-mk42/K9/main/WhatsApp%20Image%202023-03-17%20at%2011.58.34%20AM.jpeg)





- 
## What can our project be used for
 
 Security and law enforcement agencies can use this technology :

 - Social media monitoring: Law enforcement authorities can monitor social media platforms to find information about missing people and criminals. They can use facial recognition technology to match images of individuals on social media with images in their databases.

 - Automated facial recognition systems: Law enforcement authorities can use automated facial recognition systems that can scan faces in real-time to identify wanted individuals. These systems can be installed in public places such as airports, train stations, and other transport hubs to monitor the movement of people.By doing so, they can quickly identify individuals and locate them.

 

## Who all can use this technology 



- Security and law enforcement agencies: These organizations may use AI face detection applications to identify suspects or persons of interest in security camera footage or to monitor public areas for potential security threats.

- Event organizers: AI face detection can be used by event organizers to keep track of attendance or to identify individuals who are not authorized to enter a restricted area.

- Researchers and academics: AI face detection is an active area of research, and researchers may use these applications to study and develop new algorithms and techniques for facial recognition and analysis.


- Non-profit organizations: Non-profit organizations that focus on privacy or human rights issues may be interested in sponsoring AI face recognition projects that address privacy concerns or use the technology for humanitarian purposes.

- Human resources: AI face recognition models can be used in human resources to verify employee attendance and prevent time theft. This can be particularly useful in industries with high labor costs, such as manufacturing.

- Retail: AI face recognition models can be used in retail to track customer behavior and preferences, as well as to personalize shopping experiences. For example, an AI face recognition model could identify a customer and provide personalized recommendations based on their previous purchases and browsing history.




 ##What challenges did you face and how did you overcome them?


- Image quality: The quality of the images used for facial detection can significantly impact the accuracy of the algorithm. In many cases, images of missing persons were of low-quality or distorted, which made it difficult for the software to identify a match.

- Legal and ethical considerations: The use of facial recognition technology is subject to legal and ethical considerations, such as compliance with data protection laws and the potential for misuse. We had to consider these issues when creating an AI face detection software for finding missing persons.

- Privacy concerns: The use of facial recognition technology raises concerns about privacy, surveillance, and the potential for misuse. We designed the software to protect the privacy and security of individuals and have maximum transparency possible.


## How to run the code locally

Running project locally

establish a database by using 'police_data1.csv' file in MySQL.
name the database ‘police_database' and create table with the required fields and name it 'missing_person'. 
dowload all the essential libraries provided below :

Pip install smtplib
pip install customtkinter
Pip install tkinter
Pip install beautifulsoup4
pip install dlib
Pip install face_recognition
Pip install csv
Pip install requests
Pip install mimestypes
Pip install pillow
Pip install pyautogui
Pip install pycopy-webbrowser
Pip install mysql-connector-python
Pip install opencv-python

save all the 'TEST IMAGES' and the ‘main.py' file in a single folder.
dowload all files from the ‘REQUIREMENTS' folder into the same folder as that of ‘main.py' folder.


