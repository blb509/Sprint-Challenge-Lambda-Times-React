- [ ] What are PropTypes used for? Please describe why it's important to type check our data in JavaScript.

PropTypes are used to make sure that we are passing in the correct type of props into our components. This is important because 
they make it easier to debug your code and make sure nothing is breaking because the wrong types of props are being passed in.

- [ ] Describe a life-cycle event in React?

A life-cycle event in react is a set of three phases. Mounting, Updating, and Unmounting. Mounting is when
your component is first built and initial data it has access to is defined. When updating happens is when state is changed 
and therefore the component is changed as well. Finally unmunting happens when a component is removed from the screen. 

- [ ] Explain the details of a Higher Order Component?

A higher order component is a function that takes in one or multiple components and can return one or multiple components and even
alter them before they are returned.

- [ ] What are three different ways to style components in React? Explain some of the benefits of each.

First way, inline styling. From what I have seen this is a method that is looked down upon and I understand why. The only reason
I could think of to do this is if you were making the most simple page in the world and were to lazy to set up and other 
styling methods. Second, the classic CSS stylesheet. A great way to style since it seperates your CSS from your JSX and some people really
prefer that. Last, styled components. The most recent way to style in react, it is amazing cause it allows you to have your html, css, and javascript all in one page. And, styled components lets you scope the css you make so it wont leak over and affect other components.