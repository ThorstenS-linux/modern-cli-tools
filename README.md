# modern-cli-tools
[ansible](https://github.com/ansible/ansible) helps to install and **upgrade** a set of modern rust/go cli tools

## list of tools

* [bat](https://github.com/sharkdp/bat) - a ` cat`(1) clone with wings
* [broot](https://dystroy.org/broot/) - get an overview of a directory, even a big one
* [dstp](https://github.com/ycd/dstp) - run common networking tests against your site
* [exa](https://github.com/ogham/exa) - a modern replacement for `ls` 
* [fd](https://github.com/sharkdp/fd) - a simple, fast and user-friendly alternative to `find`
* [fzf](https://github.com/junegunn/fzf) - a general-purpose command-line fuzzy finder
* [gickup](https://github.com/cooperspencer/gickup) - clone/mirror git-repositories
* [gh](https://github.com/cli/cli) - GitHub’s official command line tool `gh`
* [glow](https://github.com/charmbracelet/glow) - render markdown on the CLI, with pizzazz!
* [restic](https://github.com/restic/restic) - fast, secure, efficient backup program 
* [watchexec](https://github.com/watchexec/watchexec) - executes commands in response to file modifications

## installing

Just invoke ansible like this, to install all tools on `localhost`:

```bash
ansible-playbook tool*yml
```

Invoke like this, to install fd as sudo enabled user under `/usr/local/bin`:

```bash
sudo ansible-playbook -e instpath="/usr/local/bin" tool_fd.yml
```

## running

Your new tools are in `~/bin` - expand `$PATH` if needed or change `{{ instpath }}`.  
For the individual options, consult the relevant project pages

## contributing

If you know another great tool, please fill an issue. 👍

tia /t