This Python script converts all images in a specified folder to **PNG format** using the `Pillow` library.  

### **How It Works:**
1. **Imports Required Modules**:  
   - `PIL.Image` for image processing.  
   - `os` for handling file paths and directories.  

2. **Defines the `convert_image` Function**:
   - Sets the output format to PNG.  
   - Ensures the target folder exists (`C:\ add rute`).  
   - Iterates through all files in the folder.  
   - Checks if each file is an image (JPEG, BMP, TIFF, GIF, WEBP, AVIF).  
   - Converts the image and saves it in the same directory with a `.png` extension.  
   - Prints a success or error message.  

3. **Runs the Function on Laura's Desktop Folder**:
   - Calls `convert_image(r"C:\ add rute")`, applying the conversion to all valid images in the directory.  

### **Note:**  
For AVIF support, install `pillow-avif-plugin` using:  
```sh
pip install pillow-avif-plugin
```  
Then, add `import pillow_avif` at the beginning of the script.
