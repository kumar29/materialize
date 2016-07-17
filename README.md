A fork of materializecss framework with the grid system stripped out so that 
it can be used along with bootstrap framework
Compile sass with:
sass --watch sass/materialize.scss:dist/css/materialize.css
sass --watch sass/materialize.scss:dist/css/materialize.min.css --style compressed --scss

### Current Version : v0.97.11
Added filled-in class to the input of a select if the select has a non null value.

### Current Version : v0.97.10
Added a webkit-transform for input field labels which have an active class

### Version : v0.97.9
Changed select-plugin code to have select-id as an attr instead of a data attribute. This is needed for 
haven and bindster to have the select-id come back to the DOM after it was removed. 

### Version : v0.97.8
Changed drop down caret so that it doesn't conflict with bootstrap's caret
