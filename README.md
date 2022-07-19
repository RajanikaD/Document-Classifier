# Tensorflow Document-Classifier-Detection
This set of Notebooks provides a complete set of code to be able to train and leverage document detection model using the Tensorflow Object Detection API.
The model will identify if a document is classified as a Pan Card or not.

OVERVIEW

Document classification or document categorization is a problem in library science, information science and computer science. The task is to assign a document to one or more classes or categories. It assigns a known set of labels to untagged documents, using a model of text learned from documents with known labels. Like document clustering, document classification draws from an enormous field of work in data mining, statistics, and machine learning.
Organizations needs to manage customer's documents by compiling personal information. It is then verified from Indian government. These KYC documents include PAN, Adhaar etc. The process of managing KYC documents manually is time consuming and costly. We can solve this problem by automating this process using AI. So, the developed application will take scanned images as input and classify the type of document it is.

1.	Types of documents:
•	PAN Card: 
A permanent account number is a ten-character alphanumeric identifier, issued in the form of a laminated "PAN card", by the Indian Income Tax Department, to any "person" who applies for it or to whom the department allots the number without an application. 
•	Aadhar Card:
Aadhaar is a 12-digit individual identification number issued by the Unique Identification Authority of India on behalf of the Government of India. The number serves as a proof of identity and address, anywhere in India.
•	Driving Licence:
A driver's license is a legal authorization, or the official document confirming such an authorization, for a specific individual to operate one or more types of motorized vehicles—such as motorcycles, cars, trucks, or buses—on a public road. 
•	Passport:
A passport is an official travel document issued by a government that contains a given person's identity.

2.	Image Classification:
Image Classification is a fundamental task that attempts to comprehend an entire image as a whole. The goal is to classify the image by assigning it to a specific label. Typically, Image Classification refers to images in which only one object appears and is analysed. 

3.	Object Detection:
Object detection is a computer technology related to computer vision and image processing that deals with detecting instances of semantic objects of a certain class in digital images and videos. It involves both classification and localization tasks, and is used to analyse more realistic cases in which multiple objects may exist in an image.

•	Few Unique Features of a PAN Card

 ![pan-card-sampel](https://user-images.githubusercontent.com/65722154/179815444-f9752bc1-7e20-48b9-809e-3c095c7b1d5b.jpg)


1.	INCOME TAX DEPARTMENT 
The tax department issues an individual's PAN on a physical card referred to as the PAN card. The stamp of the same at the upper left side of the card serves as the card’s authenticity that it is indeed authorised by the tax department.

 ![Screenshot 2022-07-19 231316](https://user-images.githubusercontent.com/65722154/179815480-2dfdb231-8c38-4c64-8928-131f584d7375.png)

2.	THE SYMBOL OF LION CAPITAL OF ASHOKA
The lions are part of the Lion Capital. These lions are shown on our documents in honour of one of the greatest kings of India, Ashoka, who built the Capital. This also helps us to authenticate one’s card. It is placed at the centre top of the card.

 ![Screenshot 2022-07-19 231332](https://user-images.githubusercontent.com/65722154/179815520-0ffd4681-db38-41c0-b237-a8d4e649dbc7.png)


3.	THE PAN CARD NUMBER
All pan cards have a unique PAN number including alphabets. They are usually cantered at the centre of the card or on the lower left side of the card. This will help separate the PAN card from other documents such as aadhar card, driver’s license, passport, etc.
       
![Screenshot 2022-07-19 231348](https://user-images.githubusercontent.com/65722154/179815549-6c481bbf-17bc-45d0-bedd-7266ddcb2403.png)

OUTPUT
![Screens![Screenshot 2022-07-19 212859](https://user-images.githubusercontent.com/65722154/179815668-e2206358-e2a9-48a6-8280-3997d73886b6.png)
hot 2022-07-19 212811](https://user-images.githubusercontent.com/65722154/179815635-21ed630c-a7b2-4041-9268-3708a3dec53a.png)

*Note: These images are the samples downloaded from google.

