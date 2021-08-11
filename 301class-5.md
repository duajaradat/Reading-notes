## **React Docs - thinking in React**

**1-How would you break a mock into a component heirarchy?**

breaking amock into a component consists of drawing boxes around each components .

**2-What is the single responsibility principle and how does it apply to components?**

The single repo principle says the each component should only do one thing. if component became big, it should split to a another components.

**3-What does it mean to build a ‘static’ version of your application?**

 it means that the app doesn't change . inreact the state not including any state in the static mode.


**4-Once you have a static application, what do you need to add?**
add state to the mix.


**5-What are the three questions you can ask to determine if something is state?**

1-is it passing function using props? if yes then it's not state 

2-does it change overtime??
if yes then it's not state 

3-if it can be based on state or props in other component? if yes then it's not state 


**6-How can you identify where state needs to live?**

identify components that need a certain piece of data. if multiple components need that data , then if those components share parent element , then the state should be kept in their shared parent .

[Thinking in React](https://reactjs.org/docs/thinking-in-react.html)

#### Things I want to know more about 

how we can handle multiple web pages?

