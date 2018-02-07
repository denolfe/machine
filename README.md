# machine

> Machine setup, powered by Ansible.

My [dotfiles](https://github.com/denolfe/dotfiles) were becoming slightly bloated having to worry about configuration *and* setup, so it made sense to split out the configuration into its own repo.

This setup is currently optimized for [elementary os](https://elementary.io/) but should still work for ubuntu xenial.

## Usage

```console
$ wget https://github.com/denolfe/machine/archive/master.zip
$ unzip master.zip
$ cd machine-master
```

At this point, you might want to edit the `main.yml` file and comment
out stuff you don't want, when you're done, simply run:

```console
$ ./setup
```
