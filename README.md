# SOCETechnicalTest

## Introduction
Install node.js

npm install json-server
>Use json-server db.json to quickly build a simple Rest API against db.json

npm install http-server
>Quickly set up an HTTP server using http-server in the Test/ and Back/ folders respectively.

Use http://127.0.0.1:8080 and http://127.0.0.1:8081 as the front and back end on the browser, the password of the back end can refer to the json file inside the Back/ folder, they are read and written with different permissions by the established API-db.json.

Because only Apache and Phpmyadmin have been learned, so in this test in order to be able to quickly establish an environment that can complete this test so the use of json-server.

In order to let users see the changes of the table without refreshing the web page, I have tried several ways for this section, but most of them are for the processing of strings, and finally decided to use array to store each column, which will not only change the DB when pressing the button, but also the local array will change, so you can see the effect without reloading.

In this test, Jquery is used to make the whole operation more smooth and concise.
The data entered by the user is handled by charcode, Id and Price can only be entered as numbers and Name can only be entered as text.
The CSS parts have also been handled, such as the back-end login interface.
