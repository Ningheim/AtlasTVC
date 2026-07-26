# AtlasTVC
An easily edit-able TVC mount model for any rocketry hobbyist to use on their own rocket. From the clearance between gimbals, to the motor tube outder diameter that you'll be using with this design, everything here is easily adjustable via the variables seen inside the onshape document.


<img width="808" height="636" alt="Atlas" src="https://github.com/user-attachments/assets/83ae976b-abd3-4c06-a9a3-81ab90df1e68" />

Access the onshape document [here](https://cad.onshape.com/documents/687bb891e5fdc86e637405f0/w/7709ffe7004c15a579f76044/e/4d2dc5f323421dbaa3c98495?renderMode=0&uiState=6a65378148685660edb522a3)
Printed model available on [Printables](https://www.printables.com/model/1791204-atlastvc)
*Note: I can't Commit the native CAD source file since the only option is to share via a link*

## Adjustments
Ok as you can see below, the variables control the form factor of the amount so you can adjust it to adhere to whatever you'd like:
<img width="209" height="515" alt="image" src="https://github.com/user-attachments/assets/405f4a75-8845-48ff-96cb-2532fa482569" />
<br>
Here's a brief description of each variable so you know exactly what each one represents
#### MotorTubeOD
Outer diameter of the motor tube the mount is built around
#### BaseThickness
This adjusts the thickness of the innermost gimbal, the specific part is called "Base Rig"
#### SecondaryThickness
This adjusts the thickness of the middle gimbal, the specific part is called "Secondary Rig"
#### TertiaryThickness
This adjusts the thickness of the outermost gimbal, the specific part is called "Tertiary Rig"
#### Clearance
Gap between the Base Rig and Secondary Rig axes so they can pivot freely without binding
#### Clearance2
Gap between the Secondary Rig and Tertiary Rig axes so they can pivot freely without binding
#### AxisSize
Diameter of the pivot axis pins connecting each gimbal ring
#### Servo1Offset
Mounting offset for the first servo. The servo head/servo horn needs to be tangent in a way to the cylindrical part it's going to be pushing and pulling on. You'll see reference picture later on in this document.
#### Servo2Offset
Mounting offset for the second servo. The servo head/servo horn needs to be tangent in a way to the cylindrical part it's going to be pushing and pulling on. You'll see reference picture later on in this document.

*NOTE: I have the servo mounts set to fit Miuzei MG90 Servos from the dimensions [here](https://manuals.plus/asin/B0BWJ26PX2). You can redesign the mounts to fit your own but MG90s are often the gold standard for TVC in hobby rocketry*

## Assembly
The [onshape document's](https://cad.onshape.com/documents/687bb891e5fdc86e637405f0/w/7709ffe7004c15a579f76044/e/4d2dc5f323421dbaa3c98495?renderMode=0&uiState=6a65378148685660edb522a3) assembly tab has the assembly with movable parts and a detailed render to help you mirror it with your own design. You can use this as a type of Demo.
<br>
<img width="191" height="268" alt="image" src="https://github.com/user-attachments/assets/6db4b9f5-505b-4425-a430-c66e84a5d5e0" />

<br>
First, you align the circular __indentations__ of the innermost gimbal and __holes__ of the secondary gimbal, then you insert the first pair of axis defining rods into the circular opennings to lock the pair in place. Once they're through, glue the circular faces of the axis-defining rods to the __circular indentations__ on the innermost gimbal.

*NOTE: Sand the edges if you need to, all printers have imperfections so if the fit is too tight for you, sand the edges*

Next, you align the circular __indentations__ of the secondary gimbal and __holes__ of the outermost/tertiary gimbal, then you insert the second pair of axis defining rods into the circular opennings to lock the pair in place. Once they're through, glue the circular faces of the axis-defining rods to the __circular indentations__ on the secondary gimbal.

And after that, it's pretty straight forward, you can just slap the servos onto the notches, code them to your needs, and slide in the rocket to get ready to test and launch your TVC system. Make sure the servos are oriented with the wires going out the designated wire holes on each servo mount.

Once you secure the servos onto the model, use servo horns and use a thin firm rod to attach the servo horns and the plastic. Since the rod is going to be linked to the smooth round siding of the cylindrical gimbals, heat the rod up and melt the plastic a little with a soldering iron or something similar. And once it cools down it will form a firm adhesion.

The attachment below is what it should look like fully operational

https://github.com/user-attachments/assets/b01e91cf-8fe1-4efc-a3f6-5ec3da026bce

## Production

Material: Use PETG as it handles the heat from the rocket tube environment than cheaper ones like PLA. It's also less-brittle which can come in handy if the plastic faces stress from servo torque.

Layer height: 0.2mm.

Infill: 30-40%, since this does go into a rocket, under-filling would be detrimental and risks the entire rocket blowing up or someone getting hurt.

Supports: The servo mounts would need some supports as they have a lot of 90 degree drops and sharp corners that require support usage. Everything else is pretty independent of supports since they're mostly just cylinders that are printed straight up.

Orientation: Print the Base Rig, Secondary Rig, and Tertiary Rig flat on their circular faces. Same with all the other cylinders. You will definitely need supports for some of the rigs that have servo mounts on them.

Tolerances: This design was for a standard 0.2mm tolerance. You still might have to sand down some of the parts to ensure they can move past eachother.
