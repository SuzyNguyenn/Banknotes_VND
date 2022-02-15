# Banknotes_VND
<p align="center">
  
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
  
</p>

<p align="center">
  <a>
    <img src="https://raw.githubusercontent.com/CHP2108/Banknotes_VND/main/panda_girl.gif" alt="Logo" width="180" height="140">
  </a>
  <h3 align="center">Time goes on so whatever you do! Do it! Do it now!</h3>
  <p align="center">
    The app can recognize  the Vietnamese Banknotes.
    <br />
    <a href="https://share.streamlit.io/suzynguyenn/banknotes_vnd/main"><strong>The Streamlit app</strong></a>
    <br />
    <br />
    <a href="https://colab.research.google.com/drive/13r-kErvZuHaLDEFalIHPVN4HcfJTcJt0">Jupyter Notebooks</a>
    ·
    <a href="https://world.openfoodfacts.org/data">Dataset</a>
    ·
  </p>
</p>

<img src="https://raw.githubusercontent.com/SuzyNguyenn/Banknotes_VND/main/ezgif.com-gif-maker.gif">

<p align="center">Check out more demo below :)</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li><a href="#dataset">Dataset</a></li>
    <li><a href="#project-description">Project Description</a></li>
    <li><a href="#key-takeaways">Key TakeAways</a></li>
    <li><a href="#future-work">Future Work</a></li>
    <li><a href="#thank-you">Thank You</a></li>
  </ol>
</details>


## DATASET
The dataset used for Banknotes project originates half from [CoderSchools] and half from myself. This data contains >5000 pictures in diverse angles ranging from 1,000 VND to 500,000 VND

## PROJECT DESCRIPTION    
   - [Training Model.ipynb](https://github.com/SuzyNguyenn/Banknotes_VND/blob/main/Training.ipynb)
    
   - [app.py](https://github.com/SuzyNguyenn/Banknotes_VND/blob/main/streamlit_app.py): Streamlit web app

## KEY TAKEAWAYS

- The Deep Learning model can dêtct the Vietnamese banknotes using the available and self-made dataset of Vietnamese banknotes. 
- The deep learning model was trained is Xception with the imagenet weight. Besides, it has been trained and tunned with more epochs. 
- The final accuracy of valuation is 97,79%

## FUTURE WORK

  - Using Error Analysis to add more target dataset to impove model accuacy


## THANK YOU

  Words cannot express my gratitude enough to the people who helped me make this project a success. This project was a part of **CoderSchool 2021 Machine Learning bootcamp** that I took part in and was presented at the weekly project
  
  The bootcamp that lasted 4 months was taught by the dedicated and amazing Instructors (anh Quân, anh Nhân, anh Chinh) and Teaching Assistants (Minh, Nathan, Ngọc) whom I greatly appreciate. It also introduced me to people who have been very supportive throughout the course and that are now my good friends.
  
  Thank you again to all of the wonderful people whom I met at CoderSchool. Wish you all Good luck!
  
 -----------------
 If you like my work, please give this repository a star so I can keep improving and work on more projects :)

[contributors-shield]: https://img.shields.io/github/forks/CHP2108/Banknotes_VND?color=pink&label=Contributors&style=for-the-badge
[contributors-url]: https://github.com/CHP2108/Banknotes_VND/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/CHP2108/Banknotes_VND?style=for-the-badge
[forks-url]: https://github.com/CHP2108/Banknotes_VND/network/members
