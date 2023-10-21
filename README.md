# Form Story

Forms are great for collecting information on users, like job applications or insightful surveys. However, we can also stretch our creative muscles and have a little fun with forms. For this project, we’ll use our knowledge of the HTML <form> and grab user input to put a spin on a classic story!

The logic for parsing and inserting of user inputs is already taken care of in main.js using JavaScript . We’ve also added some styling to the page in style.css. 

What you have to do is now make a <form> capable of collecting the correct information so that the newly crafted story makes sense!

# Tasks

### Adding The Form

**1.** We’ll be collecting information from our users using a <form> so, first, we have to add a <form> under the < hr > element inside the <body> of index.html.

**2.** Assign the <form> an action of "story.html" and a method of "GET".

We’ll be sending information from our form to story.html using a GET request.

**3.** In the <form>, create a submit button by adding an <input> with a type of "submit". Assign the value a value of "Form My Story!". Save your code to see the button rendered.

This might seem counterintuitive, but by creating this submit button and submitting the form as you add more code, you can see how the final result of the story evolves and debug in smaller chunks. Check the hint for more debugging tips!

### Adding Text Input
**4.** Now we can populate our <form> with <input> elements that allow users to type in their responses. We’ll also want to have associated <label>s with these <input> elements so users know what they’re filling in.

Add a <label> element and assign the for attribute a value of "animal-1". Have the <label> render the text Animal: on the webpage.

Write your code so that the submit button always shows up at the bottom of the <form>. As you add more code, the submit button should be kept at the bottom.

Write your code so that the submit button a