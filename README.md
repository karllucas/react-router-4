# react-router-4

This project is for learning the fundamentals of using _React _Router features.

It utilises the _react-router-dom features such as _<Switch>, _<Route>, _<Link>, and more.
The project also teaches one how to use React props such as _history, _location, _params and more.
Simply pass a console.log() method immediately after your render() and include _this.params as your parameter to access the features. A clear illustration is shown below:

       import React, { Component } from 'react';

       export default class AnyClassName extends Component {
         render() {
           *console.log(this.props);
           return (
              //returns a certain element
           );
         }
       }
       
       The project uses the props to access the url.
       The inputs of the form are pushed into the url using _this.props.history.params to display a new page with details of the inputs.
       
       *This is a great way to learn how to work with react-router-dom and to utilize props on the console.
