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

