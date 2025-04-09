# TrainModel  
Learning how to train a custom model    

custom dataset 
![image](https://github.com/user-attachments/assets/0a71b016-a792-4cdd-993d-3484460ec228)

using Anaconda to install label studion for annotation.  

creating a new python env for installing labelstudio for running yolo models   
--> conda create --name yolo-env1 python=3.12  
activate    
--> conda activate yolo-env1  
install label studio in the environment  
--> pip install label-studio  
  
To run labelstudio  
--> label-studio start  
(label studio runs on a server that is hosted locally on the browser)  

after running the complete google colab, download my_model zip file.   
On anaconda prompt, go to the my_model directory  
ultralytics library to run inference with the model  
--> pip install ultralytics  

python script to run the model(github - https://github.com/EdjeElectronics/Train-and-Deploy-YOLO-Models )  
--> curl -o yolo_detect.py https://www.ejtech.io/code/yolo_detect.py  
to run the script  
--> python yolo_detect.py --model my_model.pt --source usb0 --resolution 1280x720  


results  
![results](https://github.com/user-attachments/assets/daec2385-569a-4e56-978c-ff3b15f7c904)

