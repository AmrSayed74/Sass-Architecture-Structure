# Sass-Architecture-Structure

```
sass/
|
|– base/
|   |– _reset.scss       # Reset ALl Elements
|   |- _container.scss   # Main Container For Layouts
|   |– _typography.scss  # Typography rules
|   |- _base.scss        # @forward All Files in base Folder
|   ...                  # Etc…
|
|– components/
|   |– _buttons.scss     # Buttons
|   |– _components.scss  # @forward All Files in components Folder
|   ...                  # Etc…
|
|– helpers/
|   |– _variables.scss   # Sass Variables
|   |– _functions.scss   # Sass Functions
|   |– _mixins.scss      # Sass Mixins
|   |– _breakPoints.scss # To make layouts Responsive
|   |– index.scss        # @forward All Files in helpers Folder
|   ...                  # Etc…
|
|– layout/
|   |– _header.scss      # Header
|   |– _navigation.scss  # Navigation
|   |– _grid.scss        # Grid system
|   |– _footer.scss      # Footer
|   |– _layout.scss      # @forward All Files in layout Folder
|   ...                  # Etc…
|
|– pages/
|   |– _homepage.scss    # Home specific styles
|   |– _contact.scss     # Contact specific styles
|   |– _about.scss       # Contact specific styles
|   |– pages.scss        # @forward All Files in pages Folder
|   ...                  # Etc…
|
|– vendors/
|   |– _bootstrap.scss   # Bootstrap
|   |– _fontawesome.scss # fontawesome Library
|   |– _normalize.scss   # normalize
|   ...                  # Etc…
|
`– main.scss             # Primary Sass file
```

Tip: You Can Also Add Theme Folder If You Have More Than One Theme As seventh Folder Of 1-7 Structure  
