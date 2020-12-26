#
# Defines environment variables.
#
# Authors:
#   Sorin Ionescu <sorin.ionescu@gmail.com>
#

# Ensure that a non-login, non-interactive shell has a defined environment.
if [[ ( "$SHLVL" -eq 1 && ! -o LOGIN ) && -s "${ZDOTDIR:-$HOME}/.zprofile" ]]; then
  source "${ZDOTDIR:-$HOME}/.zprofile"
fi


# source secret env variables not to be stored in repository
if [[ -s ~/.zshsecret ]]; then
  source ~/.zshsecret
fi


export PYENV_VIRTUALENV_DISABLE_PROMPT=1
