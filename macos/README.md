## [macOS Configuration](https://ivelasq.rbind.io/blog/macos-rig/)

1. Install [Homebrew](https://brew.sh/).

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

2. Install [Git](https://git-scm.com/download/mac).

```bash
brew install git
```

3. Configure [global Git settings](https://github.com/gvelasq/git-reference#setup).

```bash
git config --global user.name "Patrick Hogan"
git config --global user.email "pmhogan@users.noreply.github.com"
```

4. Install [zsh](https://zsh.sourceforge.io/).

```bash
brew install zsh
```

5. Install [oh-my-zsh](https://ohmyz.sh/#install).

```bash
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

6. Configure [oh-my-zsh](https://github.com/pmhogan/dotfiles/tree/main/zsh).

7. Install [rig](https://github.com/r-lib/rig#macos-homebrew).

```bash
brew tap r-lib/rig
brew install --cask rig
```

8. Install [R](https://www.r-project.org/).

```bash
rig add release
```

9. Install [RStudio Desktop](https://posit.co/download/rstudio-desktop/).

```bash
brew install --cask rstudio
```

10. [Configure .Rprofile](https://github.com/pmhogan/dotfiles/blob/main/R/.Rprofile).

```r
usethis::edit_r_profile()
```

11. [Configure RStudio](https://github.com/pmhogan/dotfiles/tree/main/rstudio).

12. Create a [GitHub PAT](https://usethis.r-lib.org/reference/github-token.html).

```r
usethis::create_github_token()
```

13. Set [Git credentials](https://gitcreds.r-lib.org/reference/gitcreds_get.html).

```r
gitcreds::gitcreds_set()
```

14. Install [Quarto](https://quarto.org/docs/get-started/) if RStudio < `v.2022.07`.

```bash
brew install --cask quarto
```

15. Install [htop](https://htop.dev)

```bash
brew install htop
```