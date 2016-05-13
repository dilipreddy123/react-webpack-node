To add new pages to the project, I have

1. Created a new page in the containers (app/containers/ProductListing.jsx). This page is used as the UI. This returns Productlisting
2. Added a link in the Navigation.jsx (package: app/containers). This adds 'Product list' menu navigation bar. We need to define what the path is going to be when user performs a click action (/ProductListing)
3. We need to define a route for this path (/ProductListing). We need to edit the app/routes.jsx.
    a. import the container using "import Productlisting from 'containers/ProductListing';"
    b. Used the route tag to define the mapping for path to the component
