# Contributing Guidelines

*Pull requests, bug reports, and all other forms of contribution are welcomed and highly encouraged!* :octocat:

This article explains how to contribute to **StephanusDai**.
Please read through the following guidelines.

> 👉 **Note**: before participating in our community, please read our
> [Code Of Conduct][code-of-conduct].
> By interacting with this repository, organization, or community you agree to
> abide by its terms.


**Here are some resources to help you get started with open source contributions:**

- [Community Guidelines](crown-community-guidelines)
- [Finding Good, Filing Bugs and Change Requests](#eyes-finding-good-filing-bugs-and-change-requests)
- [Asking Any Questions Support](#bulb-asking-any-questions-support)
- [Submitting and Reporting Security Issues](#inbox_tray-submitting-and-reporting-security-issues)
- [Bug Reports and Other Issues](#beetle-bug-reports-and-other-issues)
- [Submitting Pull Requests](#repeat-submitting-pull-requests)
- [Create Feature Requests](#love_letter-create-feature-requests)
- [Write Code Review](#white_check_mark-write-code-review)
- [Formatting Coding Style](#nail_care-formatting-coding-style)
- [Certificate of Origin](#medal_sports-certificate-of-origin)
- [Contrib with Under License](#memo-contrib-with-under-license)
- [Funds or Financial support](#rose-funds-or-financial-support)
- [Author and Credits](#pushpin-author-and-credits)

> **This guide serves to set clear expectations for everyone involved with the project so that we can improve it together while also creating a welcoming space for everyone to participate. Following these guidelines will help ensure a positive experience for contributors and maintainers.**

## :crown: Community Guidelines

Hi there! We're thrilled that you'd like to contribute to this project. Your help is essential for keeping it great.

Please review our [Code Of Conduct][code-of-conduct]. It is in effect at all times. We expect it to be honored by everyone who contributes to this project. Acting like an asshole will not be tolerated.

In this guide you will get an overview of the contribution workflow from opening an issue, creating a PR, reviewing, and merging the PR.

There’s several ways to contribute, not just by writing code.
If you have questions, see [Support][support] file.

## :eyes: Finding Good, Filing Bugs and Change Requests

> *Before spending lots of time on something, ask for feedback on your idea first!*

Please search issues and pull requests before adding something new to avoid duplicating
efforts and conversations.

This project welcomes non-code contributions, too! The following types of contributions
are welcome:

- **Ideas**: participate in an issue thread or start your own to have your voice heard.
- **Writing**: contribute your expertise in an area by helping expand the included docs.
- **Copy editing**: fix typos, clarify language, and improve the quality of the docs.
- **Formatting**: help keep docs easy to read with consistent formatting.

## :bulb: Asking Any Questions Support

See our [Support Guide][support]. In short, GitHub issues are not the appropriate place to debug your specific project, but should be reserved for filing bugs and feature requests.

## :inbox_tray: Submitting and Reporting Security Issues

To navigate our codebase with confidence, see [the introduction to working in the docs repository][working-repository] :confetti_ball:. For more information on how we write our markdown files, see [the GitHub Markdown reference][content-markup].

Check to see what [types of contributions][type-contrib] we accept before making changes. Some of them don't even require writing a single line of code :sparkles:.

- **Opening an Issue** Before [creating an issue][creating-issue], check if you are using the latest version of the project. If you are not up-to-date, see if updating fixes your issue first.

- **Reporting Security Issues** Review our [Security Policy][security]. *`Do not`* file a public issue for security vulnerabilities.
  
- **Triaging Issues** You can triage issues which may include reproducing bug reports or asking for additional information, such as version numbers or reproduction instructions. Any help you can provide to quickly resolve an issue is very much appreciated!

## :beetle: Bug Reports and Other Issues

A great way to contribute to the project is to send a detailed issue when you encounter a problem. We always appreciate a well-written, thorough bug report. :v:

In short, since you are most likely a developer, **provide a ticket that you would like to receive**.

- **Review the documentation and [Support Guide][support]** before opening a new issue.

- **Do not open a duplicate issue!** Search through existing issues to see if your issue has previously been reported. If your issue exists, comment with any additional information you have. You may simply note "I have this problem too", which helps prioritize the most common problems and requests. 

- **Prefer using [reactions][reactions]**, not comments, if you simply want to "+1" an existing issue.

- **Fully complete the provided issue template.** The bug report template requests all the information we need to quickly and efficiently address your issue. Be clear, concise, and descriptive. Provide as much information as you can, including steps to reproduce, stack traces, compiler errors, library versions, OS versions, and screenshots (if applicable).

- **Use [GitHub-flavored Markdown][flavored-mark].** Especially put code blocks and console outputs in backticks (```). This improves readability.


## :repeat: Submitting Pull Requests

We **love** pull requests! Before [forking the repo][fork-a-repo] and [creating a pull request][creating-pull-request] for non-trivial changes, it is usually best to first open an issue to discuss the changes, or discuss your intended approach for solving the problem in the comments for an existing issue.

For most contributions, after your first pull request is accepted and merged, you will be [invited to the project][invit-collab] and given **push access**. :tada:

*Note: All contributions will be licensed under the project's license.*

- **Smaller is better.** Submit **one** pull request per bug fix or feature. A pull request should contain isolated changes pertaining to a single bug fix or feature implementation. **Do not** refactor or reformat code that is unrelated to your change. It is better to **submit many small pull requests** rather than a single large one. Enormous pull requests will take enormous amounts of time to review, or may be rejected altogether. 

- **Coordinate bigger changes.** For large and non-trivial changes, open an issue to discuss a strategy with the maintainers. Otherwise, you risk doing a lot of work for nothing!

- **Prioritize understanding over cleverness.** Write code clearly and concisely. Remember that source code usually gets written once and read often. Ensure the code is clear to the reader. The purpose and logic should be obvious to a reasonably skilled developer, otherwise you should add a comment that explains it.

- **Follow existing coding style and conventions.** Keep your code consistent with the style, formatting, and conventions in the rest of the code base. When possible, these will be enforced with a linter. Consistency makes it easier to review and modify in the future.

- **Include test coverage.** Add unit tests or UI tests when possible. Follow existing patterns for implementing tests.

- **Update the example project** if one exists to exercise any new functionality you have added.

- **Add documentation.** Document your changes with code doc comments or in existing guides.

- **Update the CHANGELOG** for all enhancements and bug fixes. Include the corresponding issue number if one exists, and your GitHub username. (example: "- Fixed crash in profile view. #123 @jessesquires")

- **Use the repo's default branch.** Branch from and [submit your pull request][submit-pull-request] to the repo's default branch. Usually this is `main`, but it could be `dev`, `develop`, or `master`.

- **[Resolve any merge conflicts][resolving-merge]** that occur.

- **Promptly address any CI failures**. If your pull request fails to build or pass tests, please push another commit to fix it. 

- When writing comments, use properly constructed sentences, including punctuation.

- Use spaces, not tabs.

## :love_letter: Create Feature Requests

Feature requests are welcome! While we will consider all requests, we cannot guarantee your request will be accepted. We want to avoid [feature creep](https://en.wikipedia.org/wiki/Feature_creep). Your idea may be great, but also out-of-scope for the project. If accepted, we cannot make any commitments regarding the timeline for implementation and release. However, you are welcome to submit a pull request to help!

- **Do not open a duplicate feature request.** Search for existing feature requests first. If you find your feature (or one very similar) previously requested, comment on that issue.

- **Fully complete the provided issue template.** The feature request template asks for all necessary information for us to begin a productive conversation. 

- Be precise about the proposed outcome of the feature and how it relates to existing features. Include implementation details if possible.

## :white_check_mark: Write Code Review

- **Review the code, not the author.** Look for and suggest improvements without disparaging or insulting the author. Provide actionable feedback and explain your reasoning.

- **You are not your code.** When your code is critiqued, questioned, or constructively criticized, remember that you are not your code. Do not take code review personally.

- **Always do your best.** No one writes bugs on purpose. Do your best, and learn from your mistakes.

- Kindly note any violations to the guidelines specified in this document. 

## :nail_care: Formatting Coding Style

Consistency is the most important. Following the existing style, formatting, and naming conventions of the file you are modifying and of the overall project. Failure to do so will result in a prolonged review process that has to focus on updating the superficial aspects of your code, rather than improving its functionality and performance.

For example, if all private properties are prefixed with an underscore `_`, then new ones you add should be prefixed in the same way. Or, if methods are named using camelcase, like `thisIsMyNewMethod`, then do not diverge from that by writing `this_is_my_new_method`. You get the idea. If in doubt, please ask or search the codebase for something similar.

When possible, style and format will be enforced with a linter.

## :medal_sports: Certificate of Origin

*Developer's Certificate of Origin 1.1*

By making a contribution to this project, I certify that:

> 1. The contribution was created in whole or in part by me and I have the right to submit it under the open source license indicated in the file; or
> 1. The contribution is based upon previous work that, to the best of my knowledge, is covered under an appropriate open source license and I have the right under that license to submit that work with modifications, whether created in whole or in part by me, under the same open source license (unless I am permitted to submit under a different license), as indicated in the file; or
> 1. The contribution was provided directly to me by some other person who certified (1), (2) or (3) and I have not modified it.
> 1. I understand and agree that this project and the contribution are public and that a record of the contribution (including all personal information I submit with it, including my sign-off) is maintained indefinitely and may be redistributed consistent with this project or the open source license(s) involved.

## :memo: Contrib with Under License

> **Any contributions you make will be under the BSD Software License**
> 
> In short, when you submit changes, your submissions are understood to be under the same [**`BSD-3 Clause License`**][bsd] that covers the project. Feel free to contact the maintainers if that's a concern.
>

### License of All Free Open Sources

By contributing, you agree that your contributions will be licensed under its [**`BSD-3 Clause License`**][bsd].

### License of Official and User-contributed Documentation

The text contained in the official and user-contributed project documentation as stated as other content on project, except the license projects or documents themselves and as otherwise noted, is licensed under the [**`Creative Commons Attribution 4.0 International (CC-BY-4.0)`**][cc-by]. 

See [Support][support] for details.

## :rose: Funds or Financial support

I open-source almost everything I can and try to reply to everyone needing help using these projects. Obviously, this takes time. You can use this service for free.

If you are using this project and are happy with it or just want to encourage me to continue creating stuff, there are a few ways you can do it:

- Giving proper credit on the GitHub Sponsors page. [![Static Badge](https://img.shields.io/badge/%20Sponsor%20-gray.svg?colorA=EAEAEA&colorB=EAEAEA&style=fat&logo=githubsponsors&logoColor=EA4AAA)](https://github.com/sponsors/wiefunkdai)
- Starring and sharing the project :star:
- You can make one-time donations via PayPal. I'll probably buy a coffee :coffee: or tea :tea: or cake :cake: <br>
[![paypal.me/wiefunkdai](https://img.shields.io/badge/%20Donate%20Now%20-gray.svg?colorA=2C5364&colorB=0F2027&style=for-the-badge&logo=paypal&logoColor=white)](https://www.paypal.me/wiefunkdai)
- It’s also possible to support mine financially by becoming a backer or sponsor through<br>
[![opencollective.com/wiefunkdai](https://img.shields.io/badge/%20Donate%20Now%20-gray.svg?colorA=355C7D&colorB=2980B9&style=for-the-badge&logo=opencollective&logoColor=white)](https://www.opencollective.com/wiefunkdai)

However, I am available for hire. You can also give me career opportunities to help your business in developing the software you need. Please contact me at:<br>
[![wiefunk@stephanusdai.web.id](https://img.shields.io/badge/%20Send%20Mail%20-gray.svg?colorA=EA4335&colorB=93291E&style=for-the-badge&logo=gmail&logoColor=white)](mailto:wiefunk@stephanusdai.web.id)
[![linkedin.com/in/wiefunkdai](https://img.shields.io/badge/%20LinkedIn%20-gray.svg?colorA=005AA7&colorB=0083B0&style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/wiefunkdai)

## :pushpin: Author and Credits

Written by [@wiefunkdai][author] &lt;[stephanusdai.web.id][link]&gt;. 

**Please feel free to adopt this guide in your own projects. Fork it wholesale or remix it for your needs.**

*Many of the ideas and prose for the statements in this document were based on or inspired by work from the following communities:*

- [StandardJS](https://github.com/standard/.github/blob/master/CONTRIBUTING.md)
- [RemarkJs](https://github.com/remarkjs/.github/blob/main/contributing.md)
- [Linux](https://elinux.org/Developer_Certificate_Of_Origin)
- [JesseSquires](https://github.com/jessesquires/.github/blob/master/CONTRIBUTING.md)

*We commend them for their efforts to facilitate collaboration in their projects.*

## :pray: Thanks for your contribute and support! :heart_eyes: :heart:

> Any Questions & Other Supports? see [Support][support] please.

## Resources

*   [How to Contribute](https://opensource.guide/how-to-contribute)
*   [Finding ways to contribute](https://docs.github.com/en/get-started/exploring-projects-on-github/finding-ways-to-contribute-to-open-source-on-github)
*   [Set up Git](https://docs.github.com/en/get-started/quickstart/set-up-git)
*   [GitHub flow](https://docs.github.com/en/get-started/quickstart/github-flow)
*   [Collaborating with pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests)
*   [Using pull requests](https://help.github.com/articles/about-pull-requests/)
*   [The GitHub Markdown reference](https://github.com/github/docs/blob/main/contributing/content-markup-reference.md)
*   [GitHub help](https://help.github.com)


***

<p align="center">
    <a href="https://www.stephanusdai.web.id">Visit Website</a>
    ·
    <a href="https://github.com/wiefunkdai/.github/issues/new/choose">Global Issues</a>
    ·
    <a href="https://github.com/wiefunkdai/.github/discussions">Global Discussions</a>
    ·
    <a href="https://github.com/wiefunkdai/.github/wiki">Global Wiki</a>
</p>
<p align="center">
  Copyright &copy; ID 2023 Stephanus Bagus Saputra &#40;<a href="https://www.stephanusdai.web.id">www.stephanusdai.web.id</a>&#41;<br>
  All rights reserved.
</p>

<!-- Definitions -->

[author]: https://github.com/wiefunkdai

[link]: https://stephanusdai.web.id

[bsd]: https://github.com/wiefunkdai/.github/blob/main/LICENSE.md

[cc-by]: https://github.com/wiefunkdai/.github/blob/main/LICENSE.md

[code-of-conduct]: https://github.com/wiefunkdai/.github/blob/main/CODE_OF_CONDUCT.md

[support]: https://github.com/wiefunkdai/.github/blob/main/SUPPORT.md

[security]: https://github.com/wiefunkdai/.github/blob/main/SECURITY.md

[sponsor]: https://github.com/sponsors/wiefunkdai

[paypal]: https://www.paypal.me/wiefunkdai

[creating-issue]: https://help.github.com/en/github/managing-your-work-on-github/creating-an-issue

[reactions]: https://github.blog/2016-03-10-add-reactions-to-pull-requests-issues-and-comments/

[flavored-mark]: https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax

[fork-a-repo]: https://help.github.com/en/github/getting-started-with-github/fork-a-repo

[creating-pull-request]: https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/proposing-changes-to-your-work-with-pull-requests

[invit-collab]: https://help.github.com/en/github/setting-up-and-managing-your-github-user-account/inviting-collaborators-to-a-personal-repository

[submit-pull-request]: https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request-from-a-fork

[resolving-merge]: https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/resolving-a-merge-conflict-on-github

[working-repository]: https://github.com/github/docs/blob/main/contributing/working-in-docs-repository.md

[type-contrib]: https://github.com/github/docs/blob/main/contributing/types-of-contributions.md

[content-markup]: https://github.com/github/docs/blob/main/contributing/contributing/content-markup-reference.md
