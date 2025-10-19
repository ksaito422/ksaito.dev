# ksaito.dev

## when writing

### 開発環境の起動
```shell
hugo server -D
```

### ファイル作成
```
hugo new posts/$(date "+%Y-%m-%d").md

```

### 公開設定
```
draft = true # 下書きのため公開しない
draft = false # 公開する
```

### 予約投稿
```
date = '2099-10-20T11:33:47+09:00' # 未来日時に設定すると予約投稿になる
draft = false

```
## when publishing
ビルド
```shell
hugo build
```

## powered by
- [gohugoio/hugo: The world’s fastest framework for building websites.](https://github.com/gohugoio/hugo?tab=readme-ov-file)
- [adityatelange/hugo-PaperMod: A fast, clean, responsive Hugo theme.](https://github.com/adityatelange/hugo-PaperMod)
