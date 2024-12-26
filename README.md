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


