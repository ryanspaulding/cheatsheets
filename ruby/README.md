# Ruby Cheat Sheet

## rbenv 

The best thing to happen to any language is a way to manage local installations of N versions of Ruby and its associated gems :) 

1. Get the latest installer (https://github.com/rbenv/rbenv-installer#rbenv-installer)
2. Follow the steps for installing. Note these worked at the time of writing but please check as they could of changed:
3. Add rbenv to your path, i.e. export PATH="$HOME/.rbenv/bin:$PATH"
4. Run the following and follow the steps `rbenv init`
5. Add the following to your .bashrc file `eval "$(rbenv init -)`
6. Now check your installation by running the following (expect to see all the versions of Ruby) `rbenv install -l`
