# SourceLevel - Linters

## Code Quality & Analytics for Engineering Teams

Increase visibility, collaborativity, and efficiency in your teams with
[SourceLevel](https://sourcelevel.io).

SourceLevel runs more than
[30 different engines and supports lots of programming languages](https://docs.sourcelevel.io/engines).
It can comment straight into Pull Requests the found issues, so your team can easily spot and fix them.
In adittion, we show charts showing your code health, so you can follow its improvement over time.

## About this Styleguide

This is the default Styleguide repository for SourceLevel!

Styleguide repositories are a way to share engine configuration files across multiple repositories
without replicating these files on each codebase, you can learn more information in
[our docs](https://docs.sourcelevel.io/guides/repos/using-a-styleguide/)

If you're looking for `latest` configs for [channel configuration](https://docs.sourcelevel.io/configuration/#channels)
you can check [`latest` branch](https://github.com/sourcelevel/linters/tree/latest).

Here you can find a curated styleguide for a collection of configuration files we
use for source code linters and static analysis tools:

| Programming Language | Linter                                                     | Config file                      |
|----------------------|------------------------------------------------------------|----------------------------------|
| Elixir               | [Credo](https://docs.sourcelevel.io/engines/credo)         | [.credo.exs](.credo.exs)         |
| JavaScript           | [ESLint](https://docs.sourcelevel.io/engines/eslint)       | [.eslintrc.js](.eslintrc.js)     |
| Markdown             | [Remark](https://docs.sourcelevel.io/engines/remark-lint)  | [.remarkrc](.remarkrc)           |
| Ruby                 | [Reek](https://docs.sourcelevel.io/engines/reek)           | [.defaults.reek](.defaults.reek) |
| Ruby                 | [Rubocop](https://docs.sourcelevel.io/engines/rubocop)     | [.rubocop.yml](.rubocop.yml)     |
| SCSS                 | [SCSS Lint](https://docs.sourcelevel.io/engines/scss-lint) | [.scss-lint.yml](.scss-lint.yml) |
