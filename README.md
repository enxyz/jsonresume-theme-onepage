# jsonresume-theme-onepage

A compact theme for JSON Resume, designed for printing. 

Tries to fit as much information as possible onto a single page without making sections look cluttered.

## Usage

1. Edit with local server (note that restart needed for changes to `resume.hbs`):

    ```
    resume serve --theme .
    ```

1. Export file. See https://github.com/jsonresume/resume-cli#resume-export-filename

## Options

## Themes

Or you can set the default theme for your resume on the registry by using the --theme option in the CLI tool e.g. Anything on this page can be called with an option: https://jsonresume.org/themes/

`resume publish --theme flat`

Recommended themes:
- Software: https://themes.jsonresume.org/theme/spartan
- Traditional: https://themes.jsonresume.org/theme/onepage
- https://themes.jsonresume.org/theme/class

## Sections

For the "experience" and "skills" sections, you can optionally replace the "highlights" list with a "details" list with this format:

```
"details": [
  { "text": "Javascript", "comment": "expert" },
  { "text": "Coffeescript", "comment": "expert" },
  { "text": "Ruby", "comment": "competent" },
  { "text": "Java", "comment": "novice" }
]
```

## Creating

Community Chrome extension to import your LinkedIn Profile.

https://chrome.google.com/webstore/detail/json-resume-exporter/caobgmmcpklomkcckaenhjlokpmfbdec/related

## Setup

Insall cli:

```sh
yarn global add resume-cli
```