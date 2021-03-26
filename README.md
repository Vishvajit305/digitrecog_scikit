# digitrecog_scikit

# Dependencies
1. cv2
2. sklearn
3. skimage
4. numpy
5. collections

**Here we are generating a classifier file by .pkl file that enabless objects to be serialized to files on disk and deserialized back into the program at runtime. It contains a byte stream that represents the objects. The dump method is used to pass them as string to recognize the digits.**

**`For that the generator file is runned. `**

To test the classifier, run the `performRecognition.py` script.

**python performRecognition.py -c digits_cls.pkl -i 1.jpg**
**python performRecognition.py -c digits_cls.pkl -i 2.jpg**
**python performRecognition.py -c digits_cls.pkl -i 3.jpg**

`The respective output is then displayed!`
