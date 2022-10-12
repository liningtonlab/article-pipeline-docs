# Troubleshooting

Running into error messages when trying to upload your data? You've come to the right place! In this module we will go over all possible error messages delivered by the NP-MRD platform and what they could mean for you.

# Error Messages
1. [Please check your SMILES](#error-please-check-your-smiles)
2. [Only Varian, JEOL, Bruker files are accepted](#error-only-varian-jeol-bruker-files-are-accepted)
3. [Fid file is missing](#error-fid-file-missing)
4. [.jdf is not supported](#error-jdf-is-not-supported)
5. [.mnova is not currently supported](#error-mnova-is-not-currently-supported)
6. [.nmrML is not currently supported.](#error-nmrml-is-not-currently-supported)
7. [Please make sure that the submission does not include nested zip_type file.](#error-please-make-sure-that-the-submission-does-not-include-nested-ziptype-file)


## **Error: Please check your SMILES**
This message indicates that the SMILES you have entered is not a valid SMILES string. For instructions on how to generate SMILES strings for your compounds checkout out our [Quick User Guide](index.md)

**Potential solutions:**

1. Check for (and delete) any non SMILES-valid characters in your strings.
2. If the above doesn't do the trick, you can always re-create your SMILES using ChemDraw.
3. Email us at support@npmrd-deposition.org.

<img src="https://user-images.githubusercontent.com/55040326/162302799-8a56f0e4-b6f9-4ab5-bd77-d76a8dd4eceb.png" alt="drawing" width="800"/>

## **Error: Only Varian, JEOL, Bruker files are accepted**
This is indicating that the webpage has not found NMR Data produced by one of the three manufacturers (Varian, JEOL, Bruker) in your zip file. 

**Potential solutions:**

1. Check your zip file to make sure that is really is NMR data. Have you zipped the wrong folder? Are there files missing?
2. Check to make sure that your NMR folders have parameter files in them. These files are labelled "procpar" for Varian data and "acqu/acqus" for Bruker data.
3. Email us at support@npmrd-deposition.org.

<img src="https://user-images.githubusercontent.com/55040326/162330960-e64253c8-d4a7-402b-b1d6-a95a70266899.png" alt="drawing" width="500"/>

## **Error: Fid file missing or in invalid location**
This indicates that there is a missing fid file from one of your experiments. Without this fid file we can not accept the data your are depositing.

**Potential solutions:**

1. Make sure that each experiment in the affected zip folder has a fid file or raw data file of some sort.
2. Email us at support@npmrd-deposition.org.

## **Error: .jdf is not supported.**
This error is letting you know that currently our deposition platform does not support the jdf format.

**Potential solutions:**

1. Convert the file to a .jdx format using JEOL Delta software. This is currently the only way we support submitting JEOL data. Once you have that .jdx file you can just zip that file into a folder by itself. That zip should now be depositable.
2. Email us at support@npmrd-deposition.org.

## **Error: .mnova is not currently supported.**
This is indicating that you have tried to deposit a file that in a .mnova format instead of the raw data folder.

**Potential solutions:**

1. Zip the raw data folder instead. If available try zipping the raw data folders that include parameter and fid files.
2. In the future the NP-MRD Deposition Platform is looking to accept .jdx files exported from MestreNova. If you cannot find the raw data, try coming back later and submitting a .mnova -> .jdx once our support for that file type has been developed.
3. Email us at support@npmrd-deposition.org.
## **Error: .nmrML is not currently supported.**
This is indicating that you have tried to deposit a .nmrML file. We currently don't support these file types.

**Potential solutions:**

1. Zip the raw data folder instead. If available try zipping the raw data folders that include parameter and fid files.
2. Email us at support@npmrd-deposition.org.

## **Error: Please make sure that the submission does not include nested zip_type file.**
This error is letting you know that the zip file you submitted contains other compressed files within it. In other words, you have a zip file inside of a zip file. 

**Potential solutions:**

1. Unzip the nested file. If you have zipped files inside of the larger zip file, open up that zip file and unzip all the files inside. Once this is done you should be able to rezip the larger file and deposit successfully.
2. Email us at support@npmrd-deposition.org.
