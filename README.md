# FCN_Specular_Detection

You need install **keras** to run this code

## Training dataset

**CVC-EndoSceneStill**(need register):http://www.cvc.uab.es/CVC-Colon/index.php/databases/cvc-endoscenestill/

"bbdd" and "gtspecular" is enough for specular detection, 
but you need transform BMP images to PNG images because there will be an error when decoding the BMP image by using the tensorflow

Database related to the paper “A Benchmark for Endoluminal Scene Segmentation of Colonoscopy Images” (D. Vázquez, J. Bernal, F.J. Sánchez, G. Fernández-Esparrach, A.M. López, A. Romero, M. Drozdzal and A. Courville)

## FCN model
This code modify [DnCNN-keras](https://github.com/cszn/DnCNN/tree/master/TrainingCodes/dncnn_keras) as the FCN model

## Results
![14](https://github.com/jiemojiemo/FCN_Specular_Detection/blob/master/CVC-612/bbdd_png/14.png?raw=true)
![14](https://github.com/jiemojiemo/FCN_Specular_Detection/blob/master/results/14.png?raw=true)

![597](https://github.com/jiemojiemo/FCN_Specular_Detection/blob/master/CVC-612/bbdd_png/597.png?raw=true)
![597](https://github.com/jiemojiemo/FCN_Specular_Detection/blob/master/results/597.png?raw=true)

![501](https://github.com/jiemojiemo/FCN_Specular_Detection/blob/master/CVC-612/bbdd_png/501.png?raw=true)
![501](https://github.com/jiemojiemo/FCN_Specular_Detection/blob/master/results/501.png?raw=true)
