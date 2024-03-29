## Version 1.8.2

- Fix: Re-add support for HTML completions for compatibility with Nova 10+.

## Version 1.8.1

- Add support for modifiers (e.g. `at head`) on fenced code blocks (`{% css %}` and `{% js %}`)

## Version 1.8

- Add support for nested syntax highlighting inside `{% css %}` and `{% js %}` (Craft CMS)

## Version 1.7

- Add optional `Twig-Markdown` syntax definition: Map “.md” to “Twig-Markdown” in settings to activate syntax highlighting for Twig inside Markdown files (Grav CMS).

## Version 1.6

- Add completions for Craft Element Queries and common properties

## Version 1.5

- Add completions without closing tags
- Fix: Don’t show completions right before `%}`

## Version 1.4.1

- Fix: Don’t show syntax highlighting inside comments

## Version 1.4

- Add symbols for macro definitions
- Add completions for variables and macros defined in the same file
- Add completions for argument lists

## Version 1.3

- Add basic tag completions for Twig-HTML (outside opening brackets)
- Fix: correct end tag for `autoescape` completion
- Fix: correct syntax highlighting for blocks and variables named like keywords

## Version 1.2

- Auto insert `%}` after tags in completions
- Auto insert `{% endif %}`, `{% endfor %}` etc. in tag completions
- Auto insert space after function calls in completions
- Improve context for completions
- Remove matching `{}` from Twig-HTML syntax

## Version 1.1

- Completions for Craft CMS 3.0+
- Better Syntax Highlighting for Craft CMS 3.0+
- Better Icon

## Version 1.0

Initial release

- Syntax Highlighting for Twig 3.0+
- Syntax Highlighting for custom tags/filters from Craft CMS 3.0+
- Completions for Twig 3.0+
