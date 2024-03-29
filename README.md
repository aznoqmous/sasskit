# SASSKIT
## Project structure
```sh
sasskit / scss folder         
├── abstracts
│   ├── _animations.scss   # css animation + keyframes
│   ├── _classes.scss      # generic classes
│   ├── _fonts.scss        # fonts declarations
│   ├── _function.scss     # scss functions
│   ├── _mixins.scss       # scss mixins
│   └── _resets.scss       # basic css rules
│   └── _variables.scss    # global variables
├── _sasskit.scss          # library entrypoint
├── .gitignore             # speaks for itself
└── README.md              # this file
```
## How to use
`git clone` or download full project and put it inside your sass folder.

Import full lib like so :
```scss
@import 'sasskit';
// import your custom .scss files here
```

Set `main.scss` to be the entrypoint of your `SASS` compiler.

_Start to code !_

Feel free to edit which files are loaded by editing `_sasskit.scss`
