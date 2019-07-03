# React Assessments

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. Here is a list of pros and cons to using the React library to build your application -- but some of them are false. Remove the false statements from the list:

- React is a modern, efficient answer to complex UI applications
- React is a flexible library that plays the role of V in an MVC framework

 
 #### 2. What are "smart"(logic) and "dumb"(display) components? Explain the difference and also add why we bother to make the distinction between them.
 
 
 //Your Answer
 
    -"Smart"(logic) components are more complicated and hard to test.
    -"Dumb"(display) components are presentational components that present something to the DOM
 
 //Googled Answer
 
    -Dumb Components: This component only responsible to present something to DOM. There will be no logic at all inside this component therefore it is called dumb component.
            Because dumb component only focus on the presentation (UI Component), it is ideally will the most reusable component.
    -Smart Components: Also called container components. Smart component on the other hands keep track of state and concern with how things work.
            Container component still receives data or function via props and can pass it to another smart component or dumb component as props.
            Container component pattern is class-based components and have constructor() functions. We usually initialize state inside the constructor, although you can remove the constructor and still have a state.
 
#### 3. When we use "yarn add ..." in the terminal - what is yarn doing? And what file will always be automatically updated after we add a package with yarn?
 
 
 //Your Answer
 
    -Yarn add is used to download the package for react

 //Googled Answer
 
    -Yarn add installs a package and any packages that it depends on.
    
#### 5. There are three mistakes in this code that would cause it to break our application. Find the mistakes and fix them:

import React, { Component } from 'react';

class Recipes extend Component {
    constructor(props){
        super(props)
        this.state = {
          recipes: [ 
            {name: 'Meatballs'},
            {name: 'Mac & Cheese'} ]
      
        }
      }

      render() {
    
        return (
    
          let recipes = this.state.recipes.map(function(recipe){
            return(
              <li key={recipe.name}>{recipe.name}</li>
            )
          })
        <div>
          <ul>
            {recipes}
          </ul>
         </div>
        );
      }
    }

    export default Recipes;

#### 6. Name three html input types. (NOTE: text is the default type - so it doesn't count in this case)
 
 //Your Answer
 
    -Input type- Submit
    -Input type- Reset
    -Input type- Checkbox
 
 //Googled Answer
     
    -Input type- Submit: defines a button for submitting form data to a form-handler.
            The form-handler is typically a server page with a script for processing input data.
    -Input type- Reset: defines a reset button that will reset all form values to their default values:
    -Input type- Checkbox: Checkboxes let a user select ZERO or MORE options of a limited number of choices.
 
 
 #### 7. How would you explain state to a friend who doesn't know code?
 
 //Your Answer
 
 
    -I would use the example that we used in class. I would say that state is what we can change upriver
     to change the behaviors downriver.

 
 //Googled Answer
    -In the React sense, “state” is an object that represents the parts of the app that can change.
     Each component can maintain its own state, which lives in an object called this.state
 
 #### 8. What is the difference between component state and props? Your answer should include a short explanation of both.
 
 
 //Your Answer
 
 -props get passed to the component and state is managed within the component 
 
 //Googled Answer
 
 -Props: Props are how components talk to each other. 
 -State: State is used so that a component can keep track of information in between any renders that it does. 
   
#### 9. Write a paragraph or so about your experience with building tic-tac-toe. Some topics to start with might be: things you learned about yourself, concepts from React that stood out to you, something about pair programming (if you paired), or the experience of building something in code from scratch.

My group struggled a bit with tic-tac-toe, however, I think in the end that it paid off. We were all able to learn together as a group and figure out React together. It really helped us work on our communication skills since we all had our own individual ways of learning and had to explain it to one another to help in the process of creating our game. In the end,
we all came together and completed a well-functioning game, which was a great feeling of accomplishment. I thought it was a great learning experience for all of us. It was a wake up call that maybe we didn't understand the concepts as much as we thought we did, so we needed to buckle down and come together. 

In the end, we came together and reached our goal. So, I was quite happy.