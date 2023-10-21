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


**5.** Now we can create an <input> to associate our <label> element with.

Set the id of the <input> to "animal-1" and the type to "text". Assign the name to "animal-1". Remember, the name attribute is needed for information from this <input> to be sent with the form during submission.

Speaking of submission, since we want our users to put in some value, add the required attribute to the <input>.

**6.** We’re going to be adding more <label>s and <input>s so we should add some spacing.

Below the <input> element, add a line break using < br >.

With the first input field and working submit button, type some text into the field and submit it! Remember, in order for you to see the new code rendered on the browser, you’re going to need to save your code.

**7.**
Our story has quite a few blanks, so we’re going to need a lot more <label>s and <input>s.

Add another <label> with a for attribute of "animal-2" that renders Another Animal: to the webpage.

Underneath the <label>, create a new <input> with the attributes:

- id and name set to "animal-2".
- type to "text".
- required

Add another < br > for a line break.

**8.** There’s another animal in our story, so let’s add another <label> with a for attribute of "animal-3" that renders One More Animal: to the webpage.

Then, add a new <input> with the attributes:

- id and name set to "animal-3".
- type to "text".
- required
  
Remember to add another < br > for a line break.

**9.** Let’s have our users provide an adjective.

Add another <label> with a for attribute of "adj-1" that renders the text Adjective (ends in -ed): to the webpage.

Then, add a new <input> with the attributes:

- id and name set to "adj-1".
- type to "text".
- required

Add another line break.

**10.** Let’s get a verb.

Create a <label> with has a for attribute set to "verb-1" that renders the text Verb (ends in -ing):.

Follow the <label> with an <input> with the attributes:

- id and name set to "verb-1".
- type to "text".
- required

Also, add a line break.

### Other Inputs

**11.** Great, we have some <input>s set up that accept text, but we can use some <input> with different types in our <form>.

Let’s add a field that will accept a number. First add <label> with a for attribute of "num-1"that renders the text Number: to the webpage.

After the <label> element, add an <input> that has:

- id and name set to "num-1".
- a type attribute of "number".
- a required attribute.
  
Also, add a line break.
