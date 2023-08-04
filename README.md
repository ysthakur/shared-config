# shared-config

- `my_prompt_theme.omp.json` - Needs to be shared by Windows and WSL, so has to be in a public repo
  - Edit here instead of locally since it'll be overwritten.
  - [Chezmoi docs](https://www.chezmoi.io/user-guide/include-files-from-elsewhere/#include-a-single-file-from-a-url) on external files
  - Use `chezmoi -R apply` (`-R` is `--refresh-externals`) to update
