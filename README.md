# ICU Monitoring System with YOLOv8

Welcome to our ICU Monitoring System project! This endeavor is a passion project by Hemant, an enthusiastic coder and developer from India who deeply believes in the transformative power of AI and the strength of community. "Innovation is not just a goal but a pathway to achieving better health outcomes," says Hemant, driven by a relentless commitment to pushing boundaries and making a meaningful impact in healthcare.


## Table of Contents
- [Description](#description)
- [Problem Statement](#problem-statement)
- [Dataset](#-dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Demonstration Of this Project in Local Environment](#demonstration-of-this-project-in-local-environment)
- [Demonstration Of Hosted Version Of This Project](#demonstration-of-hosted-version-of-this-project)
- [How We Built It](#how-we-built-it-)
- [Model Performance](#model-performance)
- [Future Work](#-future-work)
- [Contributing](#-contributing)
- [Final Thoughts](#-final-thoughts)

## Description
The ICU Monitoring System is designed to help healthcare professionals remotely monitor ICU patients, reducing the burden on on-site intensivists. The system includes:

- People Detection Model: Identifies various people in the ICU Room (nurse, intensivist, family member, patient).
- Movement Detection Model: Detects patient movement to alert healthcare professionals.

## Problem Statement
[Problem Statement](https://drive.google.com/file/d/1bAXo79ZjKUm8G_QeEyA7Y1AIZg7IWMNJ/view?usp=sharing)

## 📊 Dataset

The data for this project was primarily sourced from various YouTube videos, which provided a diverse range of ICU scenarios. This rich dataset allowed us to create a robust and versatile ICU monitoring system.

The dataset was utilized in two distinct ways for different parts of the project:

1. **Statement 1**: For the purpose of detecting individuals in the ICU, we used the full ICU room video data. This comprehensive dataset enabled us to train our model to identify various people in the ICU room, such as nurses, doctors, patients, and family members.

2. **Statement 2**: To detect patient movement, we extracted and used only the patient portions from the full ICU room videos. This focused dataset allowed us to train our model to accurately detect patient movements, which is crucial for alerting healthcare professionals in real-time.

A subset of this data is publicly available for further exploration and use. You can access it [here](https://github.com/hemantkumar76/Innovative-Monitoring-System-for-TeleICU-Patients-Using-Video-Processing-and-Deep-Learning/tree/main/Video%20Data).

## Project Structure
<pre>
ICU Monitoring System/
├── Statement1/
│   ├── data/
│   ├── models/
│   ├── notebooks/
│   └── Statement_1.ipynb
├── Statement2/
│   ├── data/
│   ├── models/
│   ├── notebooks/
│   └── Statement_2.ipynb
├── Video Data/
│   ├── video1.mp4
│   └── video2.mp4
├── LICENSE
├── Problem_Statement.pdf
├── README.md
└── requirements.txt
</pre>

## Installation
To install the necessary dependencies, run:
```bash
pip install -r requirements.txt
```

## Demonstration Of this Project in Local Environment

1. [ICU People Detection Video](#): This video demonstrates the detection of all people in an ICU.
2. [ICU Patient Movement Detection Video](#): This video demonstrates the detection of patient movement in an ICU.



## Demonstration Of Hosted Version Of This Project

To use this project anywhere anytime, simply visit the hosted versions:

1. [ICU People Detection](#)
2. [ICU Patient Movement Detection](#)


## How We Built It 🛠️👷‍♂️

We utilized a diverse tech stack to build this project:

- **YOLOv8**: Used for object detection and classification.
- **Python**: Served as the primary language for scripting and model development.
- **OpenCV**: Handled video processing tasks.
- **NumPy**: Facilitated numerical operations.
- **Streamlit**: Enabled us to create the web application interface.
- **PyTorch**: Assisted in loading and running the YOLO models.
- **Roboflow**: Managed dataset labeling and organization.

## Model performance 


## 🚀 Future Work

While the current system effectively identifies ICU personnel and detects patient movements, there are several avenues for future improvements:

- **Enhanced Detection Models**: We plan to integrate more advanced models or improve existing models to increase accuracy and reduce false positives.
- **Real-Time Monitoring**: We aim to implement real-time video processing to provide immediate alerts and notifications to healthcare professionals.
- **Expanded Dataset**: We intend to collect more diverse and comprehensive datasets to improve model robustness and adaptability to various ICU environments.
- **User Interface Enhancements**: We look forward to improving the user interface to provide more detailed analytics and visualization tools for healthcare providers.
- **Integration with Hospital Systems**: We aspire to connect the monitoring system with hospital management systems for seamless data integration and better patient management.

## 🤝 Contributing

We welcome contributions to this project! If you have suggestions, improvements, or new features to add, please feel free to reach out. You can contact me via:

- Email: [Hemanthku01@gmail.com]
- LinkedIn: [https://www.linkedin.com/in/hemant-kumar-299435230/]

Your contributions and feedback are highly appreciated!

## 💡 Final Thoughts

"Innovation is the key to better health outcomes." As we harness the power of AI to transform healthcare, this ICU Monitoring System is just the beginning. We’re on a journey to revolutionize patient care, making ICUs safer, smarter, and more efficient.

Join with me to push boundaries, break barriers, and create a future where technology and compassion work hand in hand to save lives. Let’s innovate, inspire, and make waves in the world of healthcare. 🚀

To endless possibilities and beyond,
😀 Hemant 😀

