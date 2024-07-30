# healthcomplexweb
Repository of the Copenhagen Health Complexity website

## Pre-requisites

Install `Hugo`, `Go` and `NodeJS` using the [following guide](https://docs.gethugothemes.com/educenter/installation/).
Once installed open a terminal in the root folder of this project and run `hugo server`.

## To-do list

- [ ] Implemenent content folder structure
- [X] Ensure visual consitency in pages that are not the homepage (edit CSS files)
- [X] Fix the refenrencing to localhost
- [X] Remove DK support
- [X] Remove columns and links from the footer
- [X] Deploy to Netlify
- [x] Add web address and ensure https

## Content

- Home
- Research
  - Research themes
  - Publications
  - Public engagement
- Education
  - Courses
  - Student projects
- Community
  - People
  - Advisory group
  - Fellows
- About us
  - Mission
  - Values
  - Contact


## File structure

| Resources | Location |
| --- | ----------- |
| Main settings | `hugo.toml` |
|Images | `static/images` |
|Content | `content/` | 
|CSS files | `themes/educenter-hugp/assets/scss` | 
|Home website layout | `/data/en/homepage.yml` |


## Hugo resources

- https://gist.github.com/janert/4e22671044ffb06ee970b04709dd7d81
