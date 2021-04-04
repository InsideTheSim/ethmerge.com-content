# ethmerge.com Content

This repo contains [Markdown](https://guides.github.com/features/mastering-markdown/) files that are fetched during the build process for
[ethmerge.com](https://ethmerge.com). Contributions are welcome in the form of Pull Requests. ❤️

I would **love** to see various authoritative voices in our community provide content for this project. My time (InsideTheSim) is best spent working on UI / UX challenges as the content accrues. Any help spreading the word about this project is greatly appreciated!

# Contributing
## Introduction
The introduction copy lives in the `/introduction.md` file at the root of the repo and is actiavely being worked on on the [`feature/intro`](https://github.com/InsideTheSim/ethmerge.com-content/tree/feature/intro) branch. See [this issue](https://github.com/InsideTheSim/ethmerge.com-content/issues/27) for discussion around drafting content for the Introduction.

## FAQs
### Existing FAQs
There are a number of pre-seeded FAQs to be worked on. Please check the open [Issues](https://github.com/InsideTheSim/ethmerge.com-content/issues) on the repo to see which questions have not yet been started / claimed by a community member before you begin your work.

Answers to questions shoud be opened as [Pull Requests](https://github.com/InsideTheSim/ethmerge.com-content/pulls) with the format: `Answer: "Name of the question here?"`

### New FAQs
To create a new FAQ create a new `.md` file in the `/faqs` directory using the structure provided in the `/faqs/_template.md` file. Do not modify the `_template.md` file directly.

The title of your FAQ `.md` file should generally be a kebab-case version of your FAQ question title.

In order to place your FAQ appropriately in the list use the `weight` property in the `.md` front-matter. The `weight` is a float value so if you want to put your FAQ immediately after a question that already exists you should:

- Open the `.md` file for the question that you wish to place your question after.
- Find the `weight` value for the question - let's say it's `5.0`.
- Add a weight of `5.1` to your own question.

If two files have the same weight defined then they will be sorted by creation date with the oldest file being listed first.

Please try to keep similar topic FAQs logically grouped together.

## Authorship
Anonymous authorship is acceptable - but given you'll need a GitHub account to contribute anyways please consider at least listing that if you're not comfortable linking your answer to a public internet profile such as Twitter or Reddit.

Questions can have multiple author attributions - and they'll be shown in order of contribution - not sorted by magnitude except in cases of extreme outliers. So, **just because a question has an answer please don't feel like you can't submit improvements to it!**

## Notice
Not all contributions are guaranteed to be merged - but all contributions are appreciated.
