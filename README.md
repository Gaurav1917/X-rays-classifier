# X-rays-classifier
## 1.Dataset:  
### Kaggle:https://www.kaggle.com/datasets/tawsifurrahman/covid1-radiography-database 
     
## 2.VGG16 model:
### https://www.tensorflow.org/api_docs/python/tf/keras/applications/vgg16/VGG16  
         
## 3.Explanation about project:
       The dataset has two parts(Train,Test).The training dataset has four classes (COVID,lung_opacity,Normal,Viral_Pneumonia), the total images                         in training dataset is 16798.

       *Training Data(images): 
       COVID - 2901, lung_opacity - 4813, Normal - 8003,Viral_Pneumonia - 1081   
       *Test Data(images): 
        COVID - 715,lung_opacity - 1199, Normal - 2189,Viral_Pneumonia - 264

  The model is made by using CNN(convolutional neural network). As we don’t have a large dataset so ,either you can generate image from ImageDataGenerator 
  or use transfer learning ,here we used technique Transfer learning(VGG16 model) . The training accuracy we got from the model is 94% and test accuracy 
  is 90%. 
  
  For deployment we used a gradio interface: https://www.gradio.app/docs/interface 

## 4.Visualisation:
### VGG16 model-

![download (21)](https://github.com/Gaurav1917/Radiography-test-classifier/assets/146158309/6cc7596e-3c3c-4804-8901-614eeee4ae69)

![download](https://github.com/Gaurav1917/Radiography-test-classifier/assets/146158309/c8ee2507-c51d-4e90-b6ed-9a0309c1bea6)

![download (1)](https://github.com/Gaurav1917/Radiography-test-classifier/assets/146158309/8026823b-ad71-45e2-a152-3ad89dcbbc40)

### Dense Layer-

![download (2)](https://github.com/Gaurav1917/Radiography-test-classifier/assets/146158309/cfd58e33-a0af-450b-8f61-e726304e537f)

![download (3)](https://github.com/Gaurav1917/Radiography-test-classifier/assets/146158309/b00e6959-b42d-44c4-b15a-959000ca39fb)

![download (4)](https://github.com/Gaurav1917/Radiography-test-classifier/assets/146158309/c13e9490-df05-4519-a04e-ad9ccc864535)


### Accuracy plot-

![download (5)](https://github.com/Gaurav1917/Radiography-test-classifier/assets/146158309/4e98b5e9-44f7-4eae-8c31-9dd0827938d2)

![download (6)](https://github.com/Gaurav1917/Radiography-test-classifier/assets/146158309/38577228-0b9f-42ff-ad67-f7b23b5e909a)



   ## 6.DRIVE LINK : https://drive.google.com/drive/folders/1Uy9mx5O0kMHl_kXbJmBp6mdXSXLPJeLB?usp=drive_link                                         

## 5.Sample 1

![sample_test_1](https://github.com/Gaurav1917/Radiography-test-classifier/assets/146158309/7a9616c3-2d48-4e6f-9a12-df0dcebf9b9f)

## 6.Sample 2
![sample_test_2](https://github.com/Gaurav1917/Radiography-test-classifier/assets/146158309/08e316e7-466e-479c-a0c0-0e3315d39fc9)


##
https://huggingface.co/spaces/Gaur1917/Radiography_test/tree/main
Check by clicking url.


