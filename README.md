# 📄 TensorFlow Document Classifier

This project provides a full implementation to train and deploy a document classification model using the **TensorFlow Object Detection API**. The objective is to identify whether a scanned document is a **PAN Card** or not, based on its visual features.

---

## 🧠 Project Summary

Managing KYC documents manually is time-consuming and prone to error. This classifier leverages computer vision and deep learning to automate the classification of key Indian identity documents like **PAN Card**, **Aadhar**, **Driving Licence**, and **Passport**. The trained model can process scanned document images and accurately predict the document type based on visual features.

---

## 📚 OVERVIEW

Document classification or categorization is a subfield of machine learning and NLP that assigns a document to one or more predefined categories. This project applies **image-based classification** using TensorFlow to automate document detection for KYC workflows.

---

## 🧾 1. Types of Documents:

**• PAN Card**  
A 10-character alphanumeric identifier issued by the Indian Income Tax Department.

**• Aadhar Card**  
A 12-digit identity number issued by the UIDAI, valid as both identity and address proof.

**• Driving Licence**  
Legal authorization to drive vehicles, issued by Indian transport authorities.

**• Passport**  
An official identity and travel document issued by the Indian Government.

---

## 🖼️ 2. Image Classification

Image Classification is the process of assigning a label to an entire image based on its content. Here, it is used to classify scanned documents.

---

## 🎯 3. Object Detection

Object Detection combines **classification and localization**. This project uses TensorFlow’s Object Detection API to recognize PAN card features visually from the image.

---

## 🔍 Few Unique Features of a PAN Card

### 1. Income Tax Department Stamp
<p align="center">
  <img 
    width="500"
    height="300"
    src="https://github.com/RajanikaD/Document-Classifier/blob/main/Screenshot%202022-07-19%20231316.png"
  >
</p>

---

### 2. Symbol of Lion Capital of Ashoka
<p align="center">
  <img 
    width="500"
    height="300"
    src="https://github.com/RajanikaD/Document-Classifier/blob/main/Screenshot%202022-07-19%20231332.png"
  >
</p>

---

### 3. PAN Card Number (Alphanumeric ID)
<p align="center">
  <img 
    width="500"
    height="300"
    src="https://github.com/RajanikaD/Document-Classifier/blob/main/Screenshot%202022-07-19%20231348.png"
  >
</p>

Using the above features, the model distinguishes PAN cards from other document types like Aadhar, Passport, etc.

> _*Note: These images are samples downloaded from Google for demonstration only._

---

## 🛠️ Installation & Running the Model

```bash
git clone https://github.com/RajanikaD/Document-Classifier.git
cd Document-Classifier
