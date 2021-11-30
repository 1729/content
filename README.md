# The Network State

## Building Slides

We use [marp.app](https://marp.app/) for generating slides from
markdown. Here's how to build the slides for a given lecture.

```bash
git clone git@github.com:1729/content.git
cd content/000-summary
npm i @marp-team/marp-cli
marp --allow-local-files --pdf summary-slides.md
```
