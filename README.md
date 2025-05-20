# 🌟ASL_Alphabet_Classification🌟

## About
This project focuses on recognizing American Sign Language (ASL) alphabets from images. The dataset used is a comprehensive collection of images representing various ASL signs, categorized into 29 distinct classes.

## Dataset Overview
The dataset is structured into separate folders, with each folder representing a unique ASL sign.

## Training Data
The training dataset is robust, consisting of 87,000 images, each sized at 200x200 pixels. It covers 29 classes:

***26 classes for the letters A-Z of the ASL alphabet.
3 crucial additional classes:
SPACE: Represents a pause or separation in signing.
DELETE: Indicates a correction or removal.
NOTHING: Signifies no active sign.***
These additional classes are incredibly valuable for developing more practical and accurate real-time ASL recognition systems.

## Test Data
In contrast to the extensive training set, the test dataset is intentionally small, containing only 29 images. This design choice encourages developers to validate their models using real-world, unseen images, promoting robust and generalized model performance rather than overfitting to a pre-defined test set.

