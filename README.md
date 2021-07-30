# Sass Grid System
Here is a Sass grid system for your web project. This grid use both flexbox and sass technologies to provide you flexible and easy to use CSS framework.

## Configure your grid
To configure your grid, you juste need to modify the **"_variable.scss"** file. The file allow you to controls the number of the columns un your grid, the width ou the gutter and many ohter options.
- Number of columns
- Width of the Gutter
- Enable if the gutters are outside of the container or not

You also have the ability to add, modify or delete breakpoints. Breakpoints are used to generate media queries. Here is the default breakpoint list :
- xs: 0px,
- sm: 36em, // 576px
- md: 48em, // 768px
- lg: 62em, // 992px
- xl: 75em // 1200px

## Test the grid

Needed Dependences : Node.js & Parcel.js
https://nodejs.org/en/
https://parceljs.org/

You can use the grid and build the dist folder using Parcel.js.
Simply run the following command to bundle the project and launch a new web server :
```
parcel index.html
```

You can now accessing to the render at http://localhost:1234.

You can tweak the parameters to test and create your grid.

Happy coding !