# Twig for Nova (regex-based)

This extension for Nova, [a text editor from Panic](https://nova.app/), adds syntax highlighting for Twig, [a popular templating language](https://twig.symfony.com/). It supports all relevant language features from Twig 3.0+ and even some custom tags/filters from [Craft CMS](https://craftcms.com/) 3.0+.

This extension also includes a huge list of completions for Twig and Craft CMS 3.0+, including Element Queries.

**Please note:** When this plugin was released, syntax highlighting in Nova was regex-based. Starting with Nova 10, Panic migrated to Tree-sitter, a totally different form of syntax definitions. There are no plans to migrate this plugin to Tree-sitter, because it would require a full rewrite. However, this plugin will be supported until Panic decides to drop support for regex-based grammars altogether.

> With the introduction of Tree-sitter support in Nova 10, building new regex grammars is discouraged. Support will remain for the forseeable future for backward compatibility, but new features will be targeted exclusively at Tree-sitter.
> See: https://docs.nova.app/syntax-reference/regex-grammars/

## Installation

In Nova, go to “Extension > Extensions Library”, search for “Twig” and install the extension.

Manual way: Download this repository, extract the .zip file and open the folder with Nova.

If you use Twig inside Markdown files (e.g. Grav CMS): Map “.md” to “Twig-Markdown” in settings to activate syntax highlighting for Twig inside regular Markdown files.

## Development

Clone this repository and open the folder with Nova. In Nova, go to “Settings > General” and enable “Show extension development items in the Extension menu”. Then activate the extension via the “Extension” menu.

## Ideas for future development

- [ ] Migrate all syntax definitions and completions to Tree-sitter (Nova 10+)
- [ ] Restore subsyntax highlighting for `<script>`, `<style>`, `{% css %}` and `{% js %}` (requires migration to Tree-sitter)
- [ ] Update completions for Craft 4+
- [ ] Add support for matching Twig brackets (not possible at the moment?)

If you have some tips or want to help with development, feel free to let me know!
