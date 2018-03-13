---
layout: post
title:      "CreateReport action and props 🎉"
date:       2018-03-13 18:49:26 -0400
permalink:  createreport_action_and_props
---


Within my last portfolio project( an awesome React project about [Doctor Who](http://www.bbc.co.uk/programmes/b006q2x0)), I channeled in the power of mapDispatchToProps. 

I needed to add the createReport action to the props of the ReportForm component by way of mapDispatchToProps and connect.

 ‘Connect’  basically connects the component(in my case, ReportForm) to the redux store. By including the ‘mapDispatchToProps’ function as an argument, I’m allowing this component to have access to this specific part of the redux store. 
Now to further explain MapDispatchToProps; it is the useful means that redux provides to dispatching actions from my component to the store(so it is updated). In addition, we use the ‘bindActionCreators’ which maps the action function to an object using the names of the action functions(in my case, that is ‘createReport’. These functions automatically dispatch the action to the store when the function is called(in my code, this action is called on by ‘handleOnSubmit)’.  

If you want to check out the entire project and see the steps I took(commits) to create this application, checkout out my repo: https://github.com/Ccordova41/doctor-who-app-client


HAPPY CODING!! 🎉🎉
