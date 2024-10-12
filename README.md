# Zsh Aliases

A collection of custom Zsh aliases to make command-line life easier.

## Content

This repository includes the following aliases:

- **Code Editor**

  - `code`: Launch Visual Studio Code Insiders
  - `code-sw`: Launch Visual Studio Code Insiders reusing the window

- **Git**

  - `gcm`: `git commit -m` - Commit changes with a message
  - `gcl`: `git clone` - Clone a repository
  - `gpl`: `git pull` - Fetch and merge changes from a remote repository
  - `gph`: `git push` - Push changes to the remote repository
  - `gad`: `git add` - Add files to the commit
  - `gck`: `git checkout` - Switch branches
  - `gmr`: `git merge` - Merge a branch

- **pnpm**

  - `pm`: `pnpm` - Pnpm package manager
  - `pma`: `pnpm add` - Add a package
  - `pmr`: `pnpm remove` - Remove a package
  - `pmi`: `pnpm install` - Install packages

- **Utility**
  - `cl`: `clear` - Clear the terminal
  - `mk`: `make` - Execute a make command

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/pietrodev07/zsh-aliases.git
   ```

2. Add the aliases to your `.zshrc` or `aliases.zsh` file:

   ```bash
   # For .zshrc
   echo "source /path/to/zsh-aliases/aliases.zsh" >> ~/.zshrc

   # Or copy and paste the aliases directly
   cat zsh-aliases/aliases.zsh >> ~/.zshrc
   ```

3. Reload your Zsh configuration:
   ```bash
   source ~/.zshrc
   ```

## Contributing

If you would like to contribute to this project, feel free to submit a pull request. Any suggestions and improvements are welcome!

## License

This project is licensed under the [MIT](LICENSE) license.
