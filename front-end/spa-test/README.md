# Single Page Application

## Customer Registration
Build a [Single Page Application](https://en.wikipedia.org/wiki/Single-page_application) (SPA) customer registration App using JavaScript/Typescript, HTML and CSS.

### Functionality
1. There should be one view where all the customers are listed.
1. There should be another view to add, delete and edit customers.
1. The data should be persisted (on the client), and loaded again when the application starts.
1. Add fitting validation to the different input fields.

### Form Fields
* First name (input, required, minLenght=5, maxLenght=20)
* Last name (input, required, minLenght=5, maxLenght=20)
* Email (input[type=text], required, valid email)
* Country (dropdown, required) - use the [country-list](https://www.npmjs.com/package/country-list) module to populate the list

### Other Requirements
Please keep the following in mind

* Preferably, use Angular as a Framework, but feel free to depend on any other frameworks/libraries if you prefer
* If you feel it's suitable, use a state managment library to handle the customers information on the client
* All the views should have a minimum of responsiveness
* Even though this is a small project, **structure and architecture should mimic a large project**.
* The code should obviously follow best practises (DRY, maintainable, testable, commenting, etc).
* We want the code you submit to be written by you, so don’t use skelletons/generators for certain stack and functionality (just use the appropiate cli in case you want a basic app skelleton)
* Make sure the application works on Node 10.x, NPM 6.x and in latest Chrome and Firefox.

We don't only want to see your code style but also your technical assesment of the problem, from architectural decisions until technology choices. We want to see what you are capable having the freedom to approach a challengue, so you should be able to explain and argue all the decisions you have taken

Note, this is where you get to shine — *show us what you’ve got!*