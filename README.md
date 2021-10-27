# Keeper-App
Duplicate of Google Keep app

## Table of contents

- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## My process

### Built with

- HTML5
- CSS3
- React
- React Hooks
- Material UI
- Yarn

### What I learned

This was the final project for the React module in my Full Stack Engineer course. This is also the largest React project I've worked on. I was able to use the useState hook to for the individual notes and the note creation area. I also learned and used the .map(), .filter(), and .array() functions in to order and layout the notes. And lastly, I learned how to integrate Material UI into my projects to add dimension and movement.

Code written in this project that I want to highlight:

```JSX
<Zoom in={isExpanded}>
          <input
            name="title"
            onChange={handleChange}
            value={note.title}
            placeholder="Title"
            style={!isExpanded && { display: "none" }}
          />
</Zoom>
```
The Zoom component is taken from Material UI and acts as an animation feature when the Title input section is clicked. This animation expands to show the Note Creation area and a small icon pops up that allows the user to add their note.

```JSX
<textarea
          onClick={handleClick}
          name="content"
          onChange={handleChange}
          value={note.content}
          placeholder="Take a note..."
          rows={isExpanded ? 3 : 1}
        />
```
This code for the content also gets expanded to 3 rows when the Title section is activated, along with managing functions like handleClick() and handleChange(), which adds the note content into an array to be viewed by the user once they click the plus button.

### Continued development

React is a very fun way to customize the look and feel of a website, and Material UI makes that process even easier. I wish to continue to learn more about React and the different ways it can be utilized, as well as becoming better associated with the inner working od Material UI and how I can use it in different aspects as well.

## Author

- Website - [Elyse Chambers](https://www.diaryofelyse.com)
- Frontend Mentor - [Elyseeloo](https://www.frontendmentor.io/profile/Elyseeloo)
- Twitter - [@Elyseeloo\_](https://www.twitter.com/elyseeloo_)
