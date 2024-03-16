
<a name="readme-top"></a>

  <h3 align="center">AI Motion Detection </h3>

  <p align="center">
    My most ambitious project so far!
    <br />
    <br />
  </p>
</div>


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

Welcome to my Facial Recognition Security System project! This project aims to provide an intelligent and efficient security solution for monitoring and securing residential properties using facial recognition technology.

Facial Detection and Recognition: Our system utilizes advanced computer vision techniques to detect and recognize human faces captured by surveillance cameras installed at the premises. Through the integration of deep learning models, we can accurately identify individuals in real-time.

<div style="text-align:center;">
    <img src="https://github.com/NicoSchultze/AI-Security-System/assets/87664933/0e92fa48-6fce-4061-8a36-7e5be8fbab6c" alt="Image" style="width: 600px; height: 400px;">
</div>


Object Detection: In addition to facial recognition, the system includes object detection capabilities to identify and track various objects of interest such as humans, animals, or vehicles. This enhances the overall security monitoring capability, allowing for comprehensive surveillance.

<div style="text-align:center;">
    <img src="https://github.com/NicoSchultze/AI-Security-System/assets/87664933/9c10ad22-6d1a-470c-aaa1-aaece900bec6" alt="Image" style="width: 600px; height: 400px;">
</div>

Live Feed Web Interface: Users can access a user-friendly web interface to view live camera feeds from the surveillance system. The interface overlays detection and recognition results, providing real-time insights into the detected objects and recognized faces.

<div style="text-align:center;">
    <img src="https://github.com/NicoSchultze/AI-Security-System/assets/87664933/d9390980-c305-4fab-97ee-3e3a157d6b03" alt="Image" style="width: 600px; height: 400px;">
</div>

Alerting and Notification: The system is equipped with alerting mechanisms to notify users of any suspicious activities or unrecognized individuals detected on the premises. This ensures prompt action can be taken in response to potential security threats.

<div style="text-align:center;">
    <img src="https://github.com/NicoSchultze/AI-Security-System/assets/87664933/a6c7bd7a-60cd-4e3d-9036-d079b0855010" alt="Image" style="width: 600px; height: 400px;">
</div>


Use the `BLANK_README.md` to get started.




### Built With

The tech-stack of this project is not final, since it is still in its planning phase but here is an outlook on what to expect:

* Pytorch Torchvision for Object Detection
* OpenCV for Facial Detection and Recognition
* Node.js as Runtime Environment
* Express.js for Backend
* React.js for Frontend
* MongoDB as the Database
* Docker for Containerization
  

<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```



<!-- USAGE EXAMPLES -->
## Usage

This project will be used as a security system for a client. It will be deployed in the house entrance of a suburbian region in Germany. It is supposed to observe the entrance area and detect objects/animals/humans who are in that area. Furthermore, a facial recognition model will pin down on who exactly is entering and if that person is a known member of the family/friends etc. Depending on that decision notifications can be send out to family members. Also the camera video will be interactable with on a web-interface. 



<!-- ROADMAP -->
## Roadmap

- [ ] Environment Setup
  - [ ] Raspberry Pi and Camera Modul Configuraiton
- [ ] Object Detection
  - [ ] Leverage Existing Dataset
  - [ ] Implement Model
  - [ ] Training/Testing
- [ ]  Facial Detection
  - [ ] Create Dataset for known Humans
  - [ ] Implement Model
  - [ ] Training/Testing
- [ ] Integration and Alerting
  - [ ] Integrate Object and Facial Detection in Cohesive System
  - [ ] Implement Alerting System (notification etc)
- [ ] Web-Interface
  - [ ] Build Backend 
  - [ ] Build Frontend
- [ ] Testing and Optimization
- [ ] Dockerization
- [ ] Deployment
    
- [ ] (Possible Android App Implementation)



<!-- CONTACT -->
## Contact

Nico Schultze - nico.schultze97@gmail.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


