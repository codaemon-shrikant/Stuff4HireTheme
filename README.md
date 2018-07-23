Document 

document to use sass and do the future development in the stuff4hire

Run following command which compile your css file when you do the changes in the scss. It will help you to reduce your effort of compiling scss after every single change.

sass --watch assets/sass/custom.scss assets/css/custom.css


create a separate file for each component 
for eg. product.scss

import file in the custom.scss file 
@import product.scss

