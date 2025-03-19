<div align="center">
  <a href="https://www.github.com/"><img src="https://github.com/devicons/devicon/blob/master/icons/github/github-original-wordmark.svg" title="GitHub" alt="GitHub" width="64" height="64"></a>
</div>

## :book: Documentation

Further reading: https://docs.github.com/

## Keyboard & Mouse Shortcuts

| Function                                                   | Shortcut              |
| ---------------------------------------------------------- | --------------------- |
| Opens a repository or pull request in the web-based editor | `.`                   |
| Focus the search bar                                       | `S` or `/`            |
| Open blame view                                            | `B`                   |
| Activate file finder                                       | `T`                   |
| Goto line                                                  | `L`                   |
| Paste                                                      | `Middle Mouse Button` |
| Delete word                                                | `Ctrl + Backspace`    |

Further reading: https://docs.github.com/en/get-started/using-github/keyboard-shortcuts

## Co-author

```git
commit message

Co-authored-by: John Doe <johndoe@email.com>
```

Further reading:

- [GitHub Docs](https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/creating-a-commit-with-multiple-authors)
- [GitHub Blog Article](https://github.blog/2018-01-29-commit-together-with-co-authors/)

## GPG Key Setup

### Windows

1. Download and install GnuPG from https://gnupg.org/download/index.html
2. Generate a new GPG key by running `gpg --full-generate-key` in the command line
3. :warning: **Important**: Make sure to use the same email address as your GitHub account
4. List your GPG keys by running `gpg --list-secret-keys --keyid-format LONG`
5. Copy the GPG key ID
6. Add the GPG key to your GitHub account by running `gpg --armor --export <GPG_KEY_ID>`
7. Copy the GPG key and paste it into your GitHub account settings starting with and including `-----BEGIN PGP PUBLIC KEY BLOCK-----` and ending with `-----END PGP PUBLIC KEY BLOCK-----`
8. Configure Git about your GPG key by running `git config --global user.signingkey <GPG_KEY_ID>`

Further reading:

- [GitHub Docs - Generating a new GPG key](https://docs.github.com/en/authentication/managing-commit-signature-verification/generating-a-new-gpg-key)
