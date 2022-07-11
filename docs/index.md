# Quick User Guide
For those looking to deposit data with published or un-published articles, this guide will give you all the information you need to make a quick and easy deposition. 

# Deposit your first article.
## 1. Prepare your Data.
Although npmrd-deposition.org is a drag and drop data deposition platform, we still ask for some preparation to be done on the NMR-data folders.
### i) **Folder Structure**
The npmrd-deposition takes NMR-data on a compound by compound basis. In other words, we ask that each compound being submitted have its own folder which contains the NMR experiments pertaining to that compound. Below are example folders displaying the structures for folders containing data on a compound. There are three examples, one for each NMR manufacturer.


#### **Bruker**
<img src="https://user-images.githubusercontent.com/55040326/162089179-123ab9f8-90e1-4de5-89a4-8a8f7ad60a3d.png" alt="drawing" width="800"/>


#### **Varian**
<img src="https://user-images.githubusercontent.com/55040326/162089387-1422a4b6-4d2a-441f-b3bc-cd605dbd48f0.png" alt="drawing" width="800"/>


#### **JEOL**
<img src="https://user-images.githubusercontent.com/55040326/162089401-dcde0d95-4481-4604-8eea-2fb358bf947d.png" alt="drawing"/>


### ii) **Zipping your data**
Once you have confirmed the data is in the correct file structure, each folder must be zipped separately. This means that if you have three compounds you should zip each of them to produce three separate zip folders. For instruction on how to zip your compound folders for each operating system see below:


#### **Windows 10**
<img width="800" alt="Windows10 Graphic" src="https://user-images.githubusercontent.com/55040326/162090109-900c92df-418d-4d8d-a44c-5a576b12794a.png">


#### **Windows 11**
<img width="800" alt="Windows11 Graphic" src="https://user-images.githubusercontent.com/55040326/162090126-2753f72e-d852-427a-863c-9040f4353583.png">


#### **MacOS**
<img width="800" alt="MacOS Graphic" src="https://user-images.githubusercontent.com/55040326/162090147-3857045b-5aa5-464f-a11b-6fb92c2856e3.png">

## 2. Getting a deposition link.
In order to deposit into the NPMRD, you must visit a submission link unique to your deposition. This link can be obtained in one of two ways depending on whether or not you have recieved an email from npmrd-deposition.org. Follow the instructions for the case that matches you.
### i) **I recieved an email.**
Your unqiue link can be found within the body of the email. Accessing the page is as easy as clicking the hyperlink or copy pasting it into your address bar.
### ii) **I did NOT recieve an email.**
If you did not recieve an email your method of arriving at your deposition page will be based on wether or not your data is from a published article or an unpublished article. Please follow the case that applies to you below.

#### 1. My data is from a PUBLISHED article.
To get to a deposition page you will need to submit your doi through the deposition [front page](http://npmrd-deposition.org/). Once on the front page, you will first have to specify that your data is from a published article. This should load a page with a search bar where you will paste your doi and click "Submit". 

<img src="https://user-images.githubusercontent.com/55040326/161645503-5cb17cc5-ba2a-4b03-b19f-256355af6189.png" alt="drawing" width="600"/>

Once you submit the doi, you should be brought to your unique deposition link.

#### 2. My data is from an UNPUBLISHED article.
To get to your deposition page from here you will have to select the UNPUBLISHED option on the [front page](http://npmrd-deposition.org/). This will take you to another page where you will be prompted to enter information about your unpublished article.

<img width="1327" alt="Unpublished Info Page" src="https://user-images.githubusercontent.com/55040326/178079007-2297702a-1790-47e4-96b4-a3c08faef486.png">

Here the entries to be filled out are as follows:

- Submission Type: New Submission or and In-progress submission
- Article Title: The title of the unpublished article.
- Email: An email you would like to be contacted at when you article is published.
- Authors: A commas separated list of the authors of your article.
- When would you like us to display the deposited data?: When embargo period ends, immediately, or once the article is published

Once you complete this page and click next you will be taken to the first step in your deposition process.

## 3. Entering your Compound Info.
This is the first step in the deposition process for both depositors with published and unpublished articles. On this page you will be prompted to enter info about the compounds you are depositing. The deposition software will also attempt to pre-fill this info for you if it is able to find your article.

<img width="1271" alt="Enter Compound Info" src="https://user-images.githubusercontent.com/55040326/178080744-5e24573b-f0a9-4a97-a34d-c0c2cb9f76e1.png">

Once the compound info is filled click next to proceed to the second step in your deposition process. Here you will be asked if you intend to deposit raw NMR data. If the answer is yes, see step 4.

## 4. Depositing Raw NMR Data.
Below is an image of the raw nmr data deposition page. On this page you will see the compound info you entered paired with the structure of that compound and a deposition box. A deposition workflow should include:
- Ensure your compound info matches the structure presented.
- Drag and drop your prepared raw data zips into the corresponding boxes. (You may also click on the box to bring up the file explorer.)
- Wait for the upload and check that no errors were presented.
- Click submit to finalize your nmr submission.

Note: All submissions are final so be sure to triple check your data before clicking the submit button.

<img width="1311" alt="Depositing Raw NMR Data v1.2" src="https://user-images.githubusercontent.com/55040326/178318866-c595fe47-efeb-4928-8e12-22bd28b15e7e.png">

Once this data is submitted you will be asked if you have any peak lists you would like to submit. If the answer is yes, see step 5.

## 5. Submitting Peak List Data
On this page you will see the compound info you entered, the structures, and some text boxes. If you have not done so on the nmr data page, please check over your structures and compound info to ensure correctness. After doing so you will need to copy and paste you peak lists into the text boxes and click "Validate".

<img width="1290" alt="Peak List Submission" src="https://user-images.githubusercontent.com/55040326/178322118-f714630f-83d7-4e55-bd02-fd4e40cc24cd.png">

From here you will most likely get many errors in reference to your peak lists. The format for which peak lists are accepted is quite strict so below is a guide to submitting sucessfully.

### Peak List Formatting Guide

When pasting your peak lists, make sure that the pasted content follows the below guidelines.

#### 1. Must be in list format.
- The peaks lists should be in some sort of list format with either , (commas) or ; (semicolons) as separators. 
- Ex. 1,2,3,4,5

#### 2. Only contains valid characters.
- The submitted peak list must contain numerical digits or only characters found here: ( ) . , ; -

#### 3. Overlapping peaks should be expressed as ranges.
- To express a range use - (dashes) in between the min and max values.
- Example of a list with a range: 1,2,3,5-7,8 OR 1,2,3,(5-7),8

#### 4. The number of values should not exceed the number of atoms.
- Ex. If your structure has 4 unique Hydrogen atoms, the H peak list should not exceed 4 in length.

#### 5. The values should be within a reasonable range for the type of atom they are referencing.
- Ex. If your peak list is a H peak list the values in the list should not exceed 20.

If you have followed all the guidelines above then your peak lists should present green tables when you click "Validate". Once all the peak lists present green, you can go ahead an click the "Submit" button.

# Congratulations!
Your deposition has been completed! You should now be on the sucess page and see a check list of all the types of data you deposited. If you would like to make an changes from here please email support@npmrd-deposition.org. 

Thank you for taking the time to deposit data with us! 
