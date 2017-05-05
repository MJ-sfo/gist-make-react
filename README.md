Step one
npm in terminal for nodes you will need -
npm i -g create-react-app
npm run start

html doc - has div block with ID tag for rest of html to land in

index.js list CMDs that are needed - react, ReactDOM, maybe database (such as MongoDB)

outline boxes/components for your project
helps to have a scr folder for individual components
├──README.md
├──  favicon.ico
├──  index.html
├──  node_modules
├──  package.json
└──  src
    ├──  App.css
    ├──  App.js
    ├──  index.css
    ├──  index.js
    └──  logo.svg

each component is a class - doc needs links to dependent documents, and finish with a export line, for other documents to use. component/class 'Render' html 'props' (embedded with data) and 'states' that will end up on html page, then show on website

props has html and data, the data that will not change during calculations (immutable).  some data is mutable, and is stored in status variables that can be changes.  data that depends on one level component that will be moved to another level component will be bound (using .bind(this) ) to store the level 'this' that 'this' refers to.

css on project, and individual docs, on separate css files.

local components 'bubble-up' data components in props and status, up to parent component, which calculates data, makes changes in variables, and then 'bubble-down' the changes to smaller components.
