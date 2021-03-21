# modern-cli-tools
[ansible](https://github.com/ansible/ansible) helps to install and **upgrade** a set of modern rust/go cli tools

* [bat](https://github.com/sharkdb/bat)
* [exa](https://github.com/ogham/exa)
* [fd](https://github.com/sharkdb/fd)
* [fzf](https://github.com/junegunn/fzf)

## Installing

Just invoke ansible like this, to installi:

```bash
ansible-playbook tool*yml
```

Your new tools are in `~/.local/bin` - expand `$PATH` if needed.

## contributing

If you have another great tool, please fill an issue. 👍
