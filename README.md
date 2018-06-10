# vim-test-truffle

A plugin for [vim-test](https://github.com/janko-m/vim-test) to support [Truffle](https://github.com/trufflesuite/truffle).
[Truffle](https://github.com/trufflesuite/truffle) is a development framework for Ethreum.
This plugin can run `truffule test` from vim.

# Setup

Add the line to your `.vimrc` before loading `vim-test`.

```vim:.vimrc
let test#custom_runners = {'Solidity': ['Truffle']}
```
