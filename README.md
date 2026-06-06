# personal-website
This is my first attempt building a website.

# First Commit - File Creation.

## Step 1: Create a GitHub Repository

Created a GitHub repository named:

* personal-website

## Step 2: Clone the Repository

Opened Command Prompt and cloned the repository to my local machine using:

"C:\Program Files\Git\cmd\git.exe" clone https://github.com/Ndabezinhle-Maphumulo/personal-website.git

## Step 3: Navigate to the Project Folder

Changed into the project directory using:

cd personal-website

This allowed me to work inside the repository folder.

## Step 4: Open the Project in Visual Studio Code

Opened the repository in Visual Studio Code using:

code .

Created the following project files:

* index.html
* portfolio.css
* graduation-photo.jpg
* README.md

## Step 5: Commit the files.
I created my first commit by running:

"C:\Program Files\Git\cmd\git.exe" commit -m "Create project structure and add website assets"

## Step 6: Push the Branch to GitHub

I pushed my branch to GitHub by running:

"C:\Program Files\Git\cmd\git.exe" push -u origin dev/files-creation

## Step 7: Create a Pull Request and merge with the main branch.

After pushing the branch, I created a Pull Request to compare the changes and merged into the main branch, after confirming the changes.

## Step 8: I then create the content of the website. Modified the .html file.
* First I create a new branch by running: 

"C:\Program Files\Git\cmd\git.exe" checkout -b dev/invitation-page

This branch should only create the invitation page:

* Graduation photo
* Welcome message
* Graduation details
* Appreciation message

No RSVP form yet.

## Step 9: Commit the changes

I committed my changes by running:

"C:\Program Files\Git\cmd\git.exe" add .

Then to commit:

"C:\Program Files\Git\cmd\git.exe" commit -m "Add graduation invitation page content"

## Step 10: Push

I then push by running:

"C:\Program Files\Git\cmd\git.exe" push -u origin dev/invitation-page 

## Let now stle our website on the .css file

The idea of this website is to look more like a graduation invitation by:

* Centering all content.
* Reducing the image size.
* Adding spacing between sections.
* Using a cleaner font.
* Adding a subtle background color.
* Styling the event details so they stand out.

But first, let make sure we're on main, by running:

"C:\Program Files\Git\cmd\git.exe" checkout main

## Step 1
Pull the latest changes, by running:

"C:\Program Files\Git\cmd\git.exe" pull origin main

Then create the styling branch:

"C:\Program Files\Git\cmd\git.exe" checkout -b dev/styling

# Step 2: Write a .css file
I wrote the css file that achieves my objectives.

## Step 3: Commit the Styling Changes

After updating the `portfolio.css` file, I saved my changes and prepared them for commit by running:

"C:\Program Files\Git\cmd\git.exe" add .

I then created a commit:

"C:\Program Files\Git\cmd\git.exe" commit -m "Add styling and improve invitation page layout"

## Step 4: Push the Styling Branch

I pushed the styling branch to GitHub by running:

"C:\Program Files\Git\cmd\git.exe" push -u origin dev/styling

## Step 5: Create a Pull Request and Merge with Main

After pushing the styling branch, I created a Pull Request to review the styling changes.

The styling changes included:

* Centering the page content
* Reducing the image size
* Adding a background colour
* Improving text spacing
* Styling headings
* Adding rounded corners to the graduation photo

After reviewing the changes, I merged the Pull Request into the main branch.

## I then create a button to RSVP.
## Step 1: Checkout main
Run: "C:\Program Files\Git\cmd\git.exe" checkout main

## Step 2: Pull origin main
Run: "C:\Program Files\Git\cmd\git.exe" pull origin main

## Step 3: Create a new branch for a button
Run: "C:\Program Files\Git\cmd\git.exe" checkout -b dev/rsvp-button

## Step 4: I updated the index.html by adding an RSVP button below the event details section:
Added the line: <button>RSVP</button>

## Step 5: I then updated the .css file to style the button.

So what I did was: 

* Adding an RSVP button

## Step 6: I then add the changes and commit them.
I ran: "C:\Program Files\Git\cmd\git.exe" add .
Then: "C:\Program Files\Git\cmd\git.exe" commit -m "Add RSVP button to invitation page"

## Step 7: I pushed the changes
I ran: "C:\Program Files\Git\cmd\git.exe" push -u origin dev/rsvp-button

## Add an RSVP Form

The next enhancement is to add an RSVP form to the graduation invitation website.

The form captures the following guest information:

* Name
* Surname
* Attendance (Yes/No)
* Number of Guests

For now, no data will be stored. The focus is on learning Git, branching strategies, HTML, CSS, and website navigation.

## Step 1: Switch to the Main Branch

I first switched to the main branch by running:

"C:\Program Files\Git\cmd\git.exe" checkout main

I then pulled the latest changes from GitHub by running:

"C:\Program Files\Git\cmd\git.exe" pull origin main

## Step 2: Create a New Branch

I created a new branch for this feature by running:

"C:\Program Files\Git\cmd\git.exe" checkout -b dev/rsvp-form

This branch is responsible for creating the RSVP form feature.

## Step 3: Create the RSVP Page

I created a new file named:

* rsvp.html

This page contains the RSVP form and allows guests to enter their information.

The project structure now contains:

* index.html
* rsvp.html
* portfolio.css
* graduation-photo.jpg
* README.md

## Step 4: Connect the RSVP Button

I updated the RSVP button on the invitation page to navigate to the RSVP page.

I inserted:

<a href="rsvp.html">
    <button>RSVP</button>
</a>

This allows visitors to move from the invitation page to the RSVP form page.

## Step 5: Update the Website Files

I updated the following files:

