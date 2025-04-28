# Detecting-steganography-with-tools-like-StegExpose-analyzing-file-signatures
## AIM:
To detect hidden data using steganography detection tools like StegExpose and analyze file signatures for authenticity and manipulation.

## DESIGN STEPS:
### Step 1:
Install StegExpose or use the JAR version to detect steganography in image files.

### Step 2:
Run StegExpose on a directory of suspected image files using the command:

### Step 3:
Analyze file signatures using tools like file, binwalk, or xxd to check for inconsistencies or embedded content.

## PROGRAM:
StegExpose and File Signature Analysis Commands

## Step 1: Download Image and Create Secret Message File

• Download a .jpeg image from a trusted website or use own image

![image](https://github.com/user-attachments/assets/43e22e89-09dd-4014-aab9-b2dc4df887c7)

• Create a text file named secret with a confidential message:

![image](https://github.com/user-attachments/assets/4367416e-aba5-4017-a17e-9b27efce6b1b)

## Step 2: Install and Verify Steghide Tool

• To install Steghide on Kali linux,run:

• Confirm the installation by checking its version:

![image](https://github.com/user-attachments/assets/4757d998-6435-4d68-926a-f705774331a7)

## Step 3: Embed the Secret Message into the Image

• Use the following command to embed secret into jaimurughan.jpeg:

![image](https://github.com/user-attachments/assets/4ac8c268-9d68-406c-b58a-48e6c571b514)

## Step 4: Delete the Original Secret File

• After embedding, delete the plaintext file:

![image](https://github.com/user-attachments/assets/7652143c-632a-4459-92e5-a7637ab2148a)



## OUTPUT:
List of Images with Steganography Detection Scores and File Signature Details


## Step 1: Extract the Embedded Secret from the Image

![image](https://github.com/user-attachments/assets/92ac9d2a-b11f-471b-b7f4-461bf2eed591)

• To retrieve the hidden file: • Enter the same passphrase used during embedding.

![image](https://github.com/user-attachments/assets/64125eed-6310-4879-9e21-f267863d00f9)

## Step 2: Verify the Extracted Message

• Display the extracted file content to verify:

• Ensure the message matches the original secret content.

• Another command to see the same secret message is

## Step 3: Retrieve Information About the Embedded Data

• To gather details about embedded content in the image:

![image](https://github.com/user-attachments/assets/9a58248e-1841-4f51-a154-12fcad34db44)

• This will display file type, size, and whether data is embedded.


## RESULT:
Hidden data was successfully detected and file signatures were analyzed for irregularities.
