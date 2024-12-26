# QR-CODE-GENERATOR

### DATE: 26-12-2024

### NAME: KISHORE.M

## AIM: TO GENERATE A QR CODE USING PYTHON IN VISIUAL STUDIO.

## ALGORITHM: 
## STEP 1: First you need to install qrcode and image in CMD using this command (pip install qrcode) and (pip install image).
## Step 2: The next step is to create a new file so open your file explorer and create a new file.
## Step 3: Now  open your visual studio code and import the file you have created in file explorer.
## Step 4: now write the program for qr code generator.
## Step 5: rum the program.
## Step6: check for final output.

### PROGRAM :
```
import qrcode
import image
qr=qrcode.QRCode(
    version = 5, 
    box_size = 5, 
    border = 7

)
data = "KISHORE"
qr.add_data(data)

qr.make(fit = True)

img = qr.make_image(fill="black", back_color = "yellow")

img.save("test.png")

```
-----------------------------------------------------------------------------------------------------
### PROGRAM EXPLANATION: 

### 1.Import Libraries:
     ->Import the qrcode library for generating QR codes.
     ->Import the image library for handling image operations.

### 2.Initialize QR Code Object:
     ->Create a QRCode object with specific parameters:
     ->Example:
  --------------------------------------------------------------------
     ->version = 5: Specifies the size of the QR code.                 
     
    -> box_size = 5: Specifies the size of each box in the QR code.
     
     -> border = 7: Specifies the border size around the QR code.

--------------------------------------------------------------------------
### 3.Add Data:
     ->Add the data "YOUR DATA" to the QR code object using the add_data method.
   
### 4.Generate QR Code:
    ->Call the make method with fit = True to generate the QR code.
    
### 5.Create Image:  
    ->Create an image from the QR code using the make_image method with the following parameters:
    ->Example
------------------------------------------------------------------------------------------
      fill = "black": Specifies the color of the QR code.

      back_color = "yellow": Specifies the background color of the QR code.
-----------------------------------------------------------------------------------------

### 6.Save Image:
    ->Save the generated QR code image as "test.png" using the save method.
    
------------------------------------------------------------------------------------------------------

### FINAL RESULT:

C:\Users\Kishore\OneDrive\Desktop\pyproj\python





