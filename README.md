#Data Visualization with D3 4.x Cookbook - Second Edition
This is the code repository for [Data Visualization with D3 4.x Cookbook - Second Edition](https://www.packtpub.com/web-development/data-visualization-d3-4x-cookbook-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781786468253), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
This book gives you all the guidance you need to start creating modern data visualizations with D3 4.x that take advantage of the latest capabilities of JavaScript.

The book starts with the basic D3 structure and building blocks and quickly moves on to writing idiomatic D3-style JavaScript code. You will learn how to work with selection to target certain visual elements on the page, then you will see techniques to represent data both in programming constructs and its visual metaphor. You will learn how map values in your data domain to the visual domain using scales, and use the various shape functions supported by D3 to create SVG shapes in visualizations.


##Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.



The code will look like the following:
```
var timeFormat = d3.time.format.iso;
var data = crossfilter(json); // <-A
var hours = data.dimension(function(d){
return d3.time.hour(timeFormat.parse(d.date)); // <-B
});
```

A text editor to edit and create HTML, CSS. and JavaScript files. 
A modern web browser (Firefox 3, IE 9, Chrome, Safari 3.2, and later) 
A local HTTP server to host data file for some of the more advanced recipes in this book.
We will cover how to set up a Node-based or Python-based simple HTTP server in the first chapter.
Optionally, you will need a Git client if you would like to check out the recipe source code directly from our Git repository.

##Related Products
* [Building Responsive Data Visualizations with D3.js [Video]](https://www.packtpub.com/web-development/building-responsive-data-visualizations-d3js-video?utm_source=github&utm_medium=repository&utm_campaign=9781784394509)

* [Rapid D3.js [Video]](https://www.packtpub.com/web-development/rapid-d3js-video?utm_source=github&utm_medium=repository&utm_campaign=9781783554416)

* [Mastering D3.js [Video]](https://www.packtpub.com/web-development/mastering-d3js-video?utm_source=github&utm_medium=repository&utm_campaign=9781783985784)

###Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.
### Download a free PDF

 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to claim your free PDF.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781782162162">https://packt.link/free-ebook/9781782162162 </a> </p>