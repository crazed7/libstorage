# Contributing to libstorage

:+1::tada: First off, thanks for taking the time to contribute! :tada::+1:

The following is a set of guidelines for contributing to libstorage. 
These are mostly guidelines, not rules. 
Use your best judgment, and feel free to propose changes to this document in a pull request.

#### Table Of Contents

[How Can I Contribute?](#how-can-i-contribute)
  * [Reporting Bugs](#reporting-bugs)
  * [Suggesting Enhancements](#suggesting-enhancements)
  * [Your First Code Contribution](#your-first-code-contribution)
  * [Pull Requests](#pull-requests)
  
[Contributor License Agreement](#contributor-license-agreement)
## How Can I Contribute?

### Reporting Bugs

This section guides you through submitting a bug report for libstorage. 
Following these guidelines helps maintainers and the community understand your report :pencil:, 
reproduce the behavior :computer: :computer:, and find related reports :mag_right:.

Before creating bug reports, please check [this list](#before-submitting-a-bug-report) as you might 
find out that you don't need to create one. When you are creating a bug report, 
please [include as many details as possible](#how-do-i-submit-a-good-bug-report). 
Fill out [the required template](ISSUE_TEMPLATE.md), the information it asks for helps us resolve issues faster.

> **Note:** If you find a **Closed** issue that seems like it is the same thing that you're experiencing, 
open a new issue and include a link to the original issue in the body of your new one.

#### How Do I Submit A (Good) Bug Report?

Bugs are tracked as [GitHub issues](https://guides.github.com/features/issues/). 
After you've determined what your bug is related to, create an issue on that repository and 
provide the following information.

Explain the problem and include additional details to help maintainers reproduce the problem:

* **Use a clear and descriptive title** for the issue to identify the problem.
* **Describe the exact steps which reproduce the problem** in as many details as possible. 
For example, start by explaining how you started libstorage, e.g. which command exactly you used in the terminal, 
or how you started libstorage otherwise. When listing steps, **don't just say what you did, but explain how you did it**. 
* **Provide specific examples to demonstrate the steps**. Include links to files or GitHub projects, or 
copy/pasteable snippets, which you use in those examples. If you're providing snippets in the issue, 
use [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Describe the behavior you observed after following the steps** and point out what exactly is the problem with that 
behavior.

Provide more context by answering these questions:

* **Did the problem start happening recently** (e.g. after updating to a new version of libstorage) or was this always a problem?
* If the problem started happening recently, **can you reproduce the problem in an older version of libstorage?** What's 
the most recent version in which the problem doesn't happen? You can download older versions of libstorage 
from [the releases page](https://github.com/Comcast/libstorage/releases).
* **Can you reliably reproduce the issue?** If not, provide details about how often the problem happens and under which 
conditions it normally happens.

Include details about your configuration and environment:

* **Which version of libstorage are you using?**.
* **What's the name and version of the OS you're using**?

### Suggesting Enhancements

Enhancements are more than welcome.  Please submit an issue to track and a PR when ready for review.

### Your First Code Contribution

Unsure where to begin contributing to libstorage? You can start by looking through these `beginner` and `help-wanted` issues:

* [Beginner issues][beginner] - issues which should only require a few lines of code, and a test or two.
* [Help wanted issues][help-wanted] - issues which should be a bit more involved than `beginner` issues.


#### Local development

libstorage enhancements can be developed locally. For instructions on how to do this, see the following sections in the 
[Development Guide](https://github.com/Comcast/libstorage#to-start-developing-libstorage):

### Pull Requests

* Please run `rustfmt` over your code before submitting.  It is very helpful.
* Try to document complex functions when possible.  `cargo clippy` is also
very useful and it is highly suggested to run that against your code
before submitting your pull request.

## Contributor License Agreement

Before Comcast merges your code into the project you must sign the [Comcast Contributor License Agreement (CLA)](https://gist.github.com/ComcastOSS/a7b8933dd8e368535378cda25c92d19a).

If you haven't previously signed a Comcast CLA, you'll automatically be asked to when you open a pull request. Alternatively, we can send you a PDF that you can sign and scan back to us. Please create a new GitHub issue to request a PDF version of the CLA.
