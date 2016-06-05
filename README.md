# NPM TypeScript Skeleton [![TypeScript](https://badges.frapsoft.com/typescript/code/typescript.png?v=100)](https://github.com/ellerbrock/typescript-badges/) [![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=102)](https://github.com/ellerbrock/open-source-badge/) [![Gitter Chat](https://badges.gitter.im/frapsoft/frapsoft.svg)](https://gitter.im/frapsoft/frapsoft/)

Getting Started to write NPM Modules in TypeScript.

# Todo

- create ShellScript for Project Setup

  # NPM Modules

`npm install -g typescript tslint typings` - install [TypeScript](https://github.com/Microsoft/TypeScript), [TSLint](https://github.com/palantir/tslint) and [Typings](https://github.com/typings/typings)

# IDE and Plugins

- [Atom](https://atom.io/) - A hackable text editor.
- [Atom TypeScript](https://atom.io/packages/atom-typescript) - The only TypeScript plugin you will ever need.
- [Atom Linter](https://atom.io/packages/linter) - A Base Linter with Cow Powers.
- [Atom Linter TSLint](https://atom.io/packages/linter-tslint) - Linter plugin for TypeScript, using tslint.

# tsconfig.json

- [tsconfig / typescriptlang](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html)
- [tsconfig / Schema](http://json.schemastore.org/tsconfig)

```
{
    "compileOnSave": true,
    "compilerOptions": {
        "module": "commonjs",
        "moduleResolution": "node",
        "target": "es5",
        "sourceMap": true,
        "removeComments": true,
        "declaration": true,
        "outDir": "./js",
        "noImplicitAny": false,
        "noLib": false,
        "pretty": true,
        "suppressImplicitAnyIndexErrors": true,
        "preserveConstEnums": true
    },
    "exclude": [
        "node_modules"
    ],
    "atom": {
        "rewriteTsconfig": true
    }
}
```

### Contact / Social Media

*Get the latest News about Web Development, Open Source, Tooling, Server & Security*

[![Twitter](https://github.frapsoft.com/social/twitter.png)](https://twitter.com/frapsoft/)
[![Facebook](https://github.frapsoft.com/social/facebook.png)](https://www.facebook.com/frapsoft/)
[![Google+](https://github.frapsoft.com/social/google-plus.png)](https://plus.google.com/116540931335841862774)
[![Gitter](https://github.frapsoft.com/social/gitter.png)](https://gitter.im/frapsoft/frapsoft/)
[![Github](https://github.frapsoft.com/social/github.png)](https://github.com/ellerbrock/)

### Development by 

Developer / Author: [Maik Ellerbrock](https://github.com/ellerbrock/)  
Company: [Frapsoft](https://github.com/frapsoft/)


### License 

Copyright (c) 2016 [Maik Ellerbrock](https://github.com/ellerbrock/)  

[![MIT Licence](https://badges.frapsoft.com/os/mit/mit-125x28.png?v=102)](https://opensource.org/licenses/mit-license.php)  

