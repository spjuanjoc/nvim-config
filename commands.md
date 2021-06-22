# nvim commands


## Create a config file

Create it in the following path:

```
~/.config/nvim/init.vim
```

See [stsewd](https://stsewd.dev/es/posts/neovim-installation-configuration/)

Requires python3 and pip3


## Copiar y pegar dentro y fuera de nvim

- Instalar xclip

```
sudo apt install xclip
```

- Copiar al portapapeles:

```
"+y
```

- Pegar desde portapapeles:

```
"+p
```

## Recargar archivo


```
:e

:e!
```

## Seleccionar todo

```
ggVG
```

`gg` moves to first line. `V` starts visual mode. `G` jumps to last line thereby selecting from first to last line 

