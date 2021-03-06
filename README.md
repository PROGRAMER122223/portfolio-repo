# portfolio-repo

## This repository  is built to potray details about me,and showing my skills n knowledge  using  css and html,it gave me a platform to learn new skills .this portfolio satisfies typical requirements as below



## User Story

```
This portfolio satisfies a potential employee's deployed portfolio of work samples.
```
## Acceptance Criteria

Here are the critical requirements necessary to develop a portfolio that satisfies a typical hiring manager’s needs:

```

WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them
WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section
WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications
WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others
WHEN I click on the images of the applications
THEN I am taken to that deployed application
WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport
```
## Mock-Up

The following animation shows the web application's appearance and functionality:

![webpagelooks](./assets/scren.png)

## Build status
 Though this page runs without error,while taking screen shot aside and paragraph is poping out of the div container.
 
## Features
         
   * The name h1 element has given some glowing effect on hovering:
``` html   
              
           <h1><span></span><span>Prathibha </span><span>V</span>adakkini <span>P</span>urakkal</h1>
```        
```css
           h1 span{
  transition:0.5s;
}

h1:hover span:nth-child(1){

  margin-right: 10px;
}
h1:hover span:nth-child(1)::after{
  content:"I m";
}


h1:hover span:nth-child(2){
  margin-left: 10px;
}


h1:hover span{
  color: #fff;
  
  text-shadow:0 0 10px #fff;
  cursor: pointer;  
}
             
```

*   implemented code to display name and url on image source:
```html

  <div class="image">
       <img src="./assets/pic4.jpg" alt="image of Project-3" class="workimage" />
        <div class="bottom-left">
             <h3>Project-3</h3>
             <a ref="">READ MORE</a>
         </div>
  </div>                       
```
```css
#image{
       position:relative;
       color:blue;
       height:380px;
       width:100%;
       transition:1s;
       
     }
     .bottom-left{
      position:absolute;/*SINCE HOLDING CONTAINER IS RELATIVE*/
      background-color:white;
      bottom:5px;
      
    }
```

##  API reference

    HOVERING EFFECTS ON TEXT[YOUTUBE VIDEOS](https://youtu.be/I_RhD99rROc)

    position text over an image[w3schools](https://www.w3schools.com/howto/howto_css_image_text.asp)


## URL

* The URL of deployed application:https://programer122223.github.io/portfolio-repo/
* The URL of github repository:https://github.com/PROGRAMER122223/portfolio-repo.git