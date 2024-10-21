# healthcomplexweb
Repository of the Copenhagen Health Complexity website

## Pre-requisites

Install `Hugo`, `Go` and `NodeJS` using the [following guide](https://docs.gethugothemes.com/educenter/installation/).
Once installed open a terminal in the root folder of this project and run `hugo server`.

## To-do list

- [X] Fix list of courses in the homepage
- [ ] Fix bug when accessing the people page (it requires refreshing the page)
- [ ] Reduce resolution of people images
- [ ] Fix bug in navigation bar in the phone version
- [ ] Add animation in the background of the homepage e.g center video as animation
- [ ] Add a search bar
- [ ] Embbed video in the homepage

## Content

- Home
- Research
  - Research themes
  - Publications
  - Public engagement
  - Opinions
- Education
  - Courses
  - Student projects
- Community
  - People
  - Advisory group
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
|CSS files | `assets/scss` | 
|Home website layout | `/data/en/homepage.yml` |
|Html templates | `/layouts/` |

# Layouts


## Hugo resources

- https://gist.github.com/janert/4e22671044ffb06ee970b04709dd7d81
