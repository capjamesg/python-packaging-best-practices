# Best Practices for Packaging Python Projects

I have contributed to numerous Python packages over the last few months, from a package to use foundation vision 
models to train smaller models to a small package for computing word surprisals. When I am working on packages, I 
ask myself the question "what can I do to make the developer experience as seamless as possible?"

Strong documentation and package organization is an excellent long-term investment. The more comprehensive and 
intuitive your documentation is, the easier it is for people to use the library. Notably, good documentation makes 
the lives of all maintainers (and future maintainers!) easier. Robust documentation makes it easier to navigate 
and use a codebase, and helps to build a shared understanding around the structure of a codebase.

There are a few tips I have picked up while working on packaging Python projects that I want to share. In this 
article, I share the tasks, questions, and thoughts that come to mind when I am preparing to launch a Python 
project. I cover everything from documentation to CI integrations to code style.