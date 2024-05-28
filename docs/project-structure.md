```
public                # files that need to be publicly available, such as images, fonts, and other static files
|
src                   # source code for your application, including your JavaScript, CSS, and other assets
|
+-- app               # application layer containing:
|   |
|   +-- routes        # application routes / can also be called pages
    +-- app.jsx       # main application component
+-- assets            # assets folder can contain all the static files such as images that we are using inside our components
|
+-- components        # shared components used across the entire application
|   
+-- timer             # timer components folder
|   +-- Timer.jsx     # component file
    +-- Timer.css     # every component will have its corresponding css file 
|
+-- utils             # shared utility functions
```
