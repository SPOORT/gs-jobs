# Coding Exercise

You've been asked to create a simple MVC framework from the scratch following all MVC (https://en.wikipedia.org/wiki/Model–view–controller) pattern standards.
You should have clearly divided controllers, models and views. Also, there should be nice routing pattern included,
so it's easy to build SEO friendly routes (that will include usage of .htaccess file(s) to achieve needed behavior).

### So, as end result, there should be website with 3 pages: (on http://localhost)

#### ``` GET / ```
  * Content is not relevant (can be empty)

#### ``` GET /contact-us ```
  * Page should have contact form with fields: name, phone number, textarea, file upload
  * After submitting form, data should be stored in DB (there should be SQL file which we can run to build initial DB structure) and file should be store in a root of the project

#### ``` GET /about-us ```
  * Content is not relevant (can be empty)
   
- Language in which it should be developed is PHP!
- Have in mind you should prevent any kind of form/DB injection or cross-side scripting (XSS)
- Routing should be separate file, so it's possible easily to add more routes, e.g. if we would like to add new route /jobs, by adding route and needed controller/model/view we could extend framework
- Keep your code clean and nicely organized
- Commenting code is always welcome :)
- Try always to fully complete the test before sending it in ;)

### How should I apply for this? 

Easy, just do the test, add it on your own GitHub repo and send us a link to an email on: tech@gospoort.com

