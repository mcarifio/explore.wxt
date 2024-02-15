# wxt-notes

Explore [wxt](https://wxt.dev/), a framework to write chrome plugins. See [./notes/](./notes/) for more.

## start

### start nodejs

The wxt documentation traffics in node, so I started there. I installed asdf, then nodejs, updated/installed `pnpm` and `npm` and then install installed `wxt@latest`.

```bash
$ p='' output='' OLDPS1="$PS1" PS1="\$p " ## now you can paste all the commands below wholesale with (set -x; <paste> ) 2>&1 | tee -p /dev/stderr | wl-copy 

$p asdf install nodejs latest
${output}

$p asdf global nodejs latest
${output}

$p asdf current nodejs
nodejs          21.6.2          /home/mcarifio/.tool-versions

$p type -p node
/home/mcarifio/opt/asdf/current/shims/node

$p asdf which node
/home/mcarifio/opt/asdf/current/installs/nodejs/21.6.2/bin/node

$p node --version
v21.6.2

$p npm --version
10.4.0

$p npm install --global npm@latest pnpm@latest
${output}

$p npm --version
10.4.0

$p pnpm --version
8.15.0

$p pnpm install --global wxt@latest
${output}

$p type -p wxt
/home/mcarifio/opt/asdf/current/shims/wxt

$p asdf which wxt
/home/mcarifio/opt/asdf/current/installs/nodejs/21.6.2/.npm/bin/wxt

$p wxt --version
wxt/0.16.6 linux-x64 node-v21.6.2

$p mkdir -p ~/explore/wxt; cd $_
```

### start deno

### start bun

