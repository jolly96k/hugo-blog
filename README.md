# hugo-blog

## ■このリポジトリについて
静的サイトジェネレーターのHugoでブログを書くプロジェクト。

開発環境をコンテナで作成して利用することを前提としているが、ネイティブの開発環境で利用することも可能。

Hugoについては公式情報を参照。

## ■利用時の注意
ブログテーマをサブモジュールで追加しているため、クローンするときは"--recurse-submodules"オプションを付ける必要あり。

    $ git clone https://github.com/jolly96k/hugo-blog.git --recurse-submodules --remote-submodules

## ■参考URL
Hugo公式サイト: <https://gohugo.io/>

Hugoクイックスタート: <https://gohugo.io/getting-started/quick-start/>

HugoのDockerコンテナ(非公式): <https://github.com/jolly96k/blog>