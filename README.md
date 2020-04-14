# Libre health

## Model to predict the pneumonia and other 14 types of diseases using Deeplearning models. 

## To deploy on local machine -

Create a new environment

1. Clone this repository
```
git clone https://github.com/Parag0506/Chest-xray-diagnosis.git
```

3. Install requirements.txt
```
pip3 install -r requirements.txt
```

4. Cd into the project directory and run the following in terminal:
```
python app.py
```

5. Navigate to [http://127.0.0.1:5000/](http://127.0.0.1:5000/) and upload your image



### The Model is trained on the following keras transfer learning libraries: <br>
VGG16<br>
VGG19<br>
DenseNet121<br>
ResNet50<br>
InceptionV3<br>
InceptionResNetV2<br>
NASNetMobile<br>
NASNetLarge<br>

## USE
Visit : 
https://checxray.herokuapp.com/

Upload any xray image you need to scan. [for now it supports only 1024*1024 image sizes]
There is a folder in the repos containing sample x-ray images of the required size.  
