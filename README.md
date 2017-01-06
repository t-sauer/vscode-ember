# VSCode Ember

This is the Visual Studio Code plugin for the [Ember Language Server](https://github.com/emberwatch/ember-language-server).

This is currently under heavy development.  
To use this plugin clone this repository and the [Ember Language Server](https://github.com/emberwatch/ember-language-server) into the same directory.  

Afterwards :

```bash
cd ember-language-server
yarn
yarn link
cd ../vscode-ember
yarn
yarn link "ember-language-server"
code .
```

In the opened VSCode editor you can start a debugging session with the plugin enabled.
