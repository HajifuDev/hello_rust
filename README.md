# Hello Rust

はじめての Rust。  
インストールして公式のチュートリアルをやってみる。

# VSCode Extensions

下記の拡張機能をインストールした。

- Rust
- CodeLLDB
- Better TOML

# NOTE

## `error: linkerccnot found`

手順通り進ても `error: linkerccnot found` というエラーが出てしまったが、 `sudo apt install build-essential` で `gcc` などのツール群をインストールしたら解決した。  
インストール時、`いくつかのアーカイブを取得できません。apt-get update を実行するか --fix-missing オプションを付けて試してみてください。` というメッセージが出てしまったので、 `sudo apt-get update --fix-missing` 実行。  
それでも同じエラーが出てしまったので、 [これ](https://ostechnix.com/how-to-fix-rust-error-linker-cc-not-found-on-linux/) を参考に `cmake` というのを入れてみる。  
=> できた！！
