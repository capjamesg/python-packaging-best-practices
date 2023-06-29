### Project Documentation

READMEs are the first entry point for many developers to coding projects, but it should not be your only 
documentation. Long READMEs with extensive technical text and examples can become unwieldy and cause information 
overload. For documenting the full functionality of your project, and discussing specific topics in more depth, 
you should maintain external documentation.

Python documentation tools like mkdocs and sphinx create websites to host your project documentation. The 
advantage of using a documentation tool built with Python in mind is that these tools often offer extensions that 
work with your codebase. For example, you can use the `pydocstrings` module to use docstrings to generate 
documentation with `mkdocs`. Sphinx has a module for generating documentation from docstrings, too.

In your documentation, you should have:

1. Your README (you worked so hard on it, why not re-use it for your project home page?)
2. Links to important resources like your license, contributing guidelines, and code of conduct
3. Coverage for your codebase (optional, but preferred)

You should document all public functions and classes in your project. These functions should have:

1. Type hints
2. Clear, descriptive summaries
3. Documentation for what each function parameter does
4. Example usage, if relevant

You can include all of this information in your Python docstrings. If you do, this information will be consumed by 
more than just your documentation. For example, Visual Studio Code offers rich syntax highlighting based on some 
information in docstrings. When you hover over a function name in Visual Studio Code, the IDE shows the docstring 
information.

## Examples

- [supervision](https://roboflow.github.io/supervision/)
- [granary](https://granary.readthedocs.io/en/)