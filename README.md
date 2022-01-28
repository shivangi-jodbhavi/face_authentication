## face_authentication
User Authentication by Face recognition using insightface : AI Model which recognizes face and grants access to the user.
An end-to-end real-time face recognition system using RetinaFace to detect faces
Used a CNN feature extractor to extract embeddings. Added support for handling multiple people and online registration of new user


#### Models used for face detection and recognition :
https://github.com/deepinsight/insightface/tree/master/model_zoo

1. Face Recognition model 
WebFace600K	90.566

2. Face Detection modelRetina face-R50
RetinaFace-R5096.5

#### Sample output : 
The Model has been trained with images of Jennifer Lawrence and Bradley Cooper

As seen in the picture, both Jennifer Lawrence's and Bradley Cooper's face has been identified ( as the images of both were trained ).
However, all the rest have been marked as unknown.
Also the confidence score is mentioned for each face along with bounding box


![image](https://user-images.githubusercontent.com/71159537/151610523-3d536562-ec2f-41ee-9178-aedfb5122f16.png)
