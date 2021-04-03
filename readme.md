# ethmerge.com Content

This repo contains [Markdown](https://guides.github.com/features/mastering-markdown/) files that are fetched during the build process for
[ethmerge.com](https://ethmerge.com). Contributions are welcome in the form of Pull Requests. ❤️

# Contributing
The introduction copy lives in the `/introduction.md` file at the root of the repo.

To create a new FAQ simply create a new `.md` file in the `/faqs` directory using the structure provided in the `/faqs/_template.md` file. Do not modify the `_template.md` file directly.

The title of your FAQ `.md` file should generally be a kebab-case version of your FAQ question title.

In order to place your FAQ appropriately in the list use the `weight` property in the `.md` front-matter. The `weight` is a float value so if you want to put your FAQ immediately after a question that already exists you should:

- Open the `.md` file for the question that you wish to place your question after.
- Find the `weight` value for the question - let's say it's `5.0`.
- Add a weight of `5.1` to your own question.

If two files have the same weight defined then they will be sorted by creation date with the oldest file being listed first.

Please try to keep similar topic FAQs logically grouped together.

Not all contributions are guaranteed to be merged - but all contribution are appreciated.