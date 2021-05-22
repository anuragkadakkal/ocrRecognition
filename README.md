# ocrRecognition
Recognize text from the PDF and all other Image files using  ABBYY Cloud OCR SDK Console API

# Installation
Go to https://cloud.ocrsdk.com/Account/Welcome and create account, then you will get the Application ID,
Now you want to generate the password and it will be sent to your email id.
Copy that Password and Application ID and paste it on the next.php page

Now you want to select the region URL
URL of the processing service.

	$serviceUrl = 'http://cloud-westus.ocrsdk.com // US Region
	$serviceUrl = 'http://cloud-eu.ocrsdk.com'; //	European Region

# Run
Go to browser and type :
localhost/ocrRecognition

Enter the ID CARD NO and Upload the ID Document as either PDF Or any other Image Files.
Then Click Submit.