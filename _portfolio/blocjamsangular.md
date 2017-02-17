---
layout: post
title: Bloc Jams II
thumbnail-path: "img/blocjamsangular.png"
short-description: Refactor the Bloc Jams project using the Angular Javascript Framework.

---

{:.center}
![]({{ site.baseurl }}/img/blocjamsangular.png)

## Explanation

After finishing the first version of the Bloc Jams music application, this version was used as the foundation to work with my first MVC framework: AngularJs.  Through this initial experience, I was able to refactor the entire project with AngularJs.

## Problem

To use Angular JavaScript framework to simplify the application development and to build the Bloc Jams II project as a single-page application (SPA).  To begin the refactoring, it was necessary to learn how to bootstrap Angular to the application, as well as create an Angular module. 

## Solution

To continue to successfully refactor the Bloc Jams application it was necessary to configure routing and states for the application, followed by implementing controllers for the application's views. The refactoring successfully created a service that allowed the user to control song playback, as well as creating a custom directive that controlled the song and volume sliders.  Finally, a custom time code filer was implemented to modify the time format to appear in a more presentable format.  A key feature of Angular, two-way binding, was implemented to allow for data populated in the view to update via real time to reflect the changes made by the user.

## Results

Testing the changes as I applied them were extremely important since this was my first experience with Angular.  Grunt was used to as task runner for this project.  With the continued changes it was valuable to automate the repetitive tasks during the application development.  The most beneficial task used through Grunt, was with updating the project and viewing it on my local host.  This not only allowed me to view the changed, but to use the console to debug any issues that I encountered.

> **Learning Point -** First experience with Angular, which was exciting as much as it was a learning experience.  Angular is used currently with the product of my current job (NovoEd) and it was interesting to finally understand the different words and concepts that I heard on a daily basis. 

## Conclusion

Through the refactoring of the non-Angular BlocJams, it is now fully "Angularized".  Much of the original code was simplified, as well as compartmentalized to increase security and ease of updating.