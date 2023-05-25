# Welcome to :tomato: Crealgo's GitHub

Below you'll find information regarding the repositories in this organization. Happy coding!

## Naming Structure

We'll follow a pretty simple naming structure that begins with the client/company name and, after each hyphen, provides another descriptor about the project. The basic naming convention is as follows: 

1. {{ CLIENT NAME }} : optional - if the project does not have an associated client, skip to 2
2. {{ PROJECT NAME }}
3. {{ PROJECT PART }} : let's the the project has 3 parts, frontend, wordpress, and api - these would be 3 separat repositories.
4. {{ PROJECT SUB - PART }} : a `wordpress` can have several sub parts to it: `plugin`

Some other conventions are:
- `static` as a PROJECT PART, should be used for **rendered, public repositories ONLY**. This word indicates that it will be used with github pages and to show the word. Anything that follows `static` should be conisidered either a (1) subdomain if using a CNAME or a sub-part of the of the project. Examples:
  - `crealgo-static-home` or `creaglo-static`    --> CNAME is crealgo.com
  - `crealgo-static-projects`                    --> CNAME is projects.crealgo.com
  - `crealgo-static-create`                      --> CNAME is create.crealgo.com

Below are good examples of existing repositories that follow this naming structure.

```
hydra-library-react
hydra-library-webcomponents
danafarber-library-webcomponents
fomm-wordpress-plugin-blocks
fomm-wordpress-theme
```
