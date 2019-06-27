---
Layout:
Title: "java springbot"
date: 2019-06-27 09:40
categories:
---

#Springbot

Spring Boot makes it easy to create stand-alone, 
production-grade Spring based Applications that you can "just run".
### Spring MVC
Spring MVC is the original web framework built on the Servlet API. It is build on the popular MVC design pattern. MVC (Model-View-Controller) is a software architecture pattern, which separates application into three areas: model, view, and controller.
The model represents a Java object carrying data. 
The view represents the visualization of the data that the model contains. 
The controller controls the data flow into model object and updates the view whenever data changes.
 It keeps view and model separate.
 ### Controller
the controller uses @Controller annotation to indicate that the annotated class is a controller. 
It is a specialization of @Component and is autodetected through classpath scanning. 
It is typically used in combination with annotated handler methods based on the @RequestMapping annotation.
 @RestController is a sibling convenience annotation for creating Restful controllers.