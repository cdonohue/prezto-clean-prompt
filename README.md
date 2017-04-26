# prezto-clean-prompt

A two line prezto prompt that displays the current `nvm` `node` version and, when available, `git` information about the repo that you are currently working with.

![Clean prompt](https://github.com/cdonohue/prezto-clean-prompt/blob/master/screenshots/prompt.png)

## Features
- NodeJS version
- Git branch
- Git dirty changes
- Git commits behind
- Git commits ahead

This prompt takes advantage of symbols provided with [Nerd fonts](https://github.com/ryanoasis/nerd-fonts) (os icons and nodejs logo).

It looks best with a duotone color scheme. I've included an `iTerm` theme in the repo to make things easier on setting ANSI colors. If you use another terminal app, I'll list out the colors used in the above `iTerm` color theme.

- [iTerm](https://www.iterm2.com/)
- [Duotone iTerm color theme](https://github.com/cdonohue/prezto-clean-prompt/blob/master/Duotone%20Dark%20Space.itermcolors)

## Installation
1. Update your color theme. You can use the provided [iTerm color theme](https://github.com/cdonohue/prezto-clean-prompt/releases/download/1.0.0/Duotone.Dark.Space.itermcolors) or modify your terminal with the ANSI colors below

2. Clone to your external prezto prompts
```shell
git clone https://github.com/cdonohue/prezto-clean-prompt.git ~/.zprezto/modules/prompt/external/clean
```

3. Link the prompt
```shell
ln -s ~/.zprezto/modules/prompt/external/clean/prompt_clean_setup ~/.zprezto/modules/prompt/functions
```

4. Verify that you have the `git` module loading in your `.zpreztorc` file

![zpreztorc-git](https://github.com/cdonohue/prezto-clean-prompt/blob/master/screenshots/zpreztorc-git.png)

5. Update your `.zpreztorc` to use the `clean` prompt

![zpreztorc-prompt](https://github.com/cdonohue/prezto-clean-prompt/blob/master/screenshots/zpreztorc-prompt.png)

## Color configuration
#### Foreground: `#8686cb`

#### Background: `#24242e`

| Ansi color  |  Hex color |
|---|---|
| Black  |  `#49495a` |
| Red  |  `#fe7734` |
| Green  |  `#8686cb` |
| Yellow  |  `#fe7734` |
| Blue  |  `#bebeef` |
| Magenta  |  `#ff8b42` |
| Cyan  |  `#5b5b7b` |
| White  | `#d9d9e2`  |
| BrightBlack  | `#fe7734`  |
| BrightRed  | `#fe7734`  |
| BrightGreen  |  `#bebeef` |
| BrightYellow  | `#bf7c57` |
| BrightBlue  | `#bebeef`  |
| BrightMagenta  |  `#be7b55` |
| BrightCyan  | `#bdebe4`  |
| BrightWhite  |  `#f2f2f2` |

## License
> MIT License 2017 © Chad Donohue
