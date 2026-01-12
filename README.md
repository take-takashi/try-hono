# try-hono

Honoを使ってみる試み

# setup command

```bash
% touch .mise.toml
% mise trust -a
% vim .mise.toml
% cat .mise.toml
[tools]
node = "24.8.0"
codex = "latest"

% mise install

# npm version up
% npm install -g npm@11.7.0

# hono setup
% npm create hono@latest hono -- --template cloudflare-workers
# メモ：以下のコマンドの方がいいと思われる
% npm create hono@latest backend -- --template cloudflare-workers --pm npm --install

```
