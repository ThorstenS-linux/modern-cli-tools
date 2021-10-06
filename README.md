# modern-cli-tools
[ansible](https://github.com/ansible/ansible) helps to install and **upgrade** a set of modern rust/go cli tools

* [bat](https://github.com/sharkdp/bat)
* [broot](https://dystroy.org/broot/)
* [exa](https://github.com/ogham/exa)
* [fd](https://github.com/sharkdb/fd)
* [fzf](https://github.com/junegunn/fzf)
* [glow](https://github.com/charmbracelet/glow)
* [restic](https://github.com/restic/restic)
* [watchexec](https://github.com/watchexec/watchexec)

## Installing

Just invoke ansible like this, to installi:

```bash
ansible-playbook tool*yml
```

Your new tools are in `~/bin` - expand `$PATH` if needed or change `{{ instpath }}`

## contributing

If you know another great tool, please fill an issue. 👍

