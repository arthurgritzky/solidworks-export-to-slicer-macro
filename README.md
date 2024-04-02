# solidworks-export-to-slicer-macro


## Streamline part export to slicer directly within SolidWorks using a macro

This repository provides a macro or automation script that streamlines exporting SolidWorks parts directly to the slicer. It simplifies the workflow by:

*  Automatically copying the selected part file.
*  Converting the file format to a format readable by the slicer.
*  Launching the slicer and importing the converted file.
  
This eliminates the need for manual file conversion and import, saving you time and effort.

![pipeline](https://github.com/arthurgritzky/solidworks-export-to-slicer-macro/assets/89546471/e344b2b7-3fb5-48fd-8386-5155a5a96fbd)

## How to install this macro / automation

1.  Download the swp file and icon for your preferred slicer and save them in a folder for later use
2.  Launch SolidWorks
   
3.  Create a new part
   
![Step3](https://github.com/arthurgritzky/solidworks-export-to-slicer-macro/assets/89546471/92bfdf5e-7de9-47e6-92f2-45961d9b3131)



4.  Open the Customize menue 
   
![Step4](https://github.com/arthurgritzky/solidworks-export-to-slicer-macro/assets/89546471/48376620-6f19-4f50-b70c-d119f52bb275)

    (open the dropdown menu next to the gear symbol and click on “Customize”)

5. Get the macro button

![Step5](https://github.com/arthurgritzky/solidworks-export-to-slicer-macro/assets/89546471/32ef75ef-def1-42bb-9049-213aa5992c72)

   (Go to category “Commands” and use the search for function to search for the “new macro button)

6. Pin the button to the feature toolbar
   
![Step6](https://github.com/arthurgritzky/solidworks-export-to-slicer-macro/assets/89546471/f5760a6f-dc5d-4dd2-9957-51312e076047)

   (Drag the button onto the “Features Toolbar”)

7. Customization of the macro button

![Step7](https://github.com/arthurgritzky/solidworks-export-to-slicer-macro/assets/89546471/a8d3c6ae-d677-406f-a1e3-23fc0dcfedf5)

  (After pinning the button, the “Custamize Macro button" window should show up.  Click the button with the 3 dots and brows to the folder with the swp files of step one. Choose the file for the slicer of your choice. The button with the person an the arrow lets you       select the icon for the button. [Note: SW requires 16x16 pixel bmp files for the button icons])   

8. Last step

![Step8](https://github.com/arthurgritzky/solidworks-export-to-slicer-macro/assets/89546471/02650a54-b540-44eb-a273-64ec0f7c6dc1)


Press “OK” to save the button settings and you are done.


## Usage

1. Open your part in Solidworks
2. Press the button for the slicer of your coice

You will b  presented with a launched slicer with the part on the build plate.

![U1](https://github.com/arthurgritzky/solidworks-export-to-slicer-macro/assets/89546471/8696071e-4180-4c69-ba70-0b3238f72589)

![U2](https://github.com/arthurgritzky/solidworks-export-to-slicer-macro/assets/89546471/0e3c349d-cf0d-4d23-b4af-e91ce6fb50c5)

![U3](https://github.com/arthurgritzky/solidworks-export-to-slicer-macro/assets/89546471/76b7aa48-9095-4949-a82c-2391bf8f834f)


## Customization

![C2b](https://github.com/arthurgritzky/solidworks-export-to-slicer-macro/assets/89546471/376a2da5-2968-44f5-b2a9-12430e862692)

The “Edit Macro” button allows you to customize the macro. The installation is identical to the first 5 steps in the installation chapter. Executing this button allows you to select swp file of the macro. Now you are able to alter the swp file. 

![C3](https://github.com/arthurgritzky/solidworks-export-to-slicer-macro/assets/89546471/28bb36a0-a935-40b5-bbc1-c328b52e3b91)

The default slicer paths are utilized in the provided files. If necessary, modify the slicer path as needed. These files are currently formatted in STEP, per the recommendation of Bambu Labs [https://wiki.bambulab.com/en/software/bambu-studio/step]. However, you have the flexibility to convert them to STL, 3MF, or any other supported format if desired. 









   




   

   




