# Tensorflow Document-Classifier-Detection
This set of Notebooks provides a complete set of code to be able to train and leverage document detection model using the Tensorflow Object Detection API.
The model will identify if a document is classified as a Pan Card or not.

# OVERVIEW

Document classification or document categorization is a problem in library science, information science and computer science. The task is to assign a document to one or more classes or categories. It assigns a known set of labels to untagged documents, using a model of text learned from documents with known labels. Like document clustering, document classification draws from an enormous field of work in data mining, statistics, and machine learning.
Organizations needs to manage customer's documents by compiling personal information. It is then verified from Indian government. These KYC documents include PAN, Adhaar etc. The process of managing KYC documents manually is time consuming and costly. We can solve this problem by automating this process using AI. So, the developed application will take scanned images as input and classify the type of document it is.

# 1.	Types of documents:

__•	PAN Card:__
A permanent account number is a ten-character alphanumeric identifier, issued in the form of a laminated "PAN card", by the Indian Income Tax Department, to any "person" who applies for it or to whom the department allots the number without an application. 

__•	Aadhar Card:__
Aadhaar is a 12-digit individual identification number issued by the Unique Identification Authority of India on behalf of the Government of India. The number serves as a proof of identity and address, anywhere in India.

__•	Driving Licence:__
A driver's license is a legal authorization, or the official document confirming such an authorization, for a specific individual to operate one or more types of motorized vehicles—such as motorcycles, cars, trucks, or buses—on a public road. 

__•	Passport:__
A passport is an official travel document issued by a government that contains a given person's identity.

__2.	Image Classification:__
Image Classification is a fundamental task that attempts to comprehend an entire image as a whole. The goal is to classify the image by assigning it to a specific label. Typically, Image Classification refers to images in which only one object appears and is analysed. 

__3.	Object Detection:__
Object detection is a computer technology related to computer vision and image processing that deals with detecting instances of semantic objects of a certain class in digital images and videos. It involves both classification and localization tasks, and is used to analyse more realistic cases in which multiple objects may exist in an image.

#	Few Unique Features of a PAN Card

__1.	INCOME TAX DEPARTMENT__ 
The tax department issues an individual's PAN on a physical card referred to as the PAN card. The stamp of the same at the upper left side of the card serves as the card’s authenticity that it is indeed authorised by the tax department.

<p align="center">
  <img 
    width="500"
    height="300"
    src="https://github.com/RajanikaD/Document-Classifier/blob/main/Screenshot%202022-07-19%20231316.png"
  >
</p>

__2.	THE SYMBOL OF LION CAPITAL OF ASHOKA__
The lions are part of the Lion Capital. These lions are shown on our documents in honour of one of the greatest kings of India, Ashoka, who built the Capital. This also helps us to authenticate one’s card. It is placed at the centre top of the card.

 <p align="center">
  <img 
    width="500"
    height="300"
    src="https://github.com/RajanikaD/Document-Classifier/blob/main/Screenshot%202022-07-19%20231332.png"
  >
</p>


__3.	THE PAN CARD NUMBER__
All pan cards have a unique PAN number including alphabets. They are usually cantered at the centre of the card or on the lower left side of the card. This will help separate the PAN card from other documents such as aadhar card, driver’s license, passport, etc.
       
<p align="center">
  <img 
    width="500"
    height="300"
    src="https://github.com/RajanikaD/Document-Classifier/blob/main/Screenshot%202022-07-19%20231348.png"
  >
</p>

Using such features, we will be able to identify and classify the document type and built our document classifier model.

_*Note: These images are the samples downloaded from google._

