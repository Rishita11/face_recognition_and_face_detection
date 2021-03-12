Our project can detect Human faces also when partial occlusions such as sunglasses, scarf, mask caps are  present. 

The goal of face detection is to determine whether the image exists in the dataset and that of the Face recogniser is same. If multiple faces are present, each face is enclosed by a bounding box .

Human faces are difficult to model as there are many variables that can change for example facial expression, orientation, lighting conditions etc. As a result of this the existing face detectors and recognizers recognize faces only when partial occlusions such as sunglasses, scarf, mask caps are not present.

Local Binary Pattern (LBP) is a simple yet very efficient texture operator which labels the pixels of an image by thresholding the neighborhood of each pixel and considers the result as a binary number.In this system we are using Haar feature- based cascade classifiers .It is an effective object detection method proposed by Paul Viola and Michael Jones.We are first using OpenCv for creating a database in the computer.It will take 30 images consecutively. And then store in a folder under the name of that particular candidate. This procedure will be done only once. We can access all patterns of images with this facial recognition module which helps in maintaining security of devises. OpenCv always proves beneficial in face recognition and eye detection module.
