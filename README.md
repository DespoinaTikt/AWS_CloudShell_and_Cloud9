# AWS_CloudShell_and_Cloud9
This is a lab I completed during my AWS re/Start training, where I explored the capabilities of AWS CloudShell and Cloud9, as shown in the diagram below.

![Screenshot (260)](https://github.com/user-attachments/assets/e228540c-1e0d-45df-947e-23c416360cf9)

## Connect to CloudShell and experiment

First of all, I connect to CloudShell from the AWS Management Console. I verify that the AWS CLI is installed, and I run a command to see all my S3 buckets.

![Screenshot (223)](https://github.com/user-attachments/assets/08e497f1-df93-404d-87fc-8368197ea1d9)

Then, I split the terminal window into 2 columns, and I test the ability to run SDK for Python code. I upload a Python file and run the cat command to view the contents of the file.

![Screenshot (224)](https://github.com/user-attachments/assets/4c68564a-2f8c-4834-85b7-7600807f5c00)
![Screenshot (225)](https://github.com/user-attachments/assets/e83c1dc2-37e6-4bde-ad48-20fd6ea01215)

After that, I run the SDK for Python code and the name of the S3 bucket is returned.

![Screenshot (226)](https://github.com/user-attachments/assets/e9cfa169-56a2-466e-9a4e-a74b512beb86)

I have now used two different programmatic ways to retrieve a list of the S3 buckets that exist in the AWS account. To conclude, I copy the Python file into my S3 bucket.

![Screenshot (228)](https://github.com/user-attachments/assets/cbe5d3b4-b762-4550-b099-a78526e3bc77)

## Explore Cloud9

Through the AWS Management Console, I navigate to Cloud9 and create a new environment. 

![Screenshot (229)](https://github.com/user-attachments/assets/1c41e9cb-586b-4db2-8be0-c80ebd717596)
![Screenshot (230)](https://github.com/user-attachments/assets/fc953d81-5bff-4dee-a6df-4af639305b87)
![Screenshot (231)](https://github.com/user-attachments/assets/15da92cc-1c25-4b1c-9e22-bd5e1b8f2790)

I open my IDE. There, in the bash terminal, I list again my S3 buckets and I download the Python file from S3 to the local storage on Cloud9.

![Screenshot (233)](https://github.com/user-attachments/assets/c5170e89-e153-4129-8567-f223374e0b0d)
![Screenshot (234)](https://github.com/user-attachments/assets/c1ca86e4-53d7-4ddb-95e3-234cc0c45b6b)

I open the Python file and try to run it. However, I get an error as the SDK for Python libraries are not installed. I run the appropriate command on the bash terminal to install the SDK for Python libraries.

![Screenshot (236)](https://github.com/user-attachments/assets/fd51f575-bd48-4f47-803a-4936cfddd415)
![Screenshot (237)](https://github.com/user-attachments/assets/5f0a0ad8-8bd6-42d9-965d-5b141e2b46e8)
![Screenshot (238)](https://github.com/user-attachments/assets/dbc79382-0f4f-43f2-88a8-0d7cb0353e45)

I run the Python code again and it is successful.

![Screenshot (239)](https://github.com/user-attachments/assets/dfe7ef4b-3c0e-4177-803e-831f68f7ac15)

Finally, I create an HTML file and save it. On the left side, I choose the AWS icon, I expand the Region, expand S3, and then expand my bucket to view its contents. I right-click on the bucket name to upload my HTML file.

![Screenshot (240)](https://github.com/user-attachments/assets/18110230-0113-4ed3-b385-5e501b69f8be)
![Screenshot (242)](https://github.com/user-attachments/assets/cc89a5a7-61e5-49cd-9da4-045904a208d4)
![Screenshot (244)](https://github.com/user-attachments/assets/7a306be6-5524-41aa-b98c-30206ad86a1e)
![Screenshot (246)](https://github.com/user-attachments/assets/4615f4d1-a5e8-4201-a68a-7138be9a4983)
