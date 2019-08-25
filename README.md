# Skechytheme-Bootstrap
 Apply Sketchy theme to Project

 /**
  * Sketchy theme from Bootswatch site, apply bootstrap
  * Using gulp to compile sccs to css
  *
  * Current gulp version: 4.0.2
  * Command check version of gulp:  gulp -v
  *
  * Author: Truong Giang, Huynh
  * Created: 08/03/2019
  * Modified: 08/04/2019
  
**/
![image](https://user-images.githubusercontent.com/46371428/63643971-3ce2aa00-c6a2-11e9-8d2f-b36f4a466a6c.png)

![image](https://user-images.githubusercontent.com/46371428/63643976-68fe2b00-c6a2-11e9-922f-ae54f3a6653f.png)

  Notes: Basic structure download from https://github.com/84tghuynh/Gulp-Bootstrap
         before go further steps below

1. Download from https://bootswatch.com/ these files below to "_resource" folder.

    _bootswatch.scss

    _variables.scss

    bootstrap.css

    bootstrap.min.css


    Then, rename _variables.scss to _sketchy-variables.scss

2. copy two files:
    _bootswatch.scss &  _sketchy-variables.scss  

   To src\scss\vendor\bootstrap

3. Declare _bootswatch.scss &  _sketchy-variables.scss
   to src\scss\vendor\bootstrap\_index.scss by adding to lines below

   @import "sketchy-variables";

   @import "bootswatch";

4. Create scss files in src\scss\partials

   _header.scss

   _single-product.scss

   _similar-products.scss

   _footer.scss

   Declare the files above into src\scss\partials\_index.scss

   @import "header";

   @import "single-product";

   @import "single-product";

   @import "footer";


5. index.html

   Using Navbar:  https://getbootstrap.com/docs/4.3/components/navbar/

   Using Card-Decks: https://getbootstrap.com/docs/4.3/components/card/#card-decks
