# fabula

FABULA & HEALING Center

Fabula Yoga Center, offers a wide variety of yoga types, classes starts early in the morning and ends late in the afternoon. 
The Center offers flavour water, yoga material, high certified teachers at a very reasonable price by month.

UX
This website is for any aged person who is interested in yoga practise. Because is an specialised yoga center they focus on different types of practise for everyone. 
They offer the first class for free, so we want to focus on that since is the pathway to get the client once they try the class.

Our Persona is Magdalena, she is 38 lives in Marrakech and is a French and Spanish teacher at the local school. 
Laura likes doing yoga in specialized centers, she’d like to know what kind of classes do they have and what are schedules, prices and location of the Yoga Center and contact them to start as soon as possible.

We are going to implement the information by priorities:

1. FIRST SECTION / HEADER: We want to show the offer - First Class for free
2. SECOND SECTION / CLASSES: We want to show the types and levels of yoga offered - We will link to Wikipedia for the user read further
3. THIRD SECTION / CALENDAR: We want to show the calendar for the week so the user can already know if they can fit or not in the center.
4. We want to show the prices, divided in 3 types depending on the number of classes you take a week.
5. We want to show an overview of the installations and the main features they offer.
6. We want to share three reviews from Fabula center clients. 
7. We want to share location and a short book form for any inquiry apart from the book online.

There will be two types of contact:
- BOOK ONLINE
- CONTACT US


Features

1. FIRST SECTION / HEADER: Book Online Button - Book Online Page where the user will have to fill in with:
    - Name & Surname
    - email
    - phone number
    - type of class
    - day preferred
    - time preferred
    - comments

    We will write a note: "You'll receive an email with your class confirmation soon"

2. SECOND SECTION / CLASSES: Classes Cards with Wikipedia link to learn further. Book Online button at the bottom of the section.

3. THIRD SECTION / CALENDAR: The idea is to show the full calendar in one overview, for that I experimented the following process:

The Calendar was going to be an image responsive, then I thought of doing a tab collapse in phone and uncollapsed in big screen, 
then I thought it would be ver boring to open tab per tab in the phone to see the whole programme of the Center. 
So I decided of doing a responsive table with bootstrap "table-responsive" that included a horizontal scrolling bar.
That is the reason why the design doesn't fit with the prototype, wasn't able to set up columns for the borders so the table is set up in row, I did some research to 
make the table in columns instead of rows but couldn't make it and was taking too long and had to continue with the rest at that point.



In this section, you should go over the different parts of your project, and describe each in a sentence or so.

Existing Features
Feature 1 - allows users X to achieve Y, by having them fill out Z
...
For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

Features Left to Implement
Another feature idea
Technologies Used
In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

JQuery
The project uses JQuery to simplify DOM manipulation.
Testing
In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

Contact form:
Go to the "Contact Us" page
Try to submit the empty form and verify that an error message about the required fields appears
Try to submit the form with an invalid email address and verify that a relevant error message appears
Try to submit the form with all inputs valid and verify that a success message appears.
In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

Deployment
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

Different values for environment variables (Heroku Config Vars)?
Different configuration files?
Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.

Credits
Content
The text for section Y was copied from the Wikipedia article Z
Media
The photos used in this site were obtained from ...
Acknowledgements
I received inspiration for this project from X