# Step 3: Peak Lists

## 1. Submitting Peak List Data
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