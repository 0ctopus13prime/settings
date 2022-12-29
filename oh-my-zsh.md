## Sites
https://ohmyz.sh <br/>
https://github.com/ohmyzsh/ohmyzsh/wiki/Themes <br/>
https://velog.io/@insutance/Oh-My-Zsh-%EC%84%A4%EC%B9%98 : It walks you through the basics of installing oh-my-zsh in your terminal. <br/>
https://stackoverflow.com/questions/27885057/zsh-theme-for-full-path-display-git-changes : How to tell ohmyz to display absolute path of the current working directory.

## Steps
1. `sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
2. `vi ~/.zshrc`
3. Update `ZSH_THEME="cloud"`
4. `vi ~/.oh-my-zsh/themes/cloud.zsh-theme`
5. Change `%c` to `%~`
