![Image of Logo](templates/logo.jpg)

# Smart India Hackathon 2020
Textile Detection from CCTV Surveillance Videos

# Table of Contents

* [Description](https://github.com/amurto/gearstalk#description)
* [Dependencies](https://github.com/amurto/gearstalk#dependencies)
* [Installation](https://github.com/amurto/gearstalk#installation)
  * [Prerequisites](https://github.com/amurto/gearstalk#prerequisites)
  * [Instructions](https://github.com/amurto/gearstalk#instructions)
* [Usage](https://github.com/amurto/gearstalk#usage)
* [Contributors](https://github.com/amurto/gearstalk#contributors)
* [License](https://github.com/amurto/gearstalk#license)

# Description

The system focuses on capturing and saving various attributes of fabrics worn by targeted persons captured from various CCTV cameras through distributed intelligence along with time and location stamps over the period in a database. The database is compiled to be used in identification of suspects from video clips of crime related CCTV footages captured in a series of CCTV cameras located on routes and close to scene of crime.

* To Collect Image Dataset for Indian fabrics. 
* To Train our Machine Learning models for classifying the fabric labels from the video footages frame by frame.
* To design a system Architecture for processing Video footages from CCTV.
* To Store the Identified labels and respective timestamp in a database for the processed video footages.
* To provide an user friendly interface for the operator to perform video forensics and reporting.
* To Design the entire system in a more robust manner.
 
## Screenshots
![Image 1](templates/img1.jpg)
![Image 2](templates/img2.jpg)

## Architecture
![Architecture](templates/architecture.jpg)

## Labels
![Labels](templates/labels.jpg)

# Dependencies

* [TensorFlow](https://www.tensorflow.org/)
* [Keras](https://keras.io/)
* [npm](https://www.npmjs.com/)
* [React.js](https://reactjs.org/)

# Installation

### Prerequisites

Install Node.js and npm using the link above. Follow instructions on their respecive websites. Npm is included with Node.js

### Instructions

Clone the repository
```bash
git clone https://github.com/amurto/gearstalk.git
```

Install all the dependencies
```bash
cd web_app 
npm install
```

# Usage

Run the project
```bash
cd web_app
npm start
```

Open a web browser and go to
```bash
http://localhost:3000
```

# Contributors

* Amurto Basu [@amurto](https://github.com/amurto)
* Carol Sebastian [@carol80](https://github.com/carol80)
* Sherwin Pillai [@sherwinpillai](https://github.com/sherwinpillai)
* Mahesh Desai [@mahesh131998](https://github.com/mahesh131998)
* Shubham Bhate [@ssb2920](https://github.com/ssb2920)
* Cassia Vaz [@CassiaVaz](https://github.com/CassiaVaz)

# Mentors
* Mahendra Mehra [@mahendra-mehra](https://github.com/mahendra-mehra)
* Elvis Dsouza [@ejson03](https://github.com/ejson03)

# License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[MIT License Link](https://github.com/amurto/gearstalk/blob/master/LICENSE)