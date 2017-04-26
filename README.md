# prezto-clean-prompt

A two line prezto prompt that tells you what `nvm` `node` version your using and, when available, `git` information about the repo that you are currently working with.

## Features
- NodeJS version
- Git branch
- Git dirty changes
- Git commits behind
- Git commits ahead

This prompt takes advantage of symbols provided with [Nerd fonts](https://github.com/ryanoasis/nerd-fonts) (os icons and nodejs logo).

It looks best with a duotone color scheme. I've included an `iTerm` theme in the repo to make things easier on setting ANSI colors. If you use another terminal app, I'll list out the colors used in the above `iTerm` color theme.

- [iTerm](https://www.iterm2.com/)
- [Duotone iTerm color theme]()

## Installation
>Clone to your external prezto prompts
```shell
git clone https://github.com/cdonohue/prezto-clean-prompt.git ~/.zprezto/modules/prompt/external/clean
```

>Link the prompt
```shell
ln -s ~/.zprezto/modules/prompt/external/clean/prompt_clean_setup ~/.zprezto/modules/prompt/functions
```

>Update your `.zpreztorc` to use the `clean` prompt

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

