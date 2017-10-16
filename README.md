# JavaScript Frameworks
Javascript is the most popular language in the 2016 and it will continue to be favorite among the developer groups arround the globe.
following are the most popular Javascript Frameworks.
- Angular. js 
- Angular.js 2
- React.js
- Vue.js
-  Aurelia.js

Choosing framework could be a tedious task, it should be based on the project requirement and project structure, for example framework could be good for DOM manipulation or efficient UI rendering or some framework could be good at data handling and data manipulation. So depending upon nature of work Javascript Framework should be selected.
We will be discussing above mentioned frameworks on their nature and characteristics.
# I) Angular js 1.x
Angular 1.x is the baby of google but become Daddy of javascript frameworks.
Released in 2009.
Two way data-binding is core of the angular.
Most used js framework for SPA.
Sharing a list of some of the renowned web applications, which are powered with the flexible and robust Angular JS framework.
- The Guardian
- PayPal
- jetBlue
- Lego
- iStock Photo
- Upwork
- Netflix
- Freelancer
( courtesy Google )

# II) Angular 2 (Angular 4)
Angular js 1.x was realeased in 2009, it was almost 6 - 7 year old. At the time of development of angular framework mobile device were not that advance what we see now.
Angular 2 is best for its Speed, Performance and increadible tooling.
Angular 2 can be used with TypeScript and ES6 but it has wide support for TypeScript and official documentation and examples are built using TypeScript. Almost everything on the web related to angular 2 is built using typescript.
Following are the main feature of angular 2.

- Improved Dependency Injection (DI):
- Annotation
- Child Injectors
- Instance Scope 
- Directives 
     - Decorator Directives 
     - Component Directives
     - Template Directives
- Dynamic Loading
- Child Router
- Screen Activator
   -  canActivate
   - activate
   - canDeactivate
   - deactivate
   ( Same as in durandlejs )

> Angular 4 is smaller and faster as compared to its previous version.

Angular2 is built with TypeScript from Microsoft with eye to making JavaScript more agile and attractive for large enterprises. angular2 features a component-based architecture, improved dependency injection, efficient logging service, inter-component communications and more.
Angular 1 & 2, both are most preffred choice for developing enterprise-based applications with strict programming environments with high standard for code.
### why Angular 2 ( angular 4) ??
- TypeScript 
 > We can use ES6 Features + TS feature which provides great development support to the developer.
- Tooling
 > The tooling support is as good as on Java or .Net platforms
- Routers
 > Angular 2 provides great support for complex navigation scenarios in SPA.
- Annotations
- Observables
- Shadow DOM
- Active developer community support

# III) ReactJS
ReactJS is considered the fastest growing JS framework. Virtual DOM boost its performance comparing to angular 1.x.
ReactJs can be used with ES6.
ReactJS is maintained by the facebook. It has ability to perform good in SEO, JSX, Virtual DOM because of this it is obvious choice for dynmic and high traffice web applications.

When the data manipulation is much more dynamic and complex, client side DOM manipulations become performance intensive.

The React approach to handle this is –
- Render the DOM at server side, the virtual DOM.
- Compare virtual DOM to the browser/actual DOM and figure out differences.
- Update only the selective/changed nodes of browser DOM instead of re-rendering the entire DOM.

Another biggest advantage of react is the re-usability it brings on the table in the form of reactive components. React component libraries can be created and used across applications or made available for public use.
example http://www.material-ui.com/#/customization/themes
### Why React ??
- Fast Learning Curve
   > React is very a simple and lightweight library that only deals with the view layer. It is not big weapon linke other MV* framework such angular or ember. 
Any Javascript developer can start developing cool application after reading through tutorial and documentation.
- JSX 
    > React uses JSX, JSX is simple javascript which allows HTML quoting and uses these HTML tag syntax to render subcomponents. HTML systax is processed under hood of React.
- Virual DOM
    > Updating DOM is always expensive bussines as it directly affects performance of our application. React solves this problem by introducing Virtual DOM.
