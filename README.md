cheatsheets created by dpang06 for using:

https://github.com/cheat/cheat


# Configuration
1. clone this project into `~/.config/cheat/cheatsheets/`
```bash
cd ~/.config/cheat/cheatsheets/
git clone https://github.com/cheat/cheat.git dpang06
```

2. add configurations into `~/.config/cheat/conf.yml` (0=no sub-directory, 1=1 level of sub-directory)
```yml
...

  - name: dpang06-0
    path: /home/<username>/.config/cheat/cheatsheets/dpang06/0
    tags: [ dpang06 ]
    readonly: false

  - name: dpang06-1
    path: /home/<username>/.config/cheat/cheatsheets/dpang06/1
    tags: [ dpang06 ]
    readonly: false

...
```

3. check if the cheatsheets are there
```yml
cheat -t dpang06
```