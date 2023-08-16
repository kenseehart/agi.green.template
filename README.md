# agi.green.template
Template to deploy [`agi.green`](https://github.com/kenseehart/agi.green) as a submodule in your new AGI application repo. 

Keep in mind that `agi.green` is in very early development and is not stable as of August 2023.

Typical use case is a single page web app or local browser AI app centered around a markdown chat interface and a multi-pupose work area. Your app will be mostly python and almost no javascript, since `agi.green` provides python asynchronous control over the user interface. For example, you can implement plug-in tools that dynamically generate and modify UI content, usually in extended markdown format.

Your application is responsible for implementing the actual models. `agi.green` provides an interface to `gpt-4` through the openai API as an example. But [`HuggingFace`](https://huggingface.co/) is recommended as a place to look for the good stuff. 
