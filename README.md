# Portfolio Template

This is a Jekyll website template designed for Prep Fellows.


## Make your own!

1. Use the Template button.
2. Update `_config.yml` to contain your information.
    1. Change `url` to the URL you'll be hosting it at
    2. Make sure it has the /
3. Use something like Netlify or GitHub Pages to deploy (note, this only works on username.github.io, not username.github.io/repo-name)

## Add your portfolio

Head to `_data` and fill out either `projects.yml`, `experience.yml` and `education.yml`.

Project example.
```yaml
- title: Online Shopping Application
  event: MLH Prep - Batch 4.5
  date: Fall 2021
```

Experience example.
```yaml
- role: MLH Prep Fellow
  company: MLH Fellowship
  dates: Summer 2021
  logo: fellowship.svg
```

Education example.
```yaml
- course: Prep Fellow
  institute: MLH Fellowship
  dates: Fall 2021
  logo: fellowship.svg
```
## Add project posts

1. Make a new `.md` file inside of `projects`.
2. Add the header to your markdown file (see below) and change the title to the name of your blog post.
3. Write your project page! Can be a README from GitHub or your Devpost page.
4. Add the `page-name` field to your `projects.yml` (see below).

Top of post markdown file post.
```
---
title: Project
layout: page
---
```

`projects.yml` with the `page-name` field.

```yaml
- title: Online Shopping Application
  event: MLH Prep - Batch 4.5
  date: Summer 2021
  page-name: project
```

## Development

If you want to test it locally or add some new features, run the below commands. Make sure to have Ruby and Bundler installed.

```
bundle install --path vendor/bundle
bundle exec jekyll serve
```
