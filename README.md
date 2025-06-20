# hub8735 bit Arduino SDK 

## 1. About hub8735 bit Arduino

> The hub8735 bit Arduino SDK is base on HUB8735 & HUB8735 ultra
> The version mapping is following below.

|hub8735 bit Version      		| HUB8735 ultra Version       |Remarks                         					|
|:--------------------------|:---------------------|:---------------------------------------------------|
|`4.0.15-hub8735bit` 		    |`4.0.15-Release`      | ***new create***                                  |
</br>

## 2. How to add hub8735bit package to `Arduino IDE`:

1. **Add Ameba Arduino SDK link to *Arduino IDE Additional Boards Manager***

    > Arduino IDE 1.8.19 and above versions support third party hardware so please make sure to use the latest Arduino IDE for better experience.

    Therefore, you need to add hub8735bit Arduino SDK link in 
    
    **"File" -> "Preferences" -> "Additional Boards Manager URLs:"**

    Copy and paste the following link into the field and click "OK",

    https://github.com/H-owar-d/hub8735bit_arduino/raw/main/Arduino_package/hub8735bit.json

    > We also suggest to enable "Show verbose output" options on "compilation" and "upload" in Preference for easier debugging.
    
    </br>

2. **Install Ameba board in *"Board Manager"***

    Open **"Tools" -> "Board" -> "Board Manager"**, wait for it to update additional hardware configurations, then type **"HUB8735"** in the search bar, you will see **"hub8735bit"** in the list.

    Press **"Install"** to start the installation.
    
    </br>

3. **Select your Ameba model in *"Tools" -> "Board" -> "AmebaPro2 ARM (32-bits) Boards - ideasHatch"***

    > Make sure you select the correct model for your board, otherwise your program might not work properly 

    Now you are **ready** to develop and upload firmware onto Ameba.

    For more information, please refer to https://www.amebaiot.com/en/ameba-arduino-summary/
    
    </br>
## 3. License:

> The overall project is licensed under the MIT License. See the [LICENSE](https://github.com/ideashatch/HUB-8735/blob/main/amebapro2_arduino/LICENSE.txt) file for details.
