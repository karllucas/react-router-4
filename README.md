# react-router-4

This project is for learning the fundamentals of using _React Router_ features.

It utilises the _react-router-dom_ features such as _Switch, Route, Link_, and more.
The project also teaches one how to use React props such as _history, location, params_ and more.
Simply pass a _console.log()_ method immediately after your _render()_ and include _this.params_ as your parameter to access the features. A clear illustration is shown below:

       import React, { Component } from 'react';

       export default class AnyClassName extends Component {
         render() {
           console.log(this.props);
           return (
              //returns a certain element
           );
         }
       }
       
The project uses the props to access the url.
The inputs of the form are pushed into the url using _this.props.history.params_ to display a new page with details of the inputs.
       
_This is a great way to learn how to work with react-router-dom and to utilize props on the console._
