# bosch_AI_hackathon-21

RBEI Problem Statement
Robert Bosch Engineering and Business Solutions Private Limited is a 100% owned subsidiary of Robert Bosch GmbH, one of the world's leading global supplier of technology and services, offering end-to-end Software and Digital Solutions. With over 19,500 associates, it's the largest software development center of Bosch, outside Germany, indicating that it's the Technology Powerhouse of Bosch in India with a global footprint and presence in US, Europe and the Asia Pacific region. The company has IPs in industries including Agriculture, Block chain, Electric Vehicle, Energy, Healthcare, Retail, and Mobility Solutions. RBEI is in the forefront of product conceptualization, design, development, testing, industrialization of coming of age technologies including Artificial Intelligence, Cloud services, Internet of Things, Machine Learning , AR/VR, Big Data, NLP etc.

The Robotic Technology Unit of RBEI works on pre-development activities and robotic function developments for robots to be used in residential environment. We are currently in the process of prototyping an automated home cleaning robot to be used for domestic purposes. The AI model developed or an existing Pre-trained model should be capable of negotiating obstacles that includes following objects with cleaning robots Point Of View (POV).
Furniture (especially Legs/pols). Example: chair, Tables, Sofa
Doors
cables/ wires lying around
socks/ small garments
The data used for training has to be captured and labeled by the participant.
No open source images to be used if used it should be disclosed
Images (data) for training and testing the model,
has to be captured from a cleaning robot's Point Of View (POV), i.e. approximately 10 cm above ground
should not contain any personal information and should be kept anonymous
the quality of the image . i.e. resolution of the image could be 1280 x 720 (720p) User must use custom apps to capture images in this resolution and aspect ratio
The captured and labeled data has to be shared to the Host of the Hackathon
Sufficient data to be captured for training and testing the model.

Helpful Tips

The data has to be captured from a cleaning robot's Point of View (POV) (cleaning robot - Vacuum cleaner)
Usually a cleaning robot would not be taller than 10 cm, hence all the images taken should be approximately from 10 cm above ground
For capturing the images from this height, it could be useful to use a selfie stick and point it downwards and click pictures
Capture as many images as possible for a every object, from different distances, different orientation, with different backgrounds
The captured images must be of resolution 1280 * 720 also know as 720p or 1Mp. Android phone allows user to set the resolution of images to be captured. But many of them might not allow resolution as low as 1Mp in cases where the phone doesn't allow you to capture images at 1Mp, then an app could be used
For android - Lower: https://play.google.com/store/apps/details?id=com.vweeter.lower&hl=en_US&gl=US
Choose 1 Mp/ 1280*720 resolution
For Iphone - Camera Plus: https://apps.apple.com/in/app/camera-plus-frame-the-moments/id330803072
Choose the low resolution option


Data Labeling
Data has to be labeled into 4 different classes:
Furniture (especially Legs/pols). Example: chair, Tables, Sofa
Doors
cables/ wires lying around
socks/ small garments
An image can contain either one of the object from above classes or multiple of them.
Use bounding box labeling


Few sample labelled images from this point of view:



Evaluation Criteria

The participant's model should be developed using standard development tools.
Accuracy
Performance and Scalability

Note- Performance of the model will be evaluated on test data prepared by RBEI/ RTU
The model must also be light weight, i.e. its inference time on a computer with 1080 GPU, core i5 processor shouldn't take more than 100ms.


Deliverables

Presentation
This should contain model description, features, tech stack usages, and why your model should be considered for the final round.

Model
Labelled images used for Training model
Images used for Testing the model

A presentation describing the deliverables in detail. (Click here to download sample PPT)
