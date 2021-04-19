1. Create a new project, then navigate to the folder and:
* `ember serve`
* Visit your app at [http://localhost:4200](http://localhost:4200).
2. Added index.hbs, style it and added image to the images folder.
3. Added route to About page then create template for it.
4. A new custom path for contact page has been created.
5. Using <LinkTo> to navigate to Components.
6. Testing module added 
    ember g acceptance-test name
    http://localhost:7357/ to check
7. Creating a Component and refactor code in the templates to use id. {{yield}} keyword has been used to pass
    content into it.
8. Added test fot Components testing
    ember generate component-test component
9. Create nav-bar component and using it
10. Create application.hbs file as a starting point of app an pass rendering templates 
    by using {{outlet}} keyword, template refactoring
11. Creating Components using CLI and organizing code with Namespaced Components
    using ...attributes (allow to pass attributes when invoking component Component::HTML tag -> attributes)
        ex: rental component image insertion line:
        <Rental::Image
        src="https://upload.wikimedia.org/wikipedia/commons/c/cb/Crane_estate_(5).jpg"
        alt="A picture of Grand Old Mansion" />
    Adding tests for image Component
12. Create class for image component to add behavior and interactivity using @tracked and @actions decorators
        ember generate component-class componentName
    Modify component's template using conditionals {{if conditional}} {{else}} {{/if}} // see image.hbs for example
    FYI: this is important for accessibility reasons using correct semantic tags (ex: click event in the button tag)
    Adding test fot behavior testing
13. Creating component with component class js file (omitted by default)
        ember generate component componentName --with-component-class (ember g component map -gc)
    importing data from environment.js file 
    Working with map component to usage with Map image API, then add Map component with its attributes in rental template
14. Create route with @model to use it in component by @model directive {{@model}}, accessing properties from the  model:
    {{@model.property}}
15. Adding mock data in JSON format, fetch and return it in the model 
    and render with {{#each}} loop in template
16. Dynamic route implementation, adding route based on the id and create a different model to receive appropriate data based on ID.
17. Creating Detailed Component, did a markup with data from model accorded to individual object, then add this
    to template as <Rental::Detailed @rental={{@model}} />