* index.html
* rsvp.html
* portfolio.css

The HTML files were updated to separate the invitation page from the RSVP page, while the CSS file was updated to style the RSVP form and improve the user experience.

## What I Learned

This enhancement introduced the concept of website navigation by linking multiple pages together.

The website now consists of:

* An invitation page (index.html)
* An RSVP page (rsvp.html)

This structure is more realistic and easier to maintain as new features are added in future branches.

## Step 6: I then committed the changes
By running: "C:\Program Files\Git\cmd\git.exe" add .

Then commited the changes by running: "C:\Program Files\Git\cmd\git.exe" commit -m "Move RSVP form to dedicated page"

Then push: "C:\Program Files\Git\cmd\git.exe" push -u origin dev/rsvp-form

## Let now create a Thank You Page after RSVP

The next enhancement is to improve the RSVP experience by displaying a confirmation page after a guest submits the RSVP form.

The purpose of this page is to thank guests for responding and confirm that their RSVP has been received.

For now, no information will be stored. The focus remains on learning website navigation, HTML, CSS, Git branching, commits, and Pull Requests.

## Step 1: Switch to the Main Branch

I first switched to the main branch by running:

"C:\Program Files\Git\cmd\git.exe" checkout main

I then pulled the latest changes from GitHub by running:

"C:\Program Files\Git\cmd\git.exe" pull origin main

## Step 2: Create a New Branch

I created a new branch for this feature by running:

"C:\Program Files\Git\cmd\git.exe" checkout -b dev/rsvp-confirmation

This branch is responsible for creating the RSVP confirmation page.

## Step 3: Create the Thank You Page

I created a new file named:

* thank-you.html

This page displays a confirmation message after a guest submits the RSVP form.

The message thanks guests for their response and confirms that we look forward to celebrating with them.

## Step 4: Update the RSVP Form

I updated the RSVP form in `rsvp.html` so that when the Submit RSVP button is clicked, the user is taken to the confirmation page.

I updated the form tag to:

```html
<form action="thank-you.html">
```

This creates a navigation flow between pages.

## Step 5: Test the Website Navigation

I tested the website by following the full RSVP process

## Step 6: Update the Website Files

I updated the following files:

* rsvp.html
* thank-you.html
* portfolio.css

The RSVP page was updated to redirect users to the confirmation page, while the new thank-you page was created to complete the RSVP journey.


## Step 7: Commit the Changes

I committed my changes by running:

"C:\Program Files\Git\cmd\git.exe" add .

I then created a commit by running:

"C:\Program Files\Git\cmd\git.exe" commit -m "Add RSVP confirmation page"

## Step 8: Push the Branch

I pushed the branch to GitHub by running:

"C:\Program Files\Git\cmd\git.exe" push -u origin dev/rsvp-confirmation

## Step 9: Create a Pull Request and Merge with Main

After pushing the branch, I created a Pull Request to review the confirmation page changes.

The changes included:

* Creating a thank-you page
* Linking the RSVP form to the confirmation page
* Completing the RSVP user journey

After reviewing the changes, I merged the Pull Request into the main branch.

# Connect the RSVP Form to Google Sheets

The next enhancement is to collect RSVP responses automatically and store them in a Google Sheet.

This allows guests to submit their RSVP information through the website while the data is collected in the background for event planning purposes.

The following information is collected:

* Name
* Surname
* Attendance (Yes/No)
* Number of Guests

## Step 1: Switch to the Main Branch

I first switched to the main branch by running:

"C:\Program Files\Git\cmd\git.exe" checkout main

I then pulled the latest changes from GitHub by running:

"C:\Program Files\Git\cmd\git.exe" pull origin main

## Step 2: Create a New Branch

I created a new branch for this feature by running:

"C:\Program Files\Git\cmd\git.exe" checkout -b dev/data-collection

This branch is responsible for collecting RSVP responses and storing them in Google Sheets.

## Step 3: Create a Google Sheet

I created a Google Sheet named:

* Graduation RSVP Responses

The spreadsheet contains the following columns:

* Name
* Surname
* Attending
* Guests

## Step 4: Create a Google Apps Script

Using Google Apps Script, I created a web application that receives form submissions and stores them in the spreadsheet.

The script captures:

* Name
* Surname
* Attendance
* Number of Guests

for every RSVP submission.

## Step 5: Deploy the Apps Script

I deployed the Apps Script as a Web App.

The deployment settings were:

* Execute as: Me
* Who has access: Anyone

This generated a Web App URL that can receive form submissions from the website.

## Step 6: Connect the Website Form

I updated:

* rsvp.html

The RSVP form now sends data directly to the Google Apps Script using JavaScript and the Fetch API.

The data is stored automatically in the Google Sheet when a guest submits the form.

## Step 7: Redirect Users After Submission

After the RSVP is successfully submitted:

* Guests selecting "Yes" are redirected to thank-you.html
* Guests selecting "No" are redirected to sorry-you-cant-make-it.html

This provides a personalised response based on the guest's attendance selection.

## What I Learned

This enhancement introduced:

* Google Sheets integration
* Google Apps Script
* JavaScript Fetch API
* Form submission handling
* Data collection from a website
* Background processing of user submissions

The website can now collect RSVP responses automatically while keeping the experience simple for guests.

## Step 8: Commit the Changes

I added the changes by running:

"C:\Program Files\Git\cmd\git.exe" add .

I then committed the changes by running:

"C:\Program Files\Git\cmd\git.exe" commit -m "Connect RSVP form to Google Sheets"

## Step 9: Push the Branch

I pushed the branch to GitHub by running:

"C:\Program Files\Git\cmd\git.exe" push -u origin dev/data-collection