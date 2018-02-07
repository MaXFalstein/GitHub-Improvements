# Repositories

## A few improvements GitHub could make to the repositories

### User profile pictures in miniature next to the file

The main three (default - configurable) contributors will feature to the left of the modification date.

This is toggled by keystroke and by a switch in the settings of the user.

This could be done with a JSON file in settings for all repositories.

[An example JSON file is given here](https://github.com/MaXwellFalstein/GitHub-Improvements/blob/master/Repositories/repo-contrib-pic.json).

#### Format

    "user/repo-name": {
        "default": "true",
        "toggled": "true"
    }

    "user/repo-name": {
        "default": "true",
        "toggled": "false"
    }

    "user/repo-name": {
        "default": "false",
        "toggled": "true"
    }

    "user/repo-name": {
        "default": "false",
        "toggled": "false"
    }

    "organisation/repo-name": {
        "default": "true",
        "toggled": "true"
    }

###### Format Examples

    "FalsteinInvestmentInc/Gist": {
        "default": "true",
        "toggled": "true"
    }

    "MaXSaxeDesign/Content-Delivery-Network": {
        "default": "true",
        "toggled": "true"
    }

    "MaXwellFalstein/Angular2.js": {
        "default": "true",
        "toggled": "true"
    }

#### JSON Hierarchy

    user default

    public-user/repo-name

    user/repo-name

###### JSON Hierarchy Example

    "user": {
        "default": "true",
    }

    "TryGhost/Ghost": {
        "default": "true",
        "toggled": "true"
    }

    "MaXwellFalstein/bootstrap": {
        "default": "true",
        "toggled": "true"
    }

---

### GitHub.com .md Troubles

GitHub.com see .md as GCC Machine Description, which does use the .md file format.

.md, along with .markdown, are the file formats for Markdown.

I would like GitHub.com to distringuish between .md for Markdown and .md for GCC Machine Description.

---

### Github.com Pull Requests

In the repository navigation bar, GitHub.com has ***Pull requests***, I think it should be ***Pull Requests***.

GitHub.com repository top line would look like:

| [<> Code](https://github.com/MaXwellFalstein/GitHub-Improvements) | [(!) Issues](https://github.com/MaXwellFalstein/GitHub-Improvements/Issues) | [Gists](https://github.com/MaXwellFalstein/GitHub-Improvements/tree/master/Gists) | [Pull Requests](https://github.com/MaXwellFalstein/GitHub-Improvements/tree/master/Pull-Requests) | [Wiki](https://github.com/MaXwellFalstein/GitHub-Improvements/wiki) | [Pulse](https://github.com/MaXwellFalstein/GitHub-Improvements/pulse) | [Graphs](https://github.com/MaXwellFalstein/GitHub-Improvements/graphs/contributors) | [Settings](https://github.com/MaXwellFalstein/GitHub-Improvements/settings) |


---
