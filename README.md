### Install Pyenv

To install Pyenv on your Ubuntu-based distro just execute this command in shell:

```bash
bash <(curl -sSL https://raw.githubusercontent.com/MehediBijoy/system-configure/main/pyenv-installer.sh)
```

After the installation will be completed the script will automatically add these lines at the beginning of your `.bashrc` file, and will restart your shell:

```bash
export PYENV_ROOT="$HOME/.pyenv"
export PATH="$PYENV_ROOT/bin:$PATH"
eval "$(pyenv init --path)"
```

### Install Operator Mono Lig Font
A custom font using Operator Mono and Fira-Code styled ligatures.
```bash
Operator Mono Lig
```