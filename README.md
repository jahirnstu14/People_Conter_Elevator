
# People_Counter_Elevator
Welcome to the **People_Counter_Elevator** project! This project demonstrates how to detect and count people entering and exiting an elevator using OpenCV. The system differentiates between upgoing and downgoing individuals and counts them in real time, making it ideal for monitoring elevator traffic.

## Table of Contents

-   [Project Overview](#project-overview)
-   [Technologies Used](#technologies-used)
-   [Installation](#installation)
-   [Usage](#usage)
-   [Result](#result)

## Project Overview

This project provides a system that automatically detects and counts the number of people entering (upgoing) and exiting (downgoing) an elevator using a computer vision-based approach. It processes video footage from the elevator and identifies people using object detection models. The interface is built using Python and OpenCV, which makes it suitable for real-time applications in places like shopping malls, office buildings, and other public spaces.

## Technologies Used

-   **YOLO**: For detecting cars in the video feed.
-   **OpenCV**: For handling video processing, frame extraction, and drawing bounding boxes.
-   **NumPy**: For numerical operations.
-   **Python**: The main programming language for developing the application.

## Installation

To get started with this project, follow these steps:

### 1. **Clone the Repository**

Clone the repository to your local machine:

    git clone https://github.com/jahirnstu14/People_Conter_Elevator.git
    cd people-counter-elevator


 

### 2. **Set Up a Virtual Environment**

Creating a virtual environment ensures that the dependencies are isolated from your global Python environment. Follow these steps:

#### On Windows:

    python -m venv venv
    venv\Scripts\activate

 


### 3. **Install Dependencies**

Install the required Python packages by running:

`pip install -r requirements.txt` 



## Usage

### 1. **Run the Python Script**

Once everything is set up, you can start counting people by running the following command:

    python People_Count.py
    

 

The script will process the video file provided in the code and display the people count (upgoing and downgoing) in real-time.

### 2. **OpenCV GUI**

The system opens a window displaying the processed video frames, highlighting the detected people with bounding boxes. The count of upgoing and downgoing people is displayed on the screen, updated frame by frame as people enter or exit the elevator.


## Result

Once the application is running, you will see the video feed with detected people highlighted by bounding boxes. The total number of upgoing and downgoing people will also be displayed in real-time.
[Video demo : ](https://github.com/jahirnstu14/People_Conter_Elevator/blob/main/output_video.mp4)
