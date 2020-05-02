# Angular-basics
### What is Angular App?
- Angular App is set of ngModules, ngModules provided the compilation context for components.
- An app has atlease one module for bootstraping and others for features reqired.
- there is a router navigation service used to navigate between views. It provides good in-browser navigation capabilties 
### WHat are Angular components ?
- Components can be view elements of you app, which Angular chosses and can chaneg according to logic and data.
- Components can  be services which has logic not related to rendering of component, It can be injected in diferent components as dependencies. Which help in modular, reusable and efficient code.
### What are decorators?
Above mentioned components service and View components are classes, decorators are the mata data used in compeonents so that they can be used. For Eg.
- For view components decorator @Component is used as with metadata like the templete (HTML), selector (name used to call component) and styleUrls(CSS files) .
- For services id defined by using @Injectable as decorator. 

## Component life cycle:
Following are the angular lifecycle hooks available in Angular:
| lifecycle method Hook | Desc |
|------|------|
|ngOnChanges()| When ever input properties are (re)set, the method supply SimpleChanges instance which provide value and changed value. Its called before ngOnInit() |
|ngOnInit()|its called first time when all  properties are displayed and directives/component are initalized. its called after ngOnchanges()|
|ngDoCheck()|its called to check if there is any change in vew and component|
|ngDoContentInit()|Responds after enternal content is projectected in component or directive |
|ngDoContentCheck()|Check for content check|
|ngDoViewInit()|Respond when activates component view and child view which a derective is in |
|ngDoViewCheck()|Check for changes in the view , child view |
|ngonDestroy|Do clean up when component is closed , unsubcribe obsrverables and detach event handler.|




