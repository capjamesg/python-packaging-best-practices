
## Documentation

When I am working on a Python package, I like to ensure I have:

1. A well-written README;
2. Comprehensive documentation for public-facing functions in the codebase, and;
3. Auxillery information about the project (i.e. compatability, project organization, information if the package 
is part of a broader ecosystem).

What makes a well-written README? Good question!

### READMEs

My approach to READMEs is visual. What can I do to help make the project as approachable as possible? One 
structure I like to follow in READMEs, inspired by the `supervision` project, is:

1. Header image, if relevant
2. A 1-2 sentence introduction of the project
3. GitHub badges
4. Brief installation instructions [^1]
5. A quickstart, showing how to use key functions in the project
6. Community resources
7. Contributing information
8. Citation
9. License

I will talk about each of these in their own sections.

#### Header Image

A header image that is relevant to the project goes a long way to easing someone into a repository. If your 
repository helps someone build something visual (i.e. an image processing library, a web compoenent), an image 
showing the project in action is great.

#### Introduction

A short, snappy introduction to the project helps someone quickly evaluate if the repository is relevant to them. 
Here are some examples from projects on which I have worked:

- Autodistill uses big, slower foundation models to train small, faster supervised models. Using `autodistill`, 
you can go from unlabeled images to inference on a custom model running at the edge with no human intervention in 
between.
- **indieweb-utils** provides building blocks for people  implementing IndieWeb applications in Python. Discover 
IndieWeb  endpoints, find feeds on a page, infer page names, generate reply  contexts, and more!
- `mf2py` is a full-featured microformats2 (mf2) parser implemented in Python. mf2py implements the full mf2 
specification, including backward compatibility with microformats1.

#### GitHub Badges

GitHub badges visually convey useful information about your project. Some badges that may be relevant include:

1. PyPi release badge, linking to your project
2. Colab notebook (if relevant)
3. Version number
4. License
5. Any other relevant information (Arxiv link, CI failing / passing)

You should choose the badges that make sense to you. Sites useful for creating badges include:

1. ...

#### Brief Installation Instructions

Installation instructions should be concise. Use as little text as you need to explain how to install your 
project. If installation takes several steps, list each command. Separate commands with text explaining what each 
one does.

Be sure to note any device-specific installation instructions. Nest these under appropriate headings.

***Pro tip**: Enclose any build from source instructions in a HTML `<details>` block so they don't take up too 
much room, if you are publishing your README to a place that supports HTML parsing (i.e PyPi, GitHub).*

#### Quickstart

One of my favourite parts of a README is the Quickstart. This is the code that shows how your project works, at a 
high level.

The Quickstart is an opportunity for you to showcase a selection of the most useful functions in your library. 
Select up to three different code examples to share in the Quickstart, each nested under their own headings.

#### Community Resources

Have other people written articles or recorded videos about your project? Are there any examples from social media 
you want to share? This is the place to document them! Resources from third-parties on how to use your project, or 
resources you have complied yourself, all can be helpful someone who is new to your project.

#### Contributing Information

Contribution guidelines are essential for projects that want to accept external contributions. If this is you, 
allocate some time to write a `CONTRIBUTING.md` file, the file that outlines how people can contribute to your 
project.

Your contribution guidelines are a welcome message for people to contribute to your project. Use them to explain:

1. The philosophy behind your project, and how this relates to the scope of what the project should do.
2. How people can get started?
   1. Do you want them to file GitHub issues before a PR?
   2. How can people find out if something is already being worked on?
   3. Do contributors need to write test cases as part of their original commit, or after feedback has been given 
by a reviewer?
   4. Do you have any resources to share that could be helpful (i.e. a tutorial for adding a new module to the 
codebase)?
3. The code of conduct to which your project adheres. The [IndieWeb 
community](https://indieweb.org/code-of-conduct-examples) has a collection of many codes of conduct that can help 
you write one for your project. If you opt to write your own code of conduct, save it in a file called 
`CODE_OF_CONDUCT.md` in the main directory of your project.

#### Citation

Do you have a preferred way in which people can cite your project? Add it to your README! Optionally, create a 
`CITATION.cff` file that shares how you would prefer people to cite your work. GitHub parses these files and 
creates a human-readable interface with copy-paste examples for APA and BibTeX citations.

#### License

There are many materials online that discuss choosing a license. Allocate time to choose a license that matches 
your attribution desires, commercial requirements, and all of the other factors that are meaningful to you and 
your contributors. GitHub has more information on how to choose a project license. Ask fellow developers who have 
worked with open source licenses before if you have questions; do independent research to come to a conclusion.

Your license should be saved in a file called `LICENSE`.

## Examples

- [Autodistill](https://github.com/autodistill/autodistill)
- [supervision](https://github.com/roboflow/supervision)
- [mf2py](https://github.com/microformats/mf2py)