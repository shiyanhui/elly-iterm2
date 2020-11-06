## elly-iterm2

*elly-iterm2* is a nostalgic and brown-based iTerm2 color theme.

<img alt="elly iterm2" src="https://user-images.githubusercontent.com/41639488/98157819-3f36ca00-1f1d-11eb-962c-17f33996bd48.png">

<img alt="elly.vim" src="https://user-images.githubusercontent.com/41639488/98123673-814c1580-1ef5-11eb-8520-06af6404e738.png">

<img alt="elly.vim" src="https://user-images.githubusercontent.com/41639488/98116862-3d084780-1eec-11eb-9d3c-6937554cb285.png">

## Installation

1. open iTerm > `Preferences` > `Profiles` > `Colors` Tab
2. Open the `Color Presets...` drop-down in the bottom right corner
3. Select `Import...` from the list
4. Select the `elly.itermcolors` file
5. Select the `elly` from `Color Presets...`

## Issues
This theme is in early development. If you find some bugs, please submit a issue.

## Related Projects
- https://github.com/ryuta69/elly.vim

## [Tips] elly theme for powerlevel10k

```zsh
typeset -g POWERLEVEL9K_DIR_FOREGROUND=12
typeset -g POWERLEVEL9K_DIR_ANCHOR_FOREGROUND=4
typeset -g POWERLEVEL9K_DIR_SHORTENED_FOREGROUND=4
typeset -g POWERLEVEL9K_PROMPT_CHAR_OK_{VIINS,VICMD,VIVIS,VIOWR}_FOREGROUND=12
typeset -g POWERLEVEL9K_PROMPT_CHAR_ERROR_{VIINS,VICMD,VIVIS,VIOWR}_FOREGROUND=88

local      clean='%9F'
local   modified='%58F'
local  untracked='%6F'
local conflicted='%88F'
```
