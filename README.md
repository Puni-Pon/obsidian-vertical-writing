# obsidian-vertical-writing

Obsidianで日本語の縦書き表示を実現するCSSスニペットです。

## スクリーンショット

<!-- スクリーンショットがあれば追加 -->

## インストール

1. `vertical-writing.css` をダウンロード
2. Obsidianの設定を開く
3. **外観 → CSSスニペット** のフォルダアイコンをクリック
4. 開いたフォルダに `vertical-writing.css` をコピー
5. Obsidianに戻り、スニペット一覧の更新ボタン（丸い矢印）をクリック
6. `vertical-writing` のトグルをオンにする

## 使い方

縦書きにしたいノートの先頭に、以下のフロントマターを追加します：

```yaml
---
cssclasses:
  - vertical
---
```

閲覧モード（Reading View）に切り替えると、縦書きで表示されます。

## オプション機能

### 縦中横（たてちゅうよこ）

2桁の数字などを横並びにしたい場合、`<span class="tcy">` で囲みます：

```markdown
<span class="tcy">12</span>月<span class="tcy">25</span>日
```

### アルファベットを縦にする

特定のアルファベットを縦書きにしたい場合、`<span class="upright">` で囲みます：

```markdown
<span class="upright">ABC</span>株式会社
```

## カスタマイズ

### フォントを変更する

`font-family` の行を編集してください：

```css
font-family: "游明朝", "Yu Mincho", serif;
```

### 高さを変更する

`height: 80vh` の値を調整してください。

## 動作環境

- Obsidian v1.0.0 以上
- 閲覧モード（Reading View）でのみ動作

## ライセンス

MIT License
