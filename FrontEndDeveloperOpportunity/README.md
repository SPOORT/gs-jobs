# Coding Exercise

You've been asked to create a responsive web page using pure HTML/CSS/JS. For simplicity, you're free to use any JS library/framework you prefer jQuery/AngularJS/etc.
Page itself should have all functionality presented in mockup (mockup.jpg), such as: dynamically loading content and filtering them using filter, slider activity,
listing more details about users when clicking on "VIEW DETAILS".

It's important that this page is fully responsive following mobile first strategy, so we there are nicely added breaking points for different devices.

Data are provided via external source JSON file (source.json) which should ge fetched via Ajax request. Since it's static file, it's expected that filtering of the
data is done on client side.
If there are some data missing in the external source JSON file, candidate is encouraged to add them, e.g. if discipline is missing, etc.

### /get-providers

#### ``` GET /get-providers ```
  * Will fetch full list of providers from the external source
  * Returns 200 if a list of providers are retrieved

#### ``` GET /get-providers?location=:location ```
  * Will fetch still full list of the providers, BUT we should have filter working on client side (since it's not possible to do it on external side, without actual server :)
  * Returns 200 if a list of providers are retrieved

#### ``` GET /get-providers?type=:type ```
  * Will fetch still full list of the providers, BUT we should have filter working on client side (since it's not possible to do it on external side, without actual server :)
  * Returns 200 if a list of providers are retrieved

#### ``` GET /get-providers?location=:location&type=:type ```
  * Will fetch still full list of the providers, BUT we should have filter working on client side (since it's not possible to do it on external side, without actual server :)
  * Returns 200 if a list of providers are retrieved

What a source.json looks like:

   ```javascript
   {
       "discipline": [
         "Crossfit",
         "Yoga",
         "Fitness"
       ],
       "picture": "http://placehold.it/100x100?text=Spoort",
       "about": "Ex Lorem culpa ea ut incididunt amet exercitation. Ipsum cillum aute irure ad non tempor ad occaecat excepteur sit qui. Incididunt nisi ut tempor excepteur laborum elit. Occaecat qui consectetur magna do dolor irure adipisicing pariatur. Ut proident voluptate nostrud officia ipsum adipisicing ea amet ea ullamco. Officia nulla duis proident duis enim nisi deserunt duis aliqua enim do.\r\n",
       "guid": "32aa64f0-1a83-4b9b-8717-46abf9b2fc51",
       "name": "Sherry Kinney",
       "gender": "female",
       "age": 27,
       "registered": "2015-08-08T11:52:28 -02:00",
       "longitude": 0.98487899999999995,
       "email": "sherrykinney@zoarere.com",
       "phone": "+1 (839) 449-2180",
       "address": "170 Clifton Place, Bradenville, Virginia, 3974",
       "latitude": -12.324331000000001,
       "balance": "$3,517.35",
       "favoriteDiscipline": "Fitness",
       "company": "ZOARERE",
       "isActive": true
   }
   ```
   
- Try to make it as much as possible to follow the style guideline provided in the mockup.jpg
- You're more then welcome to pick font-size/font-family that looks as much as possible to one provided in mockup.jpg
- Keep your code clean and nicely organized
- Commenting code is always welcome :)
- Keep in mind that it must be responsive
- Try always to fully complete the test before sending it in ;)
