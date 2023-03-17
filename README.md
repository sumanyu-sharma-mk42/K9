# K9 (AI Face Recognisation)

We are presenting a facial recognition algorithm and API (Application Programming Interface) which will integrate live databases and Social Media Platforms to detect the face of a missing person by scanning through the databases as well as internet/social media platforms.


![Logo](https://raw.githubusercontent.com/sumanyu-sharma-mk42/K9/main/TEST%20%20IMAGES/KHYATI.jpeg)


## Roadmap


- We provide the system with the FIR ID of the case. 
     
- The algorithm processes the input through web/social media(API’s & web scraping) and live camera feeds.

- The system detects the faces using YOLO (CNN).

- Detected faces are compared using face_recogntion library.

- If similarity is found, it extracts the username, location, time/date, tagged people, etc. from social media and live camera feeds.

- Alerts the authorities concerned via mail (smtp lib) or a popup message.

- Predicted route map is generated.

## What challenges did you face and how did you overcome them?

- Image quality: The quality of the images used for facial detection can significantly impact the accuracy of the algorithm. In many cases, images of missing persons were of low-quality or distorted, which made it difficult for the software to identify a match.

- Legal and ethical considerations: The use of facial recognition technology is subject to legal and ethical considerations, such as compliance with data protection laws and the potential for misuse. We had to consider these issues when creating an AI face detection software for finding missing persons.

- Privacy concerns: The use of facial recognition technology raises concerns about privacy, surveillance, and the potential for misuse. We designed the software to protect the privacy and security of individuals and have maximum transparency possible.

- 

!-- What did you learn while building this project? -->
## This technology can be used by
 
 Security and law enforcement agencies can use this technology :

 - Social media monitoring: Law enforcement authorities can monitor social media platforms to find information about missing people and criminals. They can use facial recognition technology to match images of individuals on social media with images in their databases.

 - Automated facial recognition systems: Law enforcement authorities can use automated facial recognition systems that can scan faces in real-time to identify wanted individuals. These systems can be installed in public places such as airports, train stations, and other transport hubs to monitor the movement of people.By doing so, they can quickly identify individuals and locate them.

 

## Goal of the project

-  To improve the speed and accuracy of identifying individuals who have gone missing and to increase the chances of locating them.


-  To search for individuals in large databases of images, such as social media profiles or security camera footage, and quickly identify matches.
## Technologies used

- YOLO (You Only Look Once) : It is a state-of-the-art object detection algorithm that uses a Convolutional Neural Network (CNN) for real-time object detection.

 - Face_recognition :This library can detect faces in an image, and return the coordinates of the bounding boxes around each detected face.

- Tkinter : It is a standard Python library that provides a GUI (Graphical User Interface) toolkit for creating desktop applications with Python.

- PyAutoGUI : It provides cross-platform support for controlling the mouse, keyboard, and screen of a computer to automate tasks that involve GUI interactions.

- PIL (Python Imaging Library) : It provides tools for working with images in tkinter GUI applications.

- Mysql.connector : It allows you to connect and interact with MySQL databases.

- csv : It is a library that provides functionality for working with comma-separated value (CSV) files.

- 
## This Technology can be used By



- Security and law enforcement agencies: These organizations may use AI face detection applications to identify suspects or persons of interest in security camera footage or to monitor public areas for potential security threats.

<!-- - Event organizers: AI face detection can be used by event organizers to keep track of attendance or to identify individuals who are not authorized to enter a restricted area.

- Researchers and academics: AI face detection is an active area of research, and researchers may use these applications to study and develop new algorithms and techniques for facial recognition and analysis.


- Non-profit organizations: Non-profit organizations that focus on privacy or human rights issues may be interested in sponsoring AI face recognition projects that address privacy concerns or use the technology for humanitarian purposes.

- Human resources: AI face recognition models can be used in human resources to verify employee attendance and prevent time theft. This can be particularly useful in industries with high labor costs, such as manufacturing.

- Retail: AI face recognition models can be used in retail to track customer behavior and preferences, as well as to personalize shopping experiences. For example, an AI face recognition model could identify a customer and provide personalized recommendations based on their previous purchases and browsing history. -->




## API Reference

#### Get all items

http
  GET /api/items


| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | *Required*. Your API key |

#### Get item

http
  GET /api/items/${id}


| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | *Required*. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.


## Appendix

Any additional information goes here


## Authors

- [@octokatherine](https://www.github.com/octokatherine)


## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

## Color Reference

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Example Color | ![#0a192f](https://via.placeholder.com/10/0a192f?text=+) #0a192f |
| Example Color | ![#f8f8f8](https://via.placeholder.com/10/f8f8f8?text=+) #f8f8f8 |
| Example Color | ![#00b48a](https://via.placeholder.com/10/00b48a?text=+) #00b48a |
| Example Color | ![#00d1a0](https://via.placeholder.com/10/00b48a?text=+) #00d1a0 |


## Demo

Insert gif or link to demo


## Deployment

To deploy this project run

bash
  npm run deploy



## Installation

Install my-project with npm

bash
  npm install my-project
  cd my-project

    
 ##What challenges did you face and how did you overcome them?



## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)


## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`API_KEY`

`ANOTHER_API_KEY`


## Running Tests

To run tests, run the following command

bash
  npm run test



## Usage/Examples

javascript
import Component from 'my-project'

function App() {
  return <Component />
}



## Problems faced 


## Features

- Light/dark mode toggle
- Live previews
- Fullscreen mode
- Cross platform


## License

[MIT](https://choosealicense.com/licenses/mit/)


## Optimizations

What optimizations did you make in your code? E.g. refactors, performance improvements, accessibility


## Run Locally

Clone the project

bash
  git clone https://link-to-project


Go to the project directory

bash
  cd my-project


Install dependencies

bash
  npm install


Start the server

bash
  npm run start



## Support

For support, email fake@fake.com or join our Slack channel.


## Tech Stack

*Client:* React, Redux, TailwindCSS

*Server:* Node, Express


## 🛠 Skills
Javascript, HTML, CSS...


## Related

Here are some related projects

[Awesome README](https://github.com/matiassingers/awesome-readme)


## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.


## Acknowledgements

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)
