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
├── main.scss              # your freshsly created file
├── .gitignore             # speaks for itself
└── README.md              # this file
```
## How to use
`git clone` or download full project and put it inside your sass folder.

Create a `main.scss` inside the project folder like so :
```scss
@import 'sasskit';
// import your custom .scss files here
```

Set `main.scss` to be the entrypoint of your `SASS` compiler.

Start to code !
