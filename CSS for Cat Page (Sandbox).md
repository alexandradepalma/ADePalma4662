## Cat Page
###CSS:

body {font-family: verdana;
   color:black;
   padding:15px;
   font-size:18px
   align:left;
  background-color:#FF99FF;}

/*headers*/
  h1,h2,h3

h1{font-size:2em;
line-height: 1.5em}
h2{font-size:1.5em;}
h3{font-size:1.25em;}

h1 {background-color:#CC00FF;}
h2 { background-color: #CC00FF;}
h3{background-color:#CC66FF;}

p { background-color:#CC99FF;}

ul{background:#CC99FF;list-style-type:none;}

li:before{ content:'✔';
margin-left: -1em;
margin-right: .100em;}

p{font-size:1em}
p:first-child::first-letter
{font-size:2em; text-decoration: underline;}
a:hover{ text-decoration: none;}


/*The Grid*/

{box-sizing: border-box;
  -moz-box-sizing:border-box;
    -webkit-box-sizing: border-box;}

.grid{
  margin: 00 10px 00;
  background: #FFCCFF;
  margin:10px;}

.grid{margin:00 10px 0; padding: 10px;}
.grid-3-4 {width: 75%}
.grid-1-4{width:25%}

[class*=grid]{
  float:left;
  padding-right: 10px;
  margin-top: 10px;
}
.grid[class=grid]:last-of-type
{padding-right:10px; /*offsets above padding*/
}
/* Grid Modules*/ 

.module{
  padding: 10px;
  height: auto;
}
.module img {
  margin:00 10px 00; padding: 10px
  width:100%;
  height:400px
}

###HTML:
<section id="cats">
  <h1>4662w-ers love cats on the internet</h1>
  
  <article class="grid bg-color">
    <h2 id="why-cats">Why cats?</h2>
    <div class="grid-1-4-left-img-container">
      <div class="module">
      
        <img src="http://www.wchs4pets.org/wp-content/uploads/2015/03/cat_1-jpg.jpg" alt="yay it's a cat picture"/>
      </div>
    </div>
    <div class="grid-3-4 right-text-container">
      <div class="module">
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea <a href="" target="_blank">commodo consequat</a>. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
        </p>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
        </p>
      </div>
    </div>
  </article>

  
  <article class="grid bg-color">
    <h2 id="cat-agenda">A cat's to-do list</h2>
    <div class="grid-1-4 left-img-container">
      <div class="module">
        <img src= "http://i.imgur.com/NAg1f1U.jpg" />
      </div>
    </div>
    <div class="grid-3-4 right-text-container">
      <div class="module">
        <p>
          A list of things on my cat-agenda today:
        </p>
        <ul class="checkmark">
          <li>Sleep
          <li>Eat
          <li>Claw the couch
          <li>Sleep
          <li>Move to the sunspot on the rug and sleep
          <li>Eat
          <li>Stare out of the window
          <li>Sleep
        </ul>
      </div>
    </div>
  </article>
  
  <article class="grid bg-color">
    <h2 id="more-cats">More on cats</h2>
    <div class="grid-1-4 left-img-container">
      <div class="module">
        <img src="http://www.themonitordaily.com/wp-content/uploads/2015/06/schizophrenic-cat.jpg" alt="cat with socks on head" />
      </div>
    </div>
    <div class="grid-3-4 right-text-container">
      <div class="module">
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
        </p>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
        </p>
      </div>
    </div>
  </article>
    
</section>

Enter text in [Markdown](http://daringfireball.net/projects/markdown/). Use the toolbar above, or click the **?** button for formatting help.
