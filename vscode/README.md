# VSCode

## Q: `code` command not found

Open the Command Palette (⇧⌘P) and type 'shell command' to find the Shell Command: Install 'code' command in PATH command.

```
cat << EOF >> ~/.bash_profile
export PATH="\$PATH:/Applications/Visual Studio Code.app/Contents/Resources/app/bin"
EOF
```
> ([source](https://code.visualstudio.com/docs/setup/mac#_launching-from-the-command-line))
