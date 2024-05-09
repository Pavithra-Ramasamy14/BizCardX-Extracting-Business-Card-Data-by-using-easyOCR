# BizCardX-Extracting-Business-Card-Data-by-using-easyOCR

Introduction
In today's fast-paced business environment, efficiently managing and organizing contact information is crucial for successful networking and communication. With the advent of digital tools and technologies, manual entry of business card details into a database can be time-consuming and prone to errors. To overcome these challenges, developers can leverage the power of optical character recognition (OCR) and databases to automate the process of extracting relevant information from business cards and storing it for easy access.

One powerful OCR library that facilitates the extraction of text from images is EasyOCR. EasyOCR is an open-source Python library that utilizes deep learning models to accurately recognize and extract text from various languages. By integrating EasyOCR with a MySQL database, developers can streamline the process of capturing business card data and storing it in a structured and organized manner.

Developer Guide

1. Tools Install

    Virtual code.
  
    Jupyter notebook.
  
    Python 3.11.0 or higher.
  
    MySQL.

2. Requirement Libraries to Install

    pip install pandas,easyocr,numpy,streamlit,streamlit_option_menu

3.Import Libraries

    import easyocr 
    
    import numpy as np
    
    from PIL import Image
    
    import os
    
    import re
    
    import pandas as pd
    
    import sqlite3
  
    import streamlit as st
    
    from streamlit_option_menu import option_menu

4. E T L Process

a) Extract data
  
  Extract relevant information from business cards by using the easyOCR library

b) Process and Transform the data
  
  After the extraction process, process the extracted data based on name, designation,contact, email, website,street,city,state,
  pincode,company is converted into a data frame.

c) Load data
  
  After the transformation process, the data is stored in the MySQL database.

User Guide

Step 1. Home

In this you can see the brief description about this project

Step 2. upload and Modify

Click the 'Browse Files' button and select an image,where the text will be extracted from image.

Click the 'Save' button to upload the data to the Mysql database

Click the 'Modify' button to modify the data.

Step 3. Delete

Click the 'Delete' button to Delete the selected data.
