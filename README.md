
# Thermal Infrared Object Detection For Aerial Crafts 

Thermal infrared object detection for aerial crafts is a cutting-edge technology that enables unmanned aerial vehicles (UAVs) and drones to identify and locate objects or subjects using thermal imaging. This capability is particularly valuable in applications such as search and rescue, surveillance, and monitoring, where traditional optical cameras may be limited by poor visibility or low-light conditions. By detecting heat signatures, these systems enhance the effectiveness of aerial platforms, making them indispensable tools for various industries, including public safety, agriculture, and infrastructure inspection.

## Downloading the Project Repo

The GitHub link for the code is https://github.com/TINOREJI/Thermal-Infrared-Object-Detection-For-Aerial-Crafts

##  Project
->This project is worked with tools like Tensorflow, Flask, and YOLOv8.

->When you install requirements.txt and make Flask Environment you can directly call the project.

## Model Training and Testing
#### Training
Open INFRARED_OBJECT_DETECTION_FOR_AERIAL_CRAFTS .ipynb in Jupyter Notebook or VS Code.
Run Each Section of the Code Except Training and Model Evaluation. 
#### Testing
For Testing, we can run the Model Validation Part with 
```bash
!yolo task=detect mode=predict model=runs\detect\yolov8m_v8_50e23\weights\best.pt source="upload/test2.jpg" 
```
where you can change the testing image by pasting the image location to `source=" "` or we can test for videos also.

The Predicted Output will be stored in `.runs/detect/`

## Run Locally Infrared Object Detection Application
After Downloading Repo and Opening the Folder in VS Code or PyCharm.

Create and activate a virtual environment, as follows:
```bash
  $ cd Thermal-Infrared-Object-Detection-For-Aerial-Crafts
  $ py -3 -m venv .venv 
  $ .venv/Scripts/activate
```
### OR

```bash
  $ cd Thermal-Infrared-Object-Detection-For-Aerial-Crafts
  $ python3 -m venv .venv 
  $ cd .venv/bin
  $ chmod 775 activate
  $ ./activate
  $ cd ..
  $ cd ..
```
Install Requirements

```bash
  pip install -r requirements.txt
```

After that, you can run the following command and access the application at 127.0.0.1:5000 on your browser.
```bash
  $ python app.py
```
![Screenshot 2023-10-25 043501](https://github.com/TINOREJI/NP/assets/95184183/983bd6ef-3032-459f-b3d8-6a6cc1cad3f5)


## Testing WEB Application
### Upload the Infrared-Thermal Images

![test](https://github.com/TINOREJI/NP/assets/95184183/608cdc1c-010b-4fe9-9fb8-0a5e6dde4e7e)

![test2](https://github.com/TINOREJI/NP/assets/95184183/0a74c8e3-9830-40f9-89df-02b10b77a16c)

![1_60_60_0_00446](https://github.com/TINOREJI/NP/assets/95184183/a0435a7c-d721-47ab-9399-14e82157c589)

## Results/Output
![test](https://github.com/TINOREJI/NP/assets/95184183/ccc546e7-9de2-4d23-92bf-3e4a730e2e7b)

![test2](https://github.com/TINOREJI/NP/assets/95184183/08b05572-4608-4faa-bd52-8e131d322824)

![image0](https://github.com/TINOREJI/NP/assets/95184183/6c4dc0a0-4bb1-462a-922a-a69d8dd4284a)



