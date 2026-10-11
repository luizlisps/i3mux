# i3mux

Configuração de painéis do tmux inspirada no tiling do i3. Testada com tmux 3.7c.

## Instalação

Clone o repositório:

```sh
git clone https://github.com/luizlisps/i3mux.git ~/.config/i3mux
```

Adicione esta linha ao seu `~/.tmux.conf`:

```tmux
source-file ~/.config/i3mux/tmux.conf
```

Recarregue o tmux com `tmux source-file ~/.tmux.conf` ou abra uma nova sessão. Os atalhos estão documentados no início de `tmux.conf`.

## Licença

Apache-2.0. Consulte [LICENSE](LICENSE).
