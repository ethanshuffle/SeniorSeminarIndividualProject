# SeniorSeminarIndividualProj
 An Android app that uses the PyTorch machine learning model resnet18 for image segmentation.

 By loading in a pretrained model; resnet18, we can load in images from the Android photo gallery to be identified.

The app can be emulated inside of Android Studio, by navigating to the top left of the screen and selecting the device manager to setup a virtual device. This is located in the drop down menu next to the Android logo that says "app". When you do this, you can choose the type of device you would like to emulate. After setting up your device, press the green arrow to the right of it and it will open an emulation window. Now mouse clicks function as screen presses and keystrokes can type into appropriate fields. When initializing the emulator, it will by default load up the app selected.

To use the app, boot it and you will have two buttons to choose from; "Load Image From Gallery" and "Scan Image". Selecting Load Image From Gallery opens the devices photo gallery, and you may select one image to scan. When you do, the image you selected will be displayed on the upper half of the screen so you may verify your selection. When you are ready, you press the Scan Image button, and after a few moments, text will appear with the closest approximation to what the model believes the image to be will appear!
