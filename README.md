# SpaceX
It is a fully responsive Angular application which shows all spacex launches. This assignment is given by Publicis Sapient.

Features
------------------------------
* User can see list of card of `spacex launch`.
* User can filter launches by selecting custom filters `Launch Year`, `Successful Launch`, `Successful Landing`.
* Fully responsive for `Mobile View`, `Tablet View:`, `Desktop View`
* Deployed on Heroku. (url==> https://space-x-assignment1.herokuapp.com/).


Pre-Requisites
------------------------------

* ``Angular 10``
* ``ES2015``
* ``NPM``
* ``Node``
* ``CSS3``
* ``TypeScript``

**Approach to Build The Project**
1) Firstly create a Base Project of Angular 10 with command "ng new <Project Name>
2) create the CSS and HTML part of the View 
3) Next implement the logic to fetch the data from the API and Integare to DOM
4) Here i have used service mecahnism to fetch the data with HTTP client Module, to make it future scaleable

Steps to Run Project Run Project
------------------------------
* run command ``git clone https://github.com/rahul751996/SpaceX.git``
* ``cd project folder``
* ``run npm install``
* ``run ng build``
* ``run ng serve --open``
* ``open app in browser using url http://localhost:4200``

**Home View showing list of Launches**

![Home Page Desktop](SpaceX\DesktopView.jpg)

![Home Page Mobile](SpaceX\MobileView.jpg)

![Home Page Tablet](SpaceX\TabletView.jpg)


Live Preview https://space-x-assignment1.herokuapp.com/