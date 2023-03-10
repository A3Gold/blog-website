# Introduction

A website that allows users to create, manage, and view blog posts on their own blog website.

## Walkthrough

**Home page of site:**

![image](https://user-images.githubusercontent.com/105163708/211862951-51efaf2f-97a0-4abf-bd2e-a427651b1175.png)

**Users can click on a blog post to view that specific post:**

![image](https://user-images.githubusercontent.com/105163708/211863169-967916f8-4903-4c40-8c54-765c74530d3e.png)

**Blog posts can be deleted using the "delete" button:**

![image](https://user-images.githubusercontent.com/105163708/211863265-07e62679-7d8e-4d07-a227-8dabe53c4c52.png)

**About page:**

![image](https://user-images.githubusercontent.com/105163708/211863406-f75225db-a216-48a8-b396-6cece8d9c6e6.png)

**Page where users can add a new blog post:**

![image](https://user-images.githubusercontent.com/105163708/211863497-d77d27f4-051c-48df-8854-d2eafe5dabbe.png)


## Technical Details

The backend uses Node.js and Express.js to handle and route HTTP requests. Blog posts created are stored in a connected MongoDB database using Mongoose Object Data Modelling. The Node.js backend was developed to save posts created on the frontend to the database when submitted and remove posts when deleted. The frontend design uses HTML, generated by EJS files, and CSS to create a pleasant user interface.
