# CSUS x McHacks Introduction to Web Development 
Welcome to the CSUS x McHacks Introduction to Web Development Workshop!  <br/>
   <br/>
The slides for the workshop are accessible through this link: <br/>
https://docs.google.com/presentation/d/1Cf836Xk-oPFjZ-ayoYAOPGvoY9IixWxDEn25VX6XBoU/edit#slide=id.g155acdc2e75_0_0 <br/>
   <br/>
This documentation will help you navigate through this interactive workshop, so let's get started! <br/>

## Getting Started 
Before we start please dowloaded Microsoft Visual Studio Code <br/>
The download link is the following: https://code.visualstudio.com/download <br/>
Once you have Visual Studio Code, dowload the Quokka extension on VSCode <br/>

## Let's Code! 
To get started download the files **outline.html** and **outline.css** from this repository<br />
Or copy and paste it from here <br />
### Outline.html  <br />
```
<!DOCTYPE <!DOCTYPE html>
<html lang="en"> <!--the language for your website-->
<html>
    <head>
        <meta charset="utf-8"> <!--specify character set-->
        <title>Insert Title </title>  <!--title of the website-->
        <meta name="description" content="">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="outline.css"> <!--this links our css file with our HTML-->
    </head>
    <body>
        <header>
            <h1> Insert Header Here </h1>
        </header>
        <p> Look at the comments to see what you can change! </p>

    </body>
</html>
```
### Outline.CSS  <br />
```
/*Outline for the a typical CSS file*/
h1{ /*Element you want to style corresponding to html tag*/
    /*Color: blue (this is how you insert a set style for css)*/
    color: lightblue;
}

p {

}
```
If you setup properly you should have the following when you run your website on your local environment <br />
   <br />
### Proper Setup <br />
![Screenshot 2023-11-19 at 11 31 32 PM](https://github.com/ethanwongca/CSUSxMcHacksWebDev/assets/87055387/e3ec718e-6cb7-47ed-9128-820bd3d7ffb7) <br/>

> If you made your first website congratulations!

## HTML Portion
Let's make the structure for the wiki page we are creating today! Don't worry if it isn't pretty, that is what CSS is for

### Final Result 
<img width="1232" alt="Screenshot 2023-11-20 at 1 09 56 AM" src="https://github.com/ethanwongca/CSUSxMcHacksWebDev/assets/87055387/5460d781-d121-4a65-865e-9befa889aa22">

### Code for the HTML Portion
```
<!DOCTYPE html>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSUS x McHacks Event</title>
    <link rel="stylesheet" href="outline.css">
</head>
<body>

    <header>
        <h1>CSUS Wiki</h1>
    </header>

    <nav>
        <a href="#overview">Overview</a>
        <a href="#people">People</a>
        <a href="#events">Events</a>
        <!-- add more to the navbar-->
    </nav>

    <section id="overview">
        <article>
            <h2>Overview</h2>
            <p>The CSUS is an elected student group tasked with improving student academics and life in the computer science department. This includes discussing course changes with faculty, organizing events, collating student feedback, and promoting a sense of community.</p>
        </article>
    </section>

    <section id="people">
        <article>
            <h2>People</h2>
            <p>We have amazing people at CSUS</p>
        </article>
    </section>

    <section id="events">
        <article>
            <h2>Events</h2>
            <p>We have events all year! Like FYC events, mixers, and more!</p>
        </article>
    </section>

</body>
</html>
```
> Fun fact Github's README uses tags to break line and to link images

## CSS Portion
Let's make out website pretty!
### Final Result
<img width="1215" alt="Screenshot 2023-11-20 at 1 15 10 AM" src="https://github.com/ethanwongca/CSUSxMcHacksWebDev/assets/87055387/677c7f87-7d07-479c-b989-77f25190e412"> 
### Code for the CSS Portion

```
body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f5f5f5;
}

header {
    background-color: #26aae1;
    color: #fff;
    padding: 1em;
    text-align: center;
}

nav {
    background-color: black;
    padding: 0.5em;
    text-align: center;
}

nav a {
    color: #fff;
    text-decoration: none;
    padding: 1em;
    margin: 0 1em;
}

section {
    max-width: 800px;
    margin: 1em auto;
    padding: 1em;
    background-color: #fff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

article {
    margin-bottom: 2em;
}
```

> Congratulations on Making Your Own Wiki


## Resources for your Web Development Journey
Here are some useful resource for after the workshop. Good luck with your web development journey! <br />
**Documentation**: https://developer.mozilla.org/en-US/ <br/>
**Frameworks and Languages to Learn**: JavaScript, React.js, Angular.js, TypeScript <br/>
