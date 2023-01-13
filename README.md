# Hand-Gesture-Recognition

## Final Project for CAP 5415: Computer vision
We have used the Google’s high-fidelity hand and finger tracking API, [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands.html), as feature extractor of hand skeletal features. Used images from a recently published dataset for hand gesture detection, [HAGRID](https://github.com/hukenovs/hagrid).
Trained multiple Machine Learning models on the extracted data to recognize hand gestures.

![image](https://github.com/RRJahin/Hand-Gesture-Recognition/blob/main/figure/landmark.png)

### Trained Models:

![image](https://github.com/RRJahin/Hand-Gesture-Recognition/blob/main/figure/result%20table.png)

### DNN
3 fully connected layers consisting of 256, 128, and 128 neurons followed by ReLU activation and dam optimizer. 
Learning rate of 0.0005 for optimizing the model over categorical cross-entropy loss.


![image](https://github.com/RRJahin/Hand-Gesture-Recognition/blob/main/figure/dnn.png)

### CNN
2 convolutional layers followed by ReLU activations and 50% dropout. The output is then fed to 3 fully connected layers consisting of 128, 64 and 6 neurons, where the first two FC layers are followed by ReLU activation and the last one by softmax activation. 

![image](https://github.com/RRJahin/Hand-Gesture-Recognition/blob/main/figure/cnn.png)


## Downloads

### Subsample
Subsample has 100 items per gesture.

| Subsample   | Archives                                | Size   |
|-------------|-----------------------------------------|--------|
| images      | [`subsample`](https://sc.link/AO5l)     | 2.5 GB |
| annotations | [`ann_subsample`](https://sc.link/EQ5g) | 1.2 MB |

### Subsample Processed
Hand landmarks - gesture labeled

[Subsample Processed Data](https://drive.google.com/drive/folders/1XKNCdbr5Wc508t4-MlyJl33EYJmbShPi?usp=share_link)

### Dataset

| Gesture                           | Size     | Gesture                                   | Size    |
|-----------------------------------|----------|-------------------------------------------|---------|
| [`call`](https://sc.link/ykEn)    | 39.1 GB  | [`peace`](https://sc.link/l6nM)           | 38.6 GB |
| [`dislike`](https://sc.link/xjDB) | 38.7 GB  | [`like`](https://sc.link/r7wp)            | 38.3 GB |
| [`fist`](https://sc.link/wgB8)    | 38.0 GB  | [`rock`](https://sc.link/kMm6)            | 38.9 GB |

### Processed
Hand landmarks - gesture labeled

[Processed Data](https://drive.google.com/drive/folders/19wKKwwZXYvPMpVrduEme5ZUc3IRVXGiF?usp=share_link)

Repost can be found here: [report.docx](https://docs.google.com/document/d/1wpoQmiob-CaOBQlJtX8fp1jDVErE-x6I/edit?usp=share_link&ouid=100550617693029965264&rtpof=true&sd=true)
