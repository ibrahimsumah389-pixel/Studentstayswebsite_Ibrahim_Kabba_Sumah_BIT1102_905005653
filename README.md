# StudentStay

StudentStay is a student accommodation website for Freetown, Sierra Leone. It helps students search, compare and contact providers of safe, affordable rooms near their university, and gives property owners a simple way to list their rooms.

The site is built with **HTML and CSS only**. It uses no JavaScript.




## Folder structure

studentstay/
├── index.html               Home page
├── accommodation.html       Find Accommodation (search and results)
├── listing.html             Room details
├── compare.html             Compare saved places
├── about.html               About StudentStay
├── services.html            Our services and FAQs
├── contact.html             Contact details and contact form
├── verify.html              Contact step 2: phone code
├── thank-you.html           Message sent confirmation
├── list-property.html       Register / Log in for property owners
├── add-listing.html         Add your listing form
├── thank-you-listing.html   Listing submitted confirmation
├── privacy.html             Privacy & terms
├── README.md                This file
├── css/
│   └── style.css            One shared stylesheet for every page
└── images/                  Photos used on the site


## Pages

| Page | What it does |

| Home | Banner with call to action, search form, featured accommodation and a "Have a room to rent?" section |
| Find Accommodation | Filters for location, price, room type and facilities, sort options and a list of 5 places |
| Room details | Photos, key facts, facilities, house rules and a provider contact box |
| Compare saved | Table comparing price, location, room type and facilities of three places |
| About | Who StudentStay is, how it works in three steps and StudentStay in numbers |
| Services | Four services for students, a section for property owners and frequently asked questions |
| Contact | Email, phone, location, office hours and a contact form (step 1 of 2) |
| List your property | Three-step process and Register / Log in tabs for owners |
| Add your listing | Form for property details, facilities, description and photos |
| Privacy & terms | How information is used and the rules for using the site |


## Navigation

- **Top menu (every page):** Home, Find Accommodation, About, Services, Contact, and a **List Property** button.
- **Student path:** Home search → Find Accommodation → Room details → Compare / Contact provider.
- **Owner path:** List Property → Register or Log in → Add your listing → Listing submitted.
- **Footer (every page):** Home, About, Services, Contact and Privacy & terms.


## Features built without JavaScript

| Feature | How it works |
|---|---|
| Mobile menu | A hidden checkbox and the :checked selector open and close the menu on small screens |
| Register / Log in tabs | Radio buttons and :checked show one form at a time |
| Save button on results | A checkbox switches the button between "Save" and "Saved" |
| Facility filters | Checkboxes styled as tags that change colour when selected |
| FAQs | The HTML <details> and <summary> elements open and close each answer |
| Form validation | required, type="email", pattern and minlength check the input, and the :user-invalid selector shows an error message under the field |
| Search forms | Use method="get" to send the chosen filters to the results page |


## Responsive design

The layout uses CSS Grid, Flexbox and media queries, so it adapts to every screen size:

- **Desktop (above 1060px):** full menu and multi-column layouts.
- **Tablet (600px–1060px):** menu becomes a button, and grids drop to two columns.
- **Phone (below 600px):** single-column layout, full-width buttons and smaller headings.

## Design

| Item | Value |
|---|---|
| Font | Inter (Google Fonts) |
| Navy (text, headings, List Property button) | #13243D |
| Cyan (buttons, accents, call-to-action strip) | #0FDCD3 |
| Light grey-blue (banner and page backgrounds) | #E1E7F0 / #EDF1F8 |
| Slate (body text) | #56637A |

All colours and sizes are stored as CSS variables at the top of css/style.css, so they can be changed in one place.

## Accessibility

- A "Skip to main content" link for keyboard users.
- Every image has descriptive `alt` text.
- Every form field has a visible label and a clear error message.
- A visible focus outline shows which element is selected when using the keyboard.
- Animations are turned off for users who choose reduced motion in their device settings.


## Limitations

This is a front-end prototype. Because it has no JavaScript and no server:

- Forms check what users type, but messages, accounts and listings are not actually sent or saved.
- No text message with a code is sent on the Contact page.
- Saved places do not carry over to the Compare page, which shows an example comparison.
- Search filters do not change the results list.

These features would need a back end (for example PHP with a MySQL database) in a future version.


## Contact

- Email: immisumah01@gmail.com
- Phone: +232 33 982076
- Location: Freetown, Sierra Leone

&copy; 2026 StudentStay
