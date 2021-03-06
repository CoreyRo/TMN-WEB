# The Music Network Frontend
Please refer to the wiki page here on github.
## Requirements
* node 8+
* npm or yarn installed
## Instructions
* Fork this repository first and then clone, DO NOT clone the repository directly.
* run ```npm install``` in a command line inside of the repo's main directory
* run ```npm run dev``` to start the dev server
* Make sure that all scss files are kept inside of the public folder under "styles" and imported into index.scss like so:
```sass
 @import "path/to/your/sass/file";
```
* remember to add a .env file and copy the contents of .env-example into it
### Syntax
Please use this JSX syntax in your Vue components to keep all files cleaner:
```javascript 
import Vue from "vue";

export default Vue.component("App", {
  render: function(h) {
    return <div>Hello World</div>;
  }
});
```
## Style Guide
### SCSS
* For this project we use BEM css. Here is a great article if you are unfamiliar with BEM style guide https://css-tricks.com/bem-101/
* All css is required to be written in SASS, more specifically SCSS, if you are unfamiliar with SASS here is a quick guide. https://sass-lang.com/guid
* Each style sheat should be placed in the assets folder, always try to find a selector inside this folder before creating one
* All pull request's must be reviewed and approved by two people, this way we can identify best practices and give advice to each other to optimize the code base




