# Fastai ASL Classification WebGL Demo
An American Sign Language (ASL) classifier WebGL demo for the fastai to Unity tutorial

### Live Demo: [https://cj-mills.github.io/Fastai-ASL-Classification-WebGL-Demo/](https://cj-mills.github.io/Fastai-ASL-Classification-WebGL-Demo/) 

### Kaggle Dataset: [belalelwikel/asl-and-some-words](https://www.kaggle.com/datasets/belalelwikel/asl-and-some-words)


<details><summary><h3>Reference Images</h3></summary><br/>

| Class    | Image                                              |
| --------- | ------------------------------------------------------------ |
| 0_OR_O    | ![O1](./images/O1.jpg) |
| 1         | ![ONE_0](./images/ONE_0.jpg) |
| 2_OR_V    | ![TWO_34](./images/TWO_34.jpg) |
| 3         | ![THREE_0](./images/THREE_0.jpg) |
| 4         | ![FOUR_0](./images/FOUR_0.jpg) |
| 5         | ![FIVE_0](./images/FIVE_0.jpg) |
| 6_OR_W    | ![W0](./images/W0.jpg) |
| 7         | ![SEVEN_0](./images/SEVEN_0.jpg) |
| 8         | ![EIGHT_0](./images/EIGHT_0.jpg) |
| 9         | ![NINE_0](./images/NINE_0.jpg) |
| A         | ![A_0](./images/A_0.jpg) |
| B         | ![B429](./images/B429.jpg) |
| C         | ![C171](./images/C171.jpg) |
| D         | ![D205](./images/D205.jpg) |
| E         | ![E430](./images/E430.jpg) |
| F         | ![F1249](./images/F1249.jpg) |
| G         | ![G3](./images/G3.jpg) |
| H         | ![H1](./images/H1.jpg) |
| I         | ![I1](./images/I1.jpg) |
| J         | ![J1](./images/J1.jpg) |
| K         | ![K_0](./images/K_0.jpg) |
| L         | ![L1](./images/L1.jpg) |
| M         | ![M1](./images/M1.jpg) |
| N         | ![N1](./images/N1.jpg) |
| O_OR_0    | ![O1](./images/O1.jpg) |
| P         | ![P1](./images/P1.jpg) |
| Q         | ![Q1](./images/Q1.jpg) |
| R         | ![R1](./images/R1.jpg) |
| S         | ![S1](./images/S1.jpg) |
| T         | ![T0](./images/T0.jpg) |
| U         | ![U1](./images/U1.jpg) |
| V_OR_2    | ![TWO_34](./images/TWO_34.jpg) |
| W_OR_6    | ![W0](./images/W0.jpg) |
| X         | ![X0](./images/X0.jpg) |
| Y         | ![Y1](./images/Y1.jpg) |
| Z         | ![Z1](./images/Z1.jpg) |
| Baby      | ![Baby_0](./images/Baby_0.jpg) |
| Brother   | ![Brother_0](./images/Brother_0.jpg) |
| Dont_Like | ![Dont_like_0](./images/Dont_like_0.jpg) |
| Friend    | ![Friend_0](./images/Friend_0.jpg) |
| Help      | ![Help_0](./images/Help_0.jpg) |
| House     | ![House_0](./images/House_0.jpg) |
| Like      | ![Like_0](./images/Like_0.jpg) |
| Love      | ![Love_0](./images/Love_0.jpg) |
| Make      | ![Make_0](./images/Make_0.jpg) |
| More      | ![More_0](./images/More_0.jpg) |
| Name      | ![Name_0](./images/Name_0.jpg) |
| No        | ![No_0](./images/No_0.jpg) |
| Pay       | ![Pay_0](./images/Pay_0.jpg) |
| Play      | ![Play_0](./images/Play_0.jpg) |
| Stop      | ![Stop_0](./images/Stop_0.jpg) |
| With      | ![With_0](./images/With_0.jpg) |
| Yes       | ![Yes_0](./images/Yes_0.jpg) |
| nothing   | ![nothing1](./images/nothing1.jpg) |
</details>

<details><summary><h3>Performance Observations</h3></summary><br/>

| OS         | Browser | Hardware                | Model    | Input      | FPS           | Notes                                                        |
| ---------- | ------- | ----------------------- | -------- | ---------- | ------------- | ------------------------------------------------------------ |
| Windows 10 | Chrome  | Titan RTX               | ResNet34 | test image | 60 (capped)   | Model returns accurate results                               |
| Windows 10 | Chrome  | Titan RTX               | ResNet34 | webcam     | 45-55         | Model returns accurate results                               |
| Windows 10 | Firefox | Titan RTX               | ResNet34 | test image | 60 (capped)   | Model returns accurate results, but framerates are less stable than Chrome |
| Windows 10 | Firefox | Titan RTX               | ResNet34 | webcam     | 34            | Model returns accurate results, but framerates are less stable than Chrome |
| Android 12 | Chrome  | Snapdragon 865 | ResNet34 | test image | 7             | Model does not return accurate results                       |
| Android 12 | Firefox | Snapdragon 865 | ResNet34 | test image | 7             | Model returns accurate results                               |
| iPadOS     | Safari  | M1                      | ResNet34 | test image | 16            | Model returns accurate results                               |
| macOS      | Chrome  | M1 Max                  | ResNet34 | test image | 35 (reported) | Model returns accurate results                               |
| macOS      | Chrome  | M1 Max                  | ResNet34 | webcam     | 27 (reported) | Model returns accurate results                               |
</details>




## Tutorial Links

[GitHub Repository](https://github.com/cj-mills/fastai-to-unity-tutorial)

[Part 1](https://christianjmills.com/Fastai-to-Unity-Tutorial-1/): Part 1 covers training and exporting a model.

[Part 2](https://christianjmills.com/Fastai-to-Unity-Tutorial-2/): Part 2 covers implementing a trained model in a Unity project.

[Part 3](https://christianjmills.com/Fastai-to-Unity-Tutorial-3/): Part 3 covers building a Unity project to run in a web browser and hosting it using GitHub Pages.

