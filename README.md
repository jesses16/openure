Openure
================================
Openure exposes the internal variables of Backbone Views on a page.

Steps:
1. Expose your backbone app in a global variable and set that variable name in the Openure extension options at chrome://extensions/

2. CMND-SHIFT-click on a view and the 'view', 'model', 'collection' and 'options' variables will be available in the chrome console.

The following variables are defined in the interactive terminal.

* view - the view you clicked
* model - the model of the view, if there is one. Same as typing view.model
* collection - the collection of the view, if there is one.  Same as typing view.collection
* options - the options passed to the view.  Same as typing view.options

Example
-------------------------
You can change the model and call view.render(), or see the state of a view.

Why
-------------------------
It's a hassle to find and drill down into your views from the console.  Going back and adding clogs or debuggers isn't fun either.  Just click and get crazy.