In React; a DOM is kept into the memory.
Any view changes are first reflected to virtual DOM, then an efficient diff algorithm compares the previous and current states of the virtual DOM and calculates the best way  to apply these changes. Finally those updates are applied to the DOM to ensure minimum read/write time. This is the main reason behind React’s high performance.
-  Flux and Redux
  > Flux is observer pattern modified a bit to fit into React.
-  Developer Tools
 > There are two great tools,  React Developer Tools and Redux Developer Tools. Both can be installed as Chrome extensions.

	
 # IV) Vue.js
 Vue 2.0 was also introduced in 2016 and it took the best from Ember, React and Angular, putting all that into a handy package. It is proved to be faster and leaner, comparing to React and Angular 2.0.
Going deeper, Vue.js offers two-way data binding (seen in AngularJS), server-side rendering (like in Angular2 and ReactJS), Vue-cli (scaffolding tool for quick start) and optional JSX support. Its founder states that Vue 2 is one of the fastest frameworks all in all.
Vue.js is a better choice for quick development of cross-platform solutions. It can become a firm basis for high-end single page applications (SPAs) and beneficial solution to those cases, when performance is put ahead of good code organization or app structure.
 - Comparison with Other Frameworks https://vuejs.org/v2/guide/comparison.html

### Why vue.js
- Lightweight
 >  Vuejs is only 21Kb download, smallest framework in the JS world.
- Components
> Everything in vuejs is component
-  Documentation 
> Nice documentation.  Vue.js comes really well documented; in fact, it probably has some of the best documentation.
link https://vuejs.org/

# V)  Aurelia.js
AureliaJS is the creation of Rob Eisenberg and team who come mostly from the world of Angular and Durandal. Aurelia though is an open source product is officially managed by Durandal Inc., a startup company that creates libraries, tools and frameworks to support next generation of web development.

Rob Eisenberg is moved to Microsoft.( Might Aurelia get adapted by MS )

# React Vs Angular1 Vs Angular 2

| Technology 	|  React 	| AngularJS  	|  Angular 2 	|
|:------:	|---	|---	|---	|
|    Author     	|   facebook	| google   	| goole   	|
|   Type     	|   Open source JS library	|  Fully-featured MVC framework 	| Fully-featured MVC framework  	|
|   Toolchain     	|   High	|  low 	|  High 	|
|     Language   	|   JSX	|   JavaScript, HTML	| TypeScript  	|
| Learning Curve       	| Low  	|  High 	|   Medium	|
|  Packaging      	|  Strong 	|  weak 	|  Medium 	|
|  Rendering      	| Server Side	  	|  Client Side	 	|  Server Side	 	|
|      App Architecture  	|  None, combined with Flux 	|  MVC 	|  Component-based 	|
|   Data Binding     	|  Uni-directional 	|  Bi-directional	 	|  Bi-directional	 	|
|  DOM      	|  Virtual DOM 	|   Regular DOM	|   Regular DOM	|


- Useful links
   - http://www.hexacta.com/2017/07/24/react-vs-angular2-which-technology-should-we-use/
    - http://blog.techmagic.co/angular-2-vs-react-what-to-chose-in-2017/
    - https://dzone.com/articles/difference-between-react-and-angular-2-does-angula
    - https://hackernoon.com/angular-vs-react-the-deal-breaker-7d76c04496bc
    - https://insights.stackoverflow.com/survey/2017#most-loved-dreaded-and-wanted

# Angular vs React vs Vue.js
   > *Angular, React and Vue.js are the top frontend framework. These framework are managed and maintained by well known organisations. These frameworks are also having great developer communities.
    * If we compared INDIA vs Rest, we can clearly see, India has highest usage of angularjs where as in rest of the world choose React.(Ref https://insights.stackoverflow.com/survey/2017#most-loved-dreaded-and-wanted )
    * Vue.js has picked many good things from React and Angular so we can say its nothing but combination of good parts of Angular +  React.
    * Learning curve is deep in Angular as compared to React or vue.js.
    * Resource availibility is good for these mentioned frameworks.
    * aurelia js's Commercial backing is not that strong as compared to Angular or React so number of active developer on the framework are very less.
    * Online developer community for aurelia js is not that strong as compared to Angular or React Or Vue.js
    * Resources are also less as compared to other framework.

```sh
          Prepared  by Ranjeet R Hange
```
