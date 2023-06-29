
## Linting

Everyone has their own code style preferences, but there is one thing on which we can all agree: it is easier to 
both read and contribute to code that is consistent in style. Linters can help with this.

You can use `black` to lint your code. Out of the box, black provides sane defaults for linting. Then, you can use 
`isort` to order your import statements, ensuring consistency across your project.

When you run a linter for the first time, be sure to do so in a separate PR if your project has other 
contributors. Do not include any other code changes in such a PR. If your code has never been linted before, or 
was not linted in a while, you will end up with lots of changes that are hard for someone to review. Your PR will 
probably get rejected for this reason.

To help people comply with your project linting requirements, create a `Makefile` that includes a command to run 
the requisite commands to prepare code for review. Share guidance on how to use this command in your Contributing 
guidelines.
