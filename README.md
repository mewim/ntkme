~
=

$HOME

Bootstrap
---------

``` sh
( cd "$(mktemp -d)" && ( git clone --depth 1 -- https://github.com/ntkme/ntkme.git && rm -rf ~/.git && mv ntkme/.git ~/.git && ( cd && git reset --hard && touch .gitconfig && git update-index --skip-worktree -- README.md LICENSE ); rm -rf -- "$(pwd)" ) )
```

License
-------

See [LICENSE](LICENSE).
