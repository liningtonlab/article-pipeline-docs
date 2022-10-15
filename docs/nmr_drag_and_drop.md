# Step 2: NMR Data Drag & Drop

[Preparing Your Data For Upload](#preparing-your-data-for-upload)
1. [What Kind of Data Can I Deposit?](#what-kind-of-data-can-i-deposit)
2. [Folder Structure](#1-folder-structure)
    - [Bruker](#bruker)
    - [Varian](#varian)
    - [Jeol](#jeol)
    - [Formats That Require Additional Preparation](#formats-that-require-additional-preparation)
        - [.jdf](#jdf)
        - [.mnova](#mnova)
        - [.nmrML](#nmrml)
    - [Converting From Unsupported Formats](#converting-from-unsupported-formats)
3. [Creating Zip File of Your Data](#2-folder-structure)

[Using The Drag & Drop Interface](#using-the-drag--drop-interface)
* [Submitting](#submitting)
* [Saving For Later](#saving-for-later)

[Troubleshooting and Additional Help](#troubleshooting-and-additional-help) 
- [Error: Only Varian, JEOL, Bruker files are accepted](#error-only-varian-jeol-bruker-files-are-accepted)
- [Error: Fid file is missing](#error-fid-file-missing-or-in-invalid-location)
- [Error: Ensure that the submission does not include nested zip file](#error-ensure-that-the-submission-does-not-include-nested-zip-file)

</br>

# Preparing Your Data For Upload


## *1) What Kind of Data Can I Deposit?*

NP-MRD is a database for the deposition and display of Nuclear Magnetic Resonance Data. In order to standardize how data is processed and presented we ask that users deposit their <u>original, unprocessed data generated directly by their NMR machines</u>. Processed NMR data may also optionally be included the same zip folder as the original data.

In order to upload data to this platform NMR files containing experimental data must be organized in a standardized folder structure (which varies depending on the manufacturer of your NMR machine) and be compressed into a single archive format file (.zip, .rar, .7z, etc.).

The Drag & Drop interface accepts NMR data on a <u>compound by compound</u> basis, meaning that each compound you submit data for must be uploaded in its own zip file which contains data for <u>each of the NMR experiments performed on that compound</u>. 

</br>

## *2) Folder Structure*
Below are examples of the directory structure required for uploading data belonging to a <u> single compound</u>.

### **Bruker**
<img src="https://user-images.githubusercontent.com/55040326/179577178-8e9bf3a1-a276-432c-8a7c-33bbcd7250b0.png" alt="drawing" width="800"/>


### **Varian**
<img src="https://user-images.githubusercontent.com/55040326/179577688-d6727d48-d88e-4dc5-be72-ef1f828c0087.png" alt="drawing" width="800"/>


### **JEOL**
Our system is currently only designed to accept .jdx files and currently not support the upload of .jdf files directly. [In order to upload data stored in .jdf files they must first be converted to a .jdx file](#jdf). The processing of .jdx files takes longer than other formats so please be patient when uploading.

<img src="https://user-images.githubusercontent.com/55040326/162089401-dcde0d95-4481-4604-8eea-2fb358bf947d.png" alt="drawing"/>

</br>



## *Formats That Require Additional Preparation*

Some NMR formats are cannot currently be read directly by our system but can be submitted by first being converted to a supported format. 

</br>

### **.jdf**

*Potential solutions:*

1. Convert the file to a .jdx format using JEOL Delta software. This is currently the only way we support submitting JEOL data. Once you have that .jdx file you can just zip that file into a folder by itself. That zip should now be depositable.
2. [Convert your .jdf files to a .jdx file using MesReNova](#converting-to-jdx-using-mestrenova)


</br>

### **.mnova**
Because our system is designed for to accept original, unprocessed NMR data. As such, .mnova files cannot be accepted directly.

*Potential solutions:*

1. Zip the raw data folder instead. If available, raw data folders must include parameter and fid files.
2. [Convert your .mnova file to a .jdx file using MesReNova](#converting-to-jdx-using-mestrenova)

</br>

### **.nmrML**

*Potential solutions:*

1. Zip the raw data folder instead. If available try zipping the raw data folders that include parameter and fid files.
2. Email us at support@npmrd-deposition.org.

</br>

## *Converting From Unsupported Formats*


### **Converting To .jdx Using MestReNova**
Some formats (.jdf, .mnova) are not accepted by our system but can be converted to .jdx files which can be read by our system. If your NMR data files require conversion please follow these steps...

- **IF CONVERTING FROM .jdf**: Each .jdf file contains only a single experiment so you must first open all files in a one Mnova instance. You can do this by selecting all of your files and dragging them into an empty MestReNova window.
- **IF CONVERTING FROM .mnova**: Open your .mnova file in a MestReNova window.
- Select all of your experiments at once. You can do this by clicking the 
and then export them all into one .jdx file by right clicking Pages tab and then clicking on "Select All".
- Ensure that all of your experiments are still selected. Then export a .jdx by clicking File -> Save As and selecting JCAMP-DX as the file export type.

<img src="https://user-images.githubusercontent.com/35554126/195957872-a3278931-be37-4301-ab61-c00c7a664086.png" alt="drawing"/>
<img src="https://user-images.githubusercontent.com/35554126/195957877-946eca31-d9b6-49b7-b6c9-f0ab15c5841b.png" alt="drawing"/>

</br>

## **3) Zipping your data**
Once you have confirmed the data is in the correct file structure, each folder must be zipped separately. This means that if you have three compounds you should zip each of them to produce three separate zip folders. For instruction on how to zip your compound folders for each operating system see below:


#### **Windows 10**
<img width="800" alt="Windows10 Graphic" src="https://user-images.githubusercontent.com/55040326/162090109-900c92df-418d-4d8d-a44c-5a576b12794a.png">


#### **Windows 11**
<img width="800" alt="Windows11 Graphic" src="https://user-images.githubusercontent.com/55040326/162090126-2753f72e-d852-427a-863c-9040f4353583.png">


#### **MacOS**
<img width="800" alt="MacOS Graphic" src="https://user-images.githubusercontent.com/55040326/162090147-3857045b-5aa5-464f-a11b-6fb92c2856e3.png">


# Using The Drag & Drop Interface


# Troubleshooting and Additional Help

## *Error: Only Varian, JEOL, Bruker files are accepted*
This is indicating that the webpage has not found NMR Data produced by one of the three manufacturers (Varian, JEOL, Bruker) in your zip file. 

**Potential solutions:**

1. Check your zip file to make sure that is really is NMR data. Have you zipped the wrong folder? Are there files missing?
2. Check to make sure that your NMR folders have parameter files in them. These files are labelled "procpar" for Varian data and "acqu/acqus" for Bruker data.
3. Email us at support@npmrd-deposition.org.

<img src="https://user-images.githubusercontent.com/55040326/162330960-e64253c8-d4a7-402b-b1d6-a95a70266899.png" alt="drawing" width="500"/>

</br>

## *Error: Fid file missing or in invalid location*
This indicates that there is a missing fid file from one of your experiments. Without this fid file we can not accept the data your are depositing.

**Potential solutions:**

1. Make sure that each experiment in the affected zip folder has a fid file or raw data file of some sort.
2. Email us at support@npmrd-deposition.org.

</br>

## *Error: Ensure that the submission does not include nested zip file*
This error is letting you know that the zip file you submitted contains other compressed files within it. In other words, you have a zip file inside of a zip file. 

**Potential solutions:**

1. Unzip the nested file. If you have zipped files inside of the larger zip file, open up that zip file and unzip all the files inside. Once this is done you should be able to rezip the larger file and deposit successfully.
2. Email us at support@npmrd-deposition.org.
