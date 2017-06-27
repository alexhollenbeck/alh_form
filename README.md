# alh_form
Simple form validator npm module

# Installation
npm install alh_form

# Usage
In the html:

Give your form inputs type "name", "email", "birthday", and "password", and give all inputs a data-error-showing="false" attribute. For each input, include an empty error entity with attribute data-error-for="[input name]" and data-error-showing="false".



In the javascript, include at the top:

var alhForm = require('alh_form');

And attach the form validator using a selector for the form.

alhForm.form('selector');

# Example
https://github.com/alexhollenbeck/wonderschool_form