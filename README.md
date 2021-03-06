# Odyssey

![license](https://img.shields.io/badge/License-MIT-blue.svg)

**version 1.0.0**

[For deployed version, click me](https://team-zeus.herokuapp.com/)

<br>

  ## Table of Contents

  
* [Description](#description)
  
* [Built With](#builtwith) 
  
* [Contributors](#contributors) 
  
* [License](#license)
  
* [Questions](#questions)

  
<hr>

  ## Description 

  Odyssey is a scrapbooking travel app that allows the user to create country-specific travelogues filled with pictures and notes. The app utilizes the MVC design pattern, and is built with Node.js, Handlebars.js, and Sequelize. It is deployed to Heroku with a jawsDB database.

  When the user signs up, they are sent an email notification from Odyssey. The user is then able to add a destination country. The searched country has a 'details' modal showing country data (capital city, continent/region, currency, flag), which pulls data using REST Countries API. When the user hits the 'log' button, they are taken to a travelogue where they can log notes about a journey, and upload pictures to the page using Cloudinary with a Slick carousel. The travelogues for each country are saved to a database so the user may return at any time to create or update their travelogues.

  <hr>

![image of Odyssey's landing page](https://raw.githubusercontent.com/joeybrown-ctrl/Odyssey/main/public/images/indexPage.png)

  <hr>

  ### User Story 

  ```
  AS a traveler,
  WHEN I enter a destination country,
  THEN I am showed country-specific information and can create a personal travelogue for that destination by uploading photos and logging notes.
  ```

  ### Acceptance Criteria

  ```
  GIVEN a scrapbooking travel app,
  WHEN I sign up I am sent an email notification.
  WHEN I log in and enter a country name,
  THEN I can click the 'details' button and find country-specific information (capital city, continent/region, currency, flag).
  WHEN I click the 'log' button,
  THEN I can create a country-specific travelogue by uploading photos and logging notes.
  ```

<br>

  ## Built With

* [SendGrid](https://sendgrid.com)
* [REST Countries](https://restcountries.eu/)
* [Cloudinary](https://cloudinary.com/)
* [Slick](https://kenwheeler.github.io/slick/)
* [Passport](http://www.passportjs.org/packages/passport-npm/)
* [Sequelize](https://sequelize.org/master/index.html)
* [ES Lint](https://eslint.org/)
* [Travis](https://travis-ci.org/)
* [Node.js](https://nodejs.org/en/about/)
* [Visual Studio Code](https://code.visualstudio.com/)
* [Bootstrap](https://getbootstrap.com/)
* [jQuery](https://jquery.com/)
* [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [HTML 5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
* [Markdown](https://guides.github.com/features/mastering-markdown/)

<br>

  ## Contributors 

  ### Team Zeus:

* [Meshal Alotaibi](https://github.com/MeshalS)
* [Saida Arevalo](https://github.com/saida179)
* [Joey Brown](https://github.com/joeybrown-ctrl)
* [Luis Diaz](https://github.com/luis26308)
* [Andrew Hoff](https://github.com/alhoffiq)

<br>

  ## Questions 
  
* [Send us an email](mailto:odyssey.travelogue@gmail.com)
  
* [Reach out on Github](https://github.com/joeybrown-ctrl)

<hr>

  ## Licence 
MIT License

Copyright (c) 2020 github.com/joeybrown-ctrl

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.