# jsonresume-theme-onepage

A compact theme for JSON Resume, designed for printing. 

Tries to fit as much information as possible onto a single page without making sections look cluttered.

## Example

http://themes.jsonresume.org/theme/onepage

## Running

1. Run local server:
    ```
    yarn global add resume-cli
    resume serve
    ```

1. Print directly from the served html.

## Options

### Themes

Or you can set the default theme for your resume on the registry by using the --theme option in the CLI tool e.g.

`resume publish --theme flat`

### Sections

For the "experience" and "skills" sections, you can optionally replace the "highlights" list with a "details" list with this format:

```
"details": [
  { "text": "Javascript", "comment": "expert" },
  { "text": "Coffeescript", "comment": "expert" },
  { "text": "Ruby", "comment": "competent" },
  { "text": "Java", "comment": "novice" }
]
```

See included resume.json for more details.

