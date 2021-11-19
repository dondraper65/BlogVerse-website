# Blogging Website (BlogVerse)
##### Submitted by: Rahul Singh Raghav

## Description
BlogVerse is a front End of a Dynamic blogging website
## Contents
1. [Home Page](#home-page)
2. [Blog List](#blog-list)
3. [Blog Page](#blog-page)

### Code formatting Guidelines Followed
1. The code is formatted correctly, uses the right spacing and indentation, and follows the formatting guidelines laid out in the Google HTML/CSS Style Guide.
2. The HTML, CSS and JS portions of the code are clearly segregated into separate files.
3. The code contains good comments that explain how  complicated portions of the code work
4. HTML/CSS/JS objects, classes or variables have proper and logical names
5. Frequent small commits have been made at all stages of the project.

## Home Page
**Glimpse of Functionality**
1. The Javascript code produces no error.	
2. On clicking the "Sign Up" and "Sign In" buttons, a modal appears on the screen.
3. Website is made responsive
4. There is a tiny cross button towards the top-right, which when clicked, would close this modal.
5. There are be 4 input boxes - Full Name, Username, Password, Confirm Password. They all are “required” fields. They also have placeholders.
6. A “Sign Up” button is inside the modal which has no functionality as this project was intended to be a front end project
7. The title of the modal is "Welcome Back!" and it is placed at the centre of the modal.
8. There isa tiny cross button towards the top-right, which when clicked, would close this modal.
9. There are 2 input boxes -Username & Password. They all are “required” fields. They also have placeholders. A “Sign In” button is inside the modal like On clicking the "Sign Up" portion of “Not a member? Sign Up” it displays the sign-up modal which was created earlier.
10. On clicking the “All Posts” button, it redirects to a new page “bloglist.html”.
11. On clicking Create Post a modal appears which with text input fields for the author to write the Title and content of the blog post. After hitting create post, that data is transferred to a new page post.html using javaScript session storage and a complete blog post is displayed with like and comment functionality.

## Blog List
1. The Javascript code produces no error.
2. The header made in Home page has been successfully imported and looks like the one in home page.
3. The text of the blog towards the right of the author name is not displayed completely (it is partially displayed). In the CSS, the blog text  has a property "overflow:hidden"
4. Above each blog post, there is a trash icon, towards the top-right of each blog, which when clicked would display a deletion modal which does not have functionality.
5. Only two blog posts appear on each row. Helps to make the page responsive
6. The display of these blog post boxes is flexible such that when the display size of the screen is changed, the blog posts adjust their placement automatically. (i.e.at all times, only two blog posts remain on one row even when screen size changes)
7. On clicking the read icon on the blog card, the blog page is opened containing the post with all functionality as described below.

## Blog Page
1. The edit button is present.
2. When clicked, this edit button makes the blog body, blog title and author name editable. When the blog body and title is in the “editable” mode, there should be a cursor which would enable the user to edit/erase/add any text he/she wants in it.
3. While the blog body is in the editable mode, a button called "Save" is displayed in place of the "Edit" button.
4. On clicking the "Save" button, the blog is edited and edited blog post is displayed, the blog body / blog title should no longer be editable.
5. The "Edit" button should reappear after the clicking the "Save" button once the changes to the blog have been made by the user (in place of the "Save" button)
6. Below the body of the blog, a "Like" button is created
7. In the default state, a statement called "Be the first one to like this!" is displayed just below the "Like" button.
8. On liking the blog for the first time, this statement is updated to "1 person likes this
9. After liking the blog post for the first time, the "Like" button morphes into a button "Liked!"
10. Subsequently, whenever the "Like" button is clicked, the number of people who have liked this get incremented and correspondingly, the statement below the "Like" button changes. As an example, on clicking the "Like" button for the 2nd time, the statement must get updated to "2 people have liked this!", for the third time, it should get updated to "3 people have liked this!" and so on.
11. Below the "Like" button, there is an input box with a placeholder text "Leave a comment...".
12. Below this box,  a red coloured "Comment" button has been created which when clicked, displays the typed comment in the “All Comments” section along with the time stamp of when the comment was posted.
13. Every new comment must be added to the top of the "All Comments" section. Meaning that the latest comment must be added to the top.
