To get the hash for the codeberg release:

- nix-prefetch-url --unpack https://codeberg.org/mikf/gallery-dl/archive/v1.32.11.zip
- nix hash convert --hash-algo sha256 --to sri 09pki2xp5ll6ll4kd7xr6kr7wmsccg7zn065arbmakzd6hshv48v
