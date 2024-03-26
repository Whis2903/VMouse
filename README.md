<br/>
<p align="center">
  <h3 align="center">
Virtual Mouse using Hand Gestures</h3>

  <p align="center">
    "Navigate with Gestures: Transform Your Hand into a Virtual Mouse!"
    <br/>
    <br/>
  </p>
</p>

![Forks](https://img.shields.io/github/forks/Whis2903/VMouse?style=social) ![Issues](https://img.shields.io/github/issues/Whis2903/VMouse) 

## Table Of Contents

* [About the Project](#about-the-project)
* [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Installation](#installation)
* [Contributing](#contributing)
* [Authors](#authors)
* [Acknowledgements](#acknowledgements)

## About The Project

This project aims to revolutionize user interaction with computers by implementing a virtual mouse controlled entirely through hand gestures. Leveraging the power of computer vision techniques provided by libraries like MediaPipe and OpenCV, it tracks the user's hand movements in real-time, overlaying landmarks to accurately interpret gestures. By simply moving their index finger, users can effortlessly control the mouse cursor on their screen. Additionally, a click action is triggered by bringing the thumb close to the index finger, mimicking a mouse click gesture. The system is designed to be adaptable to various screen resolutions, ensuring a seamless user experience across different devices. With this innovative solution, users can navigate their digital world with intuitive hand gestures, enhancing both accessibility and convenience in computer interaction.

## Built With

- MediaPipe: Utilized for real-time hand detection and landmark tracking, providing robust computer vision capabilities.
- OpenCV: Integrated for image processing tasks such as frame capture, color space conversion, and drawing overlays on the video feed.
- PyAutoGUI: Employed for simulating mouse actions and controlling cursor movements on the screen, enabling interaction based on hand gestures.

## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Installation



1. Clone the repo 

```sh
git clone https://github.com/Whis2903/VMouse.git
```

2. Install  packages

```sh
pip install opencv-python mediapipe pyautogui
```

3.Run the Script

```sh
python main.py
```

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.
* If you have suggestions for adding or removing projects, feel free to [open an issue](https://github.com/Whis2903/VMouse/issues/new) to discuss it, or directly create a pull request after you edit the *README.md* file with necessary changes.
* Please make sure you check your spelling and grammar.
* Create individual PR for each suggestion.
* Please also read through the [Code Of Conduct](https://github.com/Whis2903/VMouse/blob/main/CODE_OF_CONDUCT.md) before posting your first idea as well.

### Creating A Pull Request

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Authors

* **Vishal Mohan Nair ** - *CSE Student* - [Vishal Mohan Nair ](https://github.com/Whis2903) - *Developer*


