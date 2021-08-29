# Component  

## A component is a modular, portable, replaceable, and reusable set of well-defined functionality that encapsulates its implementation and exporting it as a higher-level interface.

## A component is a software object, intended to interact with other components, encapsulating certain functionality or a set of functionalities.

***Component-based architecture focuses on the decomposition of the design into individual functional or logical components that represent well-defined communication interfaces containing methods, events, and properties. It provides a higher level of abstraction and divides the problem into sub-problems, each associated with component partitions.***

# Views of a Component

* Object-oriented view

* Conventional view

* Process-related view 

![](https://www.tutorialspoint.com/software_architecture_design/images/principles_of_component_based_design.jpg)

# REACT & PROPS

React has a different approach to data flow & manipulation than other frameworks
* React is a component-based library which divides the UI into little reusable pieces

* the way to pass data between components is by using props. 
* properties is used for passing data from one component to another.

* uni-directional flow

* , props data is read-only, data coming from the parent should not be changed by child components.

# Using Props in React

* Firstly, define an attribute and its value(data)
* Then pass it to child component(s) by using Props
* Finally, render the Props Data

## Example : 
```html
class ParentComponent extends Component {  
  render() {
    return (
      <h1>
        I'm the parent component.
        <ChildComponent />
      </h1>
    );
  }
}
```


# Tutorial: Intro to React 

## Setup for the Tutorial

* Setup Option 1: Write Code in the Browser

First, open this Starter Code in a new tab. The new tab should display an empty tic-tac-toe game board and React code. We will be editing the React code in this tutorial.  

* Setup Option 2: Local Development Environment  

## Example :
 ```html 
 class ShoppingList extends React.Component {
  render() {
    return (
      <div className="shopping-list">
        <h1>Shopping List for {this.props.name}</h1>
        <ul>
          <li>Instagram</li>
          <li>WhatsApp</li>
          <li>Oculus</li>
        </ul>
      </div>
    );
  }
}
```



