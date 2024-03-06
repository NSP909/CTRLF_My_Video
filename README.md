# CTRLF My Video

## Overview

Our web application is designed to streamline video analysis using advanced AI audio recognition. By efficiently identifying specific events such as gunshots, car crashes, and human screams, our application saves valuable time for users who need to locate crucial moments within lengthy videos. With a user-friendly interface and powerful backend technology, our application is particularly beneficial for professionals like law enforcement officers or detectives who often face the challenge of manually reviewing extensive footage.

## Features

- **Audio Recognition**: Our AI-powered model is trained to recognize predefined sounds, including gunshots, car crashes, and various types of human screams.
- **Efficient Search Option**: Users can easily locate specific events in their videos through a search option, eliminating the need for manual video analysis.
- **Time-saving Automation**: Revolutionizing video analysis by automating the process, our application provides a faster and more accurate way to pinpoint critical moments in a vast sea of content.
- **Seamless User Experience**: The frontend is designed for a seamless user experience, allowing users to effortlessly upload their video files and access the application's features.

## How We Built It

### Data Collection and Model Training

We initiated the project by collecting diverse datasets of different sounds, with a focus on gunshots, car crashes, and human screams. Simultaneously, a basic frontend was developed. The collected data was then fed into the machine learning model, which underwent multiple training sessions. We employed data augmentation and adjusted hyperparameters to enhance the model's accuracy in distinguishing between different sounds.

### Technology Stack

#### Client Side
- React
- Redux
- TailwindCSS

#### Server Side
- Node
- Express
- Python
- Pytorch
- MongoDB

### Database Integration

We utilized MongoDB for database management, enabling the storage of audio data and generating logs based on the model's recognition outputs.

## Inspiration

Our inspiration for this project stemmed from the inefficiencies depicted in detective movies, where investigators spend hours manually reviewing video and audio footage to find a single event. Motivated by a shared goal to enhance efficiency in event detection, save valuable time for users, and contribute to more effective workflows, we embarked on the development of this web application.

## Contribution

We welcome contributions to further enhance the capabilities and features of our AI video analysis web application. Feel free to fork the repository, make improvements, and submit pull requests.

#Prizes

Cipher Tech Solutions: “Best Digital Forensics Related Hack” at HoyaHacks   2024 
