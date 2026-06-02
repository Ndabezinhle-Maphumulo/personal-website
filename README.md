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

## Future Enhancements

The next planned enhancements for the website are:

* Add an RSVP button
* Add an RSVP form
* Capture guest information:

  * Name
  * Surname
  * Attendance (Yes/No)
  * Number of guests
* Display a thank-you message after submission

For now, no data will be stored. The focus is on learning Git, branching strategies, HTML, and CSS.
