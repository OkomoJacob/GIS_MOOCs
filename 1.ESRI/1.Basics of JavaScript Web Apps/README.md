## Basics of JavaScript Web Apps By ESRI

### Contents:
- [Basics of JavaScript Web Apps By ESRI](#basics-of-javascript-web-apps-by-esri)
  - [Contents:](#contents)
- [INTRODUCTION](#introduction)
  - [Course Objectives](#course-objectives)
- [Understanding web pages](#understanding-web-pages)
  - [Getting started with HTML](#getting-started-with-html)
- [Making web pages dynamic](#making-web-pages-dynamic)
  - [Getting started with JavaScript](#getting-started-with-javascript)
  - [Write JavaScript code](#write-javascript-code)
  - [Discovering the ArcGIS API for JavaScript](#discovering-the-arcgis-api-for-javascript)
  - [Implementing the ArcGIS API for JavaScript](#implementing-the-arcgis-api-for-javascript)
    - [Resources](#resources)
  - [Exercise: Modify an existing web map app](#exercise-modify-an-existing-web-map-app)
  - [Results](#results)

## INTRODUCTION
### Course Objectives
- Differentiate between HTML, CSS, and JavaScript.
- Given code, alter the position and style of components within a web map app.

## Understanding web pages
Every web page consist of:
- HTML
- CSS
- Scripting Language e.g JS

<img src="https://github.com/OkomoJacob/GIS_MOOCs/blob/main/1.ESRI/1.Basics%20of%20JavaScript%20Web%20Apps/assets/webPage.png">

### Getting started with HTML
This is basically how a sample web page structure should look like.However, you can play around with the tags at freedom.
<img src = "https://github.com/OkomoJacob/GIS_MOOCs/blob/main/1.ESRI/1.Basics%20of%20JavaScript%20Web%20Apps/assets/webPage.png">
## Making web pages dynamic
- You will now learn about using JavaScript to make a web page more interactive. 
- This topic will introduce you to the basics of JavaScript scripting as well as how to get started writing JavaScript code. 
- You will also learn about the ArcGIS API for JavaScript and how to implement a basic web mapping app using it.

<img src="https://github.com/OkomoJacob/GIS_MOOCs/blob/main/1.ESRI/1.Basics%20of%20JavaScript%20Web%20Apps/assets/JSBrowsers.png">

### Getting started with JavaScript
Scripting languages primarily run inside web browsers to make web pages dynamic and interactive. There are many scripting languages available that are supported in multiple web browsers. When you create a web page that contains JavaScript, remember that JavaScript behaves differently in different web browsers. Incompatibility differences may exist based on which JavaScript capabilities are supported in each browser.
<img src="https://github.com/OkomoJacob/GIS_MOOCs/blob/main/1.ESRI/1.Basics%20of%20JavaScript%20Web%20Apps/assets/Getting%20started%20with%20JavaScript_2.png">

### Write JavaScript code
In this activity, you will practice writing your first JavaScript code using basic JavaScript functionality. Using the following instructions, construct your JavaScript by dragging the listed code items to their correct position in the unfinished web page.

Your supervisor has assigned you to complete the following JavaScript code to make it work properly. After an initial inspection of the code, you must create a function named myMessage. The myMessage function should be called directly from an onClick event when someone browsing your page clicks the Press Me button. Within the myMessage function, a variable named message is created with a value of My first JavaScript. After the variable is created, display the message variable in the document's demo div element.
<img src="https://github.com/OkomoJacob/GIS_MOOCs/blob/main/1.ESRI/1.Basics%20of%20JavaScript%20Web%20Apps/assets/Getting%20started%20with%20JavaScript_3.png">

### [Discovering the ArcGIS API for JavaScript](https://developers.arcgis.com/)
An application program interface (API) is set of objects and tools used for building applications. APIs exist for building desktop, mobile, and web-based applications. The ArcGIS API for JavaScript is a web API that allows you to script applications that are accessible over the web. Numerous APIs are available for building applications, and you can use multiple APIs to build a single web app. Using the ArcGIS API for JavaScript, you can implement GIS and mapping interaction-related functions by writing just a few lines of JavaScript code

<img src= "https://github.com/OkomoJacob/GIS_MOOCs/blob/main/1.ESRI/1.Basics%20of%20JavaScript%20Web%20Apps/assets/ArcGIS%20API%20for%20JavaScript.png">
Mapping, querying, feature editing, tracking, routing, and geoprocessing tasks are all capabilities or services available to you when using the ArcGIS API for JavaScript.

<img https://github.com/OkomoJacob/GIS_MOOCs/blob/main/1.ESRI/1.Basics%20of%20JavaScript%20Web%20Apps/assets/Dojo%20Toolkit.png>
- The ArcGIS API for JavaScript communicates directly with individual services published to ArcGIS for Server or services hosted in Portal for ArcGIS or ArcGIS Online. 
- The ArcGIS API for JavaScript is built on top of the [Dojo Toolkit](https://dojotoolkit.org/). 
- The toolkit provides widgets, CSS styles, and JavaScript functions for building robust interactive web apps.

### Implementing the ArcGIS API for JavaScript
Custom web apps are easy to create using the ArcGIS API for JavaScript. Styles, objects, and widgets are included in the API, allowing you to customize appearance, code custom functionality, and include existing functionality in your web app.
#### Resources
- [Esri Map Properties](https://developers.arcgis.com/javascript/latest/api-reference/esri-Map.html)
- [Basemaps](https://developers.arcgis.com/javascript/latest/api-reference/esri-Map.html#basemap)
- [Explore Code Live on Sandbox](https://developers.arcgis.com/javascript/latest/sample-code/sandbox/?sample=intro-mapview)
### Exercise: Modify an existing web map app
You work as a technical professional for a large auto parts company based out of Sandusky, Ohio. Your supervisor has an idea for upgrading the corporate web app to include a map that geographically displays the company's distributor locations. You have been tasked with putting together a quick web mapping app prototype. The prototype will display a map centered on the location of the company headquarters. To build the prototype, you will use HTML, CSS, and JavaScript referencing the ArcGIS API for JavaScript.

### Results
- Upon modifying the codes to get started with the ArcGIS Javascript API, you sould get sample outpits like the ones appended below.
<img src="https://github.com/OkomoJacob/GIS_MOOCs/blob/main/1.ESRI/1.Basics%20of%20JavaScript%20Web%20Apps/assets/preview.png">
<img src="https://github.com/OkomoJacob/GIS_MOOCs/blob/main/1.ESRI/1.Basics%20of%20JavaScript%20Web%20Apps/assets/endResults.png">
