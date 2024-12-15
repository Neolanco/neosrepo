# neosrepo
contains a only mirror (for now)

## guide
append the following to ```/etc/paru.conf```:
```sh
[neosrepo]
Url = https://github.com/Neolanco/neosrepo.git
```

and now you can use the repo like this:
```sh
paru -Sy --pkgbuilds neosrepo/xdg-desktop-portal-gnome 
```

## sources
[patched xdg-gnome: ASCUPB](https://github.com/Arxari/ASCUPB)