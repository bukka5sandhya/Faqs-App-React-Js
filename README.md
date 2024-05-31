In this project, let's build a Faqs App by applying the concepts we have learned till now.

Refer to the image below:

![image](https://github.com/bukka5sandhya/Faqs-App-React-Js/assets/133884532/0d5a4a09-8e0c-4157-bdd1-9e2ef9b1c11b)

https://assets.ccbp.in/frontend/content/react-js/faqs-output-v3.gif

Design Files

Click to view

Extra Small (Size < 576px), Small (Size >= 576px), Medium (Size >= 768px)

Large (Size >= 992px) and Extra Large (Size >= 1200px)

Set Up Instructions

Click to view

Download dependencies by running npm install

Start up the app using npm start

Completion Instructions

Functionality to be added

The app must have the following functionalities

When the plus icon is clicked in a FAQ

The answer to the FAQ should be visible to the user


The plus icon should change to a minus icon

When the minus icon is clicked in a FAQ

The answer to the FAQ should be hidden to the user

The minus icon should change to a plus icon

The Faqs component receives the faqsList as a prop. It consists of a list of faq objects with the following properties in each faq object

Key	Data Type

id	Number

questionText	String

answerText	String

Components Structure

![image](https://github.com/bukka5sandhya/Faqs-App-React-Js/assets/133884532/b0982d15-89da-49c0-a686-cad85d5c0b21)

Implementation Files

Use these files to complete the implementation:

src/components/Faqs/index.js

src/components/Faqs/index.css

src/components/FaqItem/index.js

src/components/FaqItem/index.css

Quick Tips

Click to view

You can use the box-shadow CSS property to apply the box-shadow effect to containers

 box-shadow: 0px 4px 16px 0px #bfbfbf;

 ![image](https://github.com/bukka5sandhya/Faqs-App-React-Js/assets/133884532/05ff62d0-1f8d-4651-b8c2-7ba726f454b0)

You can use the cursor CSS property to specify the mouse cursor to be displayed when pointing over an element

 cursor: pointer;

 ![image](https://github.com/bukka5sandhya/Faqs-App-React-Js/assets/133884532/a1845841-f5b6-485a-ab74-e65b35468448)

You can use the below outline CSS property for buttons and input elements to remove the highlighting when the elements are clicked 

outline:none;

Resources

Image URLs

https://assets.ccbp.in/frontend/react-js/faqs-plus-icon-img.png alt should be plus

https://assets.ccbp.in/frontend/react-js/faqs-minus-icon-img.png alt should be minus

Colors

Hex: #cb8805

Hex: #52606d

Hex: #9aa5b1

Border Colors

Hex: #d7dae6

Hex: #e4e7eb

Background Colors

Hex: #ffffff

Hex: #f1f5f8

Font-families

Roboto

Things to Keep in Mind

All components you implement should go in the src/components directory.

Don't change the component folder names as those are the files being imported into the tests.

Do not remove the pre-filled code

Want to quickly review some of the concepts you’ve been learning? Take a look at the Cheat Sheets.
