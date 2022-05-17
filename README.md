# Intro-to-SASS-and-NPM

<h2>What is SASS?</h2>
SASS stands for <i>Syntactically Awesome Stylesheet</i>. It is a CSS pre-processore scripting language
that is interpreted or compiled into Cascading Style Sheetes (CSS)

<h2>Way Use SASS?</h2>

Stylesheets are getting larger, more complex and harder to maintain. This is where pre-preocessore can help

Sass lets you use fetures that do not exist in CSS like:

 <ul>
        <li>variables</li>
        <li>import</li>
        <li>mix</li>
        <li>nesting rules</li>
        <li>inheritance</li>
        <li> build function and another stuff</li>
    </ul>
    this making the coding process easy to do, keeping your code organized and reducing repetition.

<h2>How Does SASS Work?</h2>

A browser does not understend Sass code. Therefore, you will need a Sass preprocessore to converter Sass code into Standart CSS.
This process is calles transpiling. So, you need to give a transpiler (some kind of the program) some Sass code and then get same Css code back.

<h2>Benefits of SASS</h2>

 <ul>
        <li>Sass reduce repetition of CSS and therefore saves time</li>
        <li>It lets you use variables to hold reusable values, thereby making code easy to maintain and debug</li>
        <li>It helps keep your code organized by letting you combine CSS rulesof a single unit together</li>
        <li>Organizing commponents into units also allows you to reuse commponents in other parts of the code or in other programs</li>
        <li>You can create small files with CsS SNIPPETS TO INCLUDE IN OTHER sASS FILES</li>
        <li>It lets you use operators so you can perform calculation right inside your CSS</li>
    </ul>

<h2>SASS Basic Principales-variables, nesting</h2>

Sass lets use you the variables at the same variables in differente places;

Variables are a way to store information that can you can re-use later.
With Sass , you can store the fplling information in varaibles:

<ul>
    <li>strings</li>
      <li>numbers</li>
      <li>colors</li>
      <li>booleans</li>
      <li>lists</li>
      <li>nulls</li>
</ul>

<h6>Sass Vraibles Syntax</h6>
$variablename:vaule;

<h3>There aretwo main advantages of the using  Variables in Sass</h3>

<ul>
    <li>You can use the descriptive names and replace it is'not necessary that you are to remember Hexadecimal, but just replace it with name of the variables.</li>
      <li>In the future if you want to make any changes on the variables universal just replace value, and it  gets reflects  automatically in all places.</li>
     
</ul>

<h2>Nesting Sass</h2>

Nesting lets you nest CSS selectors in the same ways as HTML.

Nest properties in Sass, makes it cleaner and easier to read than standart CSS.

<h2>SASS BASIC PRINCIPALES</h2>

<h2>@import</h2>

Using @import in Sass, you keep your code DRY (Don't Reapet yourself)

For this, keep related code in separate files and import them into a single file using @import.

<h2>Mixins</h2>
