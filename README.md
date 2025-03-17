/* General Styles */
body {
  font-family: Arial, sans-serif;
  margin: 0px;
  padding: 0px;
  line-height: 1.5;
}
header {
  background:#fff;
  color: #333;
  padding: 0px 0px;  
}
header nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding-right: 2%;
}
header .logo {
  font-size: 1em;
  font-weight: bold;
  height: 120px;
  padding-left: 1%;  
}
.hero .carousel .carousell {
width:1000px;
height:1000px;
}
header ul {
  list-style: none;
  display: flex;
  gap: 15px;
}
header ul li a {
  color: #333;
  text-decoration: none;
}



/* Section Styles = SERVICES*/
div.gallery {
  margin: 10px;
  border: 1px solid #ccc;
  float: left;
  width: 735px;
}
div.gallery:hover {
  border: 1px solid #777;
}
div.gallery img {
  width: 100%;
  height: 400px;
}
div.desc {
  padding: 15px;
  text-align: center;
}
.quarter{
  height: 100px;
  width: 200px;
}
.about{
  height: 100%;
  width: 100%;
  background-color: #777;
}



/*FREQUENTLY ASKED QUESTION*/
.expert-suggestion-section{
background-color: white;
}
.expert-suggestion-section {
    padding: 30px 0 40px;
    overflow: hidden;
    background-color: #d8dee4;
    text-align: center;
}
section {
    overflow: hidden;
    display: block;
}
article, aside, figcaption, figure, footer, header, hgroup, main, nav, section {
    display: block;
}
*, ::after, ::before {
    box-sizing: border-box;
}
section {
  text-align: center;
    display: block;
    unicode-bidi: isolate;
}
body {
    margin: 0;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
    font-size: 1rem;
    font-weight: 400;
    line-height: 1.5;
    color: #212529;
    text-align: left;
    background-color: #d8dee4;
}
html {
    font-family: sans-serif;
    line-height: 1.15;
    text-size-adjust: 100%;
    scrollbar-highlight-color: transparent;
}
*, ::after, ::before {
    box-sizing: border-box;
}
*, ::after, ::before {
    box-sizing: border-box;
}



.dropbtn {
  background-color: #04AA6D;
  color: white;
  padding: 20px;
  font-size: 16px;
  border: none;
}

.dropdown {
  position: relative;
  display: inline-block;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f1f1f1;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}

.dropdown-content a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
}

.dropdown-content a:hover {
  background-color: #ddd;
}

.dropdown:hover .dropdown-content {
  display: block;
}

.dropdown:hover .dropbtn {
  background-color: #3e8e41;
}




/*CONTACT FORM*/
form {
  max-width: 400px;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
}

form label, form input, form textarea, form button {
  margin-bottom: 10px;
}

form input, form textarea {
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

form button {
  padding: 10px;
  background: #333;
  color: #fff;
  border: none;
  cursor: pointer;
}



/*ADDRESS*/
.add {
  text-align: center;
  background: #403f3f;
  color: #fff;
  padding: 10px 0;
}


/*ADDRESS*/
footer {
  text-align: center;
  background: #333;
  color: #fff;
  padding: 10px 0;
}
