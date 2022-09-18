# latest.mc.s2n.tech

8 月から進行中の Minecraft マルチサーバー(身内) のプロジェクト状況を Issue 内で管理しちゃおう

- [latest.mc.s2n.tech - Dynmap](https://mc-map.s2n.tech/)

## サーバー情報

詳しいサーバー情報は [こちらから](./docs/Server-Info.md) 確認できます。

## 使い方

### Issue でやること管理

latest.mc.s2n.tech の [Issues](https://github.com/approvers/latest.mc.s2n.tech/issues) ページにてやることをまとめていきましょう。

やることリストの作成をサポートするため、Issue テンプレートを用意しています。

### 権限

latest.mc.s2n.tech に参加しているアクティブメンバーで、かつ approves に参加しているメンバーは `Maintain` 権限を持っています。

(`Maintain` ってなんだ？って？: [GitHub Docs: Repository permission levels for an organization](https://docs.github.com/en/organizations/managing-access-to-your-organizations-repositories/repository-permission-levels-for-an-organization) 見ろカス)

- [@m2en](https://github.com/m2en)
  - リポジトリオーナーのため `Admin` 権限を持っています。
- [@shun-shobon](https://github.com/shun-shobon)
  - approves の権限を持っているため `Admin` 権限がオーバーライドされています。
- [@noobest19s](https://github.com/noobest19s)
- [@KisaragiEffective](https://github.com/KisaragiEffective)
- [@su8ru](https://github.com/su8ru)
- [@Nanai10a](https://github.com/Nanai10a)

## その他

### ラベル

ラベルについては CI で管理しています。

ラベルを追加・削除する際は [labels.yml](./.github/labels.yml) を編集してください。

```yml
- name: "Type: 冒険"
  color: "ed7bd8"
```

- `name:` にはラベルの名前を指定します。
  - Prefix 製にしとくといいかも
- `color:` にはラベルの色を HEX で `#` を抜いて指定します。

このファイルが更新されるか、 [Actions](https://github.com/approvers/latest.mc.s2n.tech/actions/new) ページから手動実行もできます。
