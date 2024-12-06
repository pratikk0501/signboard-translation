# signboard-translation
* This project is titled 'Signboard Translation of Vernacular Languages' done under the online course 'Deep Learning' offered by Padhai, One Fourth Labs.
# Project Description
* The aim of this project is to translate the text written on a signboard to another language as desired by the user. However, in this project, only hindi to english conversion is done; but it can be extended to other languages.
* This project can be divided into three divisions:
1. Text Region Detection: This part focuses on detecting bounding boxes that contain signboard objects(mainly text) in the given image. This can be done using an object detection engine like YOLO V5.
2. Recognition of individual characters: This task entails getting the text from the cropped signboard and converting it into text using a CNN-RNN encoder decoder model.
3. Natural Language Processing for translation/transliteration: Here, a sequence-to-sequence encoder decoder model with attention is used for transliterating the above sequence of characters to the desired language. The overall accuracy for this task came out to be 0.903.
