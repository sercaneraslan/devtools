<h1 align="center">💻 Terminal</h1>

<p align="center">
I prefer <a href="https://iterm2.com">iTerm2</a> as a terminal and <a href="https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH">Oh My ZSH</a> as a shell.
</p>

## 🎨 Themes

I prefer `robbyrussell` theme which is default.

How do I change my theme?

* Open the .zshrc file: `vim ~/.zshrc`
* Find the `ZSH_THEME="robbyrussell"` line, change it and save it.
* Execute the .zshrc file: `. ~/.zshrc`
* Close your terminal and open it again if it necessary.

## 🫶 Aliases
You can find my aliases below, which I use often.

```
alias b='git branch'
alias bb='git checkout -'
alias c='git checkout'
alias ci='git commit -am'
alias cx='clear'
alias d='git diff master -w --color'
alias dd='git diff'
alias ff='git ls-files |grep '
alias ga='git add .'
alias g='git grep'
alias l='git log -p'
alias m='git checkout master'
alias mm='git merge master'
alias mb='git merge'
alias n='git diff master --name-only'
alias p='git pull'
alias pp='git push'
alias rst='git reset --hard'
alias s='git status'
alias sl='git shortlog -s'
alias sln='git shortlog -s -n'
alias st='git stash'
alias sp='git stash pop'

alias ni='npm install'
alias ns='npm run start'
alias nb='npm run build'
alias yi='yarn install'
alias ys='yarn start'
alias yb='yarn build'

alias v='vim'
alias ss="'/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl'"

alias bp='vim ~/.bash_profile'
alias bpr='. ~/.bash_profile'

alias yv='sudo chown -R sercaneraslan:wheel'

alias de='cd ~/Desktop/'
```

How do I add these aliases?

* Open the .zshrc file: `vim ~/.zshrc`
* Add all of them to the end of the file and save it.
* Execute the .zshrc file: `. ~/.zshrc`

<h1 align="center">🕹️ Text Editor</h1>

<p align="center">
I prefer <a href="https://www.sublimetext.com/">Sublime Text</a> as a text editor.
</p>

<p align="center">
PS I wrote a detailed Turkish blog post about <a href="http://blog.sercaneraslan.com/sublime-texti-etkin-kullanma">Efficient usage of Sublime Text</a> many years ago. If you are interested, you can read it.
</p>

## ⚙️ Settings

```js
{
    "font_size": 12,
    "margin": 0,
    "default_line_ending": "unix",
    "translate_tabs_to_spaces": true,
    "highlight_line": true,
    "highlight_modified_tabs": true,
    "scroll_speed": 5.0,
    "word_wrap": true,
    "preview_on_click": false,
    "ensure_newline_at_eof_on_save": true,
    "scroll_past_end": true,
    "theme": "Default Dark.sublime-theme",
    "color_scheme": "Packages/Theme - Dark Material/schemes/Dark-Material.tmTheme",
    "ignored_packages":["Vintage"],
    "overlay_scroll_bars": "enabled",
    "font_options": [ "gray_antialias" ],
    "bold_folder_labels": true
}

```

## 🎨 Themes

- [Theme - Dark Material](https://packagecontrol.io/packages/Theme%20-%20Dark%20Material)
- [Predawn](https://packagecontrol.io/packages/Predawn)

## 📦 Packages

- [Git](https://packagecontrol.io/packages/Git)
- [Git Gutter](https://packagecontrol.io/packages/GitGutter)
- [BracketHighlighter](https://packagecontrol.io/packages/BracketHighlighter)
- [SublimeLinter](https://packagecontrol.io/packages/SublimeLinter)
- [AutoFileName](https://packagecontrol.io/packages/AutoFileName)
- [Pretty JSON](https://packagecontrol.io/packages/Pretty%20JSON)
- [Live Reload](https://packagecontrol.io/packages/LiveReload)

How do I install Themes and Packages?

- Install [Package Control](https://packagecontrol.io/installation).
- Press `Cmd + Shift + P` combination.
- Type `Package Control: Install Package` and press `enter`.
- Write your theme or package name and press `enter`.

## 💫 Snippets

- Open `Tools > Developer > New Snippet`.
- Replace with the following code and save as `cl.sublime-snippet`.

```html
<snippet>
    <content><![CDATA[
console.log(${1:params});
]]></content>
    <tabTrigger>cl</tabTrigger>
</snippet>
```
