# gh-merge-commits-outline
A GitHub CLI extension that extracts merge commits from a specified pull request and lists them in the pull request description.

## Features

- Extracts all merge commits from a specified pull request
- Updates the pull request description with an outline of merge commits
- Displays each merge commit with its associated PR description in a collapsible format

## Installation

Make sure you have the [GitHub CLI](https://cli.github.com/) installed.

Install the extension:

```sh
gh extension install t4y3/gh-merge-commits-outline
```

## Usage

```sh
gh merge-commits-outline PR_NUMBER
```

Replace `PR_NUMBER` with the target pull request number.

## Example

If you have a pull request with the number `123`:

```sh
gh merge-commits-outline 123
```

The extension will extract all merge commits from pull request #123 and update its description with an outline of the merge commits.

## License

[MIT](LICENSE)
