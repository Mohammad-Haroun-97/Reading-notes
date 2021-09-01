# solving using React

## How would you break a mock into a component hierarchy?

#### The first thing youâ€™ll want to do is to draw boxes around every component (and subcomponent) in the mock and give them all names. If youâ€™re working with a designer, they may have already done this, so go talk to them! Their Photoshop layer names may end up being the names of your React components!

## What is the single responsibility principle and how does it apply to components:
![thinking](https://i.morioh.com/201022/2f6459ee.webp)
#### The single-responsibility principle (SRP) is a computer-programming principle that states that every module, class or function in a computer program should have responsibility over a single part of that program's functionality, and it should encapsulate that part.


## What are the three questions you can ask to determine if something is state?
1- if you want to control the behavior of the component
-2 some information that may change over the lifetime of the component
-3 change something inside Component
## How can you identify where state needs to live?
Once you've identified data, it should be stated in the application. We need to work out which components rely on the state,