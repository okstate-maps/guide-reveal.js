## About
Last Updated *[10/28/2019]*   
Created by [OSU Maps and Spatial Data](https://info.library.okstate.edu/map-room)


## Table of Contents
- Introduction 
- - Basic Setup
- - Folder Structure
- - Creating Presentation Content
- Conclusion
- Further Reading/Resources

## Introduction
reveal.js is a wonderful way to create sleek and unique presentations using HTML.
There are many features available to add flare to your presentation and *wow* your audience.
In this guide, I will walk you through the basic steps needed to create your own presentation.

#### Basic Setup
The **basic setup** allows you to author your very own presentations only. There is a **full setup**, but we'll go over this in another guide. 
1. To get started, you need to download the lastest version of reveal.js from [this website](https://github.com/hakimel/reveal.js/releases).
2. Unzip and replace the contents in index.html with your own presentation content.
3. Use a browser to open and view your presentation.

#### Folder Structure
There are a few different folders to store separate elements
- **css/** Core stules that make the project function correctly
- **js/** Similar to CSS but for JavaScript
- **plugin/** Stores components that were developed as extensions to reveal.js
- **lib/** Any other third party asset (JavaScript, CSS, etc.)

#### Creating Presentation Content
I, personally, prefer to create my presentation content before I get too mixed up in the style and appearance of the presentation. However, this is not the only way to create a *reveal.js* presentation. 

1. First, we need to begin with our presentation's skeleton. 
```<html>
	<head>
		<link rel="stylesheet" href="css/reveal.css">
		<link rel="stylesheet" href="css/theme/white.css">
	</head>
	<body>
		<div class="reveal">
			<div class="slides">
				<section>Slide 1</section>
				<section>Slide 2</section>
			</div>
		</div>
		<script src="js/reveal.js"></script>
		<script>
			Reveal.initialize();
		</script>
	</body>
</html>
```
The order of the presentation markup must be *.reveal > .slides > section*. Each *section* represents a different slide. 
2. Let's create a title page. For my presentation, I will be talking about hedgehogs, so this is the code for my very first slide. 
```
<section>
	<h1>Hedgehogs:</h1>
	<h2>The World's Cutest Animal</h2>
	<p>By: Addison Van Zandbergen</p>	
</section>
```
3. Continue to add sections as desired.

#### Style
verticle slides
transitions
pictures

## Conclusion

## Further Reading/Resources


[Return to Top](#about)
