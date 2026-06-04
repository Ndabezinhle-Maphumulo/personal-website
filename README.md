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

## Let now create a Thank you page after RSVP

