# Contributing

First and foremost, thanks for the help, I appreciate all contributions, and the list wouldn't be nearly as complete without them.

## To add to the list:

### Submit a pull request.

* Descriptions should be clear, concise, and non-promotional.
* The list is split into sections for Lambda functions, Resources (like blog posts) and Frameworks, please add your entries to the appropriate sections.
* Descriptions should follow the link, on the same line, with capitalization consistent with the other entries in the section.
* Each entry should be a single line. This makes keeping the sections sorted easier. We let the GitHub formatter handle adding any required line breaks rather than embedding breaks in the lines ourselves.
* Each entry should be limited to one link, and that link should be the first part of the line. It is ok to submit more than one entry in a PR.
* If you're submitting a lambda, please try to make sure that the lambda repo has a good description and configuration howto so users don't have to clone it to figure out what it does and how to configure it.
* Please make sure all section list entries are sorted *alphabetically*.
* The link should be named the name of the package or project. If it starts with aws, trim that off so that **aws-fooo-lambda** would be linked with a title of **foo-lambda** so that all the entries don't cluster in the **A** section of the list.
* Your PR should pass the Travis checks. If the travis checks show an error that you didn't add (a previous entry has gone 404, for example) you don't _have_ to fix those errors, though I'll appreciate the help if you do.
* It is fine to have multiple new entries in a single PR.
* No need to squash commits. It is fine to have multiple commits in a PR.

## To remove an entry:

Open an issue to discuss why the entry should be removed, and optionally create a PR.
