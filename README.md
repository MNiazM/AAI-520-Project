# AAI-520-Project
USD-AAI-520 Final Project

This repository contains the final project for the AAI-520 course work. 
This project is on Multi-Turn Contextual Chatbot. 

This repository has Flan-T5 based Chatbot as well as GPT-4.0 mini based Chatbot. 

Flan-T5 based Chatbot model:
============================
CornFlanT5_Trainer.ipynb trains the model. This code has been developed in google collab. 
The Cornell Movie Dialog Corpus is expected at ../Data/Cornell Directory

CornFlanT5_Chatbot.ipynb runs the chatbot with the trained model files
Trained model files are expected at ./flan_t5B_cornell_150k

Trained model files are stored in this repository with the directory name "flan_t5B_cornell_150k"
This directory requires an additional file by name model.safetensors which can be accessed from the following google drive link. 
https://drive.google.com/file/d/1URi9vWjrh2Dyb3B-31bUWngro_5Sb4Qe/view?usp=sharing

GPT-4o mini based Chatbot model:
================================
The model training code is available at Gpt4o_Mini.ipynb

The live link is running at https://group3-usd.streamlit.app/

Documents
=========
All the documents are available at the Documents Directory

Video Presentation:
==================
Video presentation on this repository is available at 
https://youtu.be/KKSgcqg9Sxs
