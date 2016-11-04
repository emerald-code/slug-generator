var slugify = require('slugify')

// add string to a function to create slug 
slugify('this is a string') // returns this-is-a-string

// if you want to change default separator(-) add 2nd paramenter to function 
slugify('this is a string', '_') //returns this_is_a_string
