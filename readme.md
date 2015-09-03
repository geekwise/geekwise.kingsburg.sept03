##Geekwise Introduction to <HTML> and CSS
###Wednesday
###Date: 09-03-2015

##Overview
### 1: Review important concepts from the prior day
* <HTML> `<tags>` have Attributes and Values
* The `<style>` Tag and how to style <HTML>
* link to course <http://www.geekwise.org>
* link to colors <http://color.geekwise.org>

### 2: Share an overview of what will they will learn today
* Using the `10	` <HTML> Tags we know with CSS
* Adding images using CSS with the `<style>` tag
* We will be making our page on <http://www.codepen.io>

### 3: Practice exercise related to concept and objective
* Working and presenting as a team your one page team site with `CSS`
 
### 4: Closing session and circling back to objective of the day
* When to use `CSS` in the `<style>` tag or as an attribute inside `<HTML>`.
* Creating a page with the `10` `<HTML>` tags we learned.

> ```
> <style type='text/css'>
> 
> h1{
> 	color:lightgreen;
> }
> 
> </style>
> ```

> VS

> `<h1 style='color:lightgreen;'Text With Color</h1>`

* Creating a full <HTML> one page site with CSS
* Answer questions about exercise
* Use <http://www.codepen.io> with new <HTML> tags and CSS.
* We will be using <HTML> and css to being creating a small site for our teams.

---
#1: Anatomy of a Website

### A website has both content and formating.
### Using `<HTML>` to structure the content and `CSS` to format it.

## `<HTML>` (Structure) + `CSS` (Presentation)

```
<style type='text/css'>
	body{
		background-color:aqua;
	}
</style>
```

## What was taught the day prior?
* using the `<style>` tag to create `CSS`
* that `CSS` has attributes that require an opening and closing process similar to `<HTML>`

> ```
> <style type='text/css'>
> body{ <----- OPEN
> 	background-color: <---- OPEN  CLOSE ----> ;
> } <------ CLOSE
> </style>
> ```

> ```
> <h1 style='color:lightgrey;'>Light Grey</h1>
> ```



## CSS = Cascading Style Sheets

CSS is a "style sheet language" that lets you style the elements on your page.

CSS is embedded inside HTML, but it is not HTML itself.

## HTML = Hyper Text Markup Language

HTML is a "markup language" that lets you structure content on your page.



## CSS: What can it do?

Color,Size,Visibility,Height and Width.

```
<!DOCTYPE HTML>
<HTML>   
 <head>
  <meta charset="utf-8">
  <style type='text/css'>
	   body{
		font-size:500%;
		color:blue;
		background:lime;
	   };
	</style>
  <title>Title of your website page</title>
 </head>
 <body>
		 	Our website!
  </body>
<HTML>
```

## Anatomy of CSS

### CSS consists of "style rules".
Each style rule consists of a "selector" and "declarations" of property-value pairs: 

```
 
selector {
  property: value;
  property: value;
}

/* Change Body Color To Yellow */

body {
  color: yellow;
  background-color: black;
}

```

#The selector: Cascade rules

Generally:
> `ID` is more specific than a `CLASS`, class is more specific than element. 

```
<style type='text/css'>
	#image01{
		height=100px;
		width=100px;
	} 
</style>
<img id='image01' href='image_url'></img>
```

#Using CSS to make the `<HTML>` more interactive

```
a:link { /* unvisited link */
  color: red;
}
a:visited { /* visited link */
  color: blue;
} 
a:hover { /* moused over link */
  color: green;
}  
a:active { /* current link */
  color: purple;
} 
a:focus {  /* focused link */
  color: purple;
} 

```


#Types of Selectors

 * 1: element
 * 2: id
 * 3: class
 * 4: position in document 


#Types of Selectors: element
```
p{
	color: yellow;
}
```

> Selects all `P` elements in the entire document.


#Types of Selectors: id

```
#header {
	background-color:lightYellow;
}
```
Selects any element with the id “header", 

```<p id="header"></p>```

Element ids are unique, so that should only be one element.

The `#` is how you tell CSS "this is an id."

# Types of Selectors: class

```
.buttons {
  color: red;
}
```

Selects any element with the class name “buttons”

```<p class="button"></p>```

Multiple elements can have the same class name.

The `.` is how you tell CSS "this is a class name."


#Extra Reference
## A list of all the colors you can use in <HTML>
<http://geekwise.github.io/colors/>