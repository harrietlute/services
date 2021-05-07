<h1 style="color:blue;">frontend</h1>
The template contain database tables which has employee details and organization information.

The template front end has tier which has nuxt application.

The template is designed to work in a team development environment. It supports deploying the application in different environment.

Documentation is at [service/frontend.md](service/frontend.md).

## DIRECTORY STRUCTURE
<h>frontend</h>

  assets /  contains application  icons,imgs,javascript and style sheet.

  plugins /   contains JavaScript files that are injected as functions and constants.

  static /      contains files that are automatically mapped and saved.

  build /      contains static files that can be hosted in web servers. 

  dist  /       contain the production files.

 middleware /  contains files that are loaded before rendering a page.

  layouts /     contains layout files for page defination. 
  node_modules contains external libraries and packages that power the app.

 pages /       contains pages to be displayed in the application.
        
    - IAM 
        - auth  contain pages of auth service
    - ems  contain pages of employee service
    - lms  contain pages of leave service
  store/   contains vuex store files to manage the state of app components.

  components/ contains imported files for rendering functionalities

     - service component  configure service implementation.
  
 nuxt.config.js/   contains app setting for asset builder to load and build.

  package.json/     contains defines app dependencies and start scripts commands.
