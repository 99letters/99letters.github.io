# shiga craft — visual concept & sitemap

**project:** 滋賀の工芸品を世界に発信するブランドサイト（トップページ・プロトタイプ）
**client:** 木下スタジオ（仮想依頼）
**reviewed by:** Jobs / CEO
**aesthetic ref:** `../../kinoshita_partner/brand_context.md`

---

## visual concept / ビジュアルコンセプト

### title
**"MADE IN SILENCE"**
> 琵琶湖の静けさの中で、手が形をつくる。

滋賀工芸の本質は「喧騒からの距離」にある。
大量生産・過剰デザインの対極——素材、手、時間。その静けさを翻訳する。

### aesthetic direction

| element | direction |
|---|---|
| color | モノクローム基調。ただし工芸素材（陶土・漆・麻）の質感色を1点のみアクセントに使う |
| typography | 欧文 serif（大文字・広いトラッキング）× 日本語明朝体の対比 |
| texture | フィルムグレイン・オーバーレイで手仕事の温度を与える |
| imagery | 工芸品のクローズアップ。余白を広く取る。背景は白または黒 |
| motion | 静的。スクロールに連動した subtle なフェードのみ |
| layout | 非対称グリッド。左寄りのテキストブロックと右の余白 |

### tone of copy

- 短く、余白がある文章。
- 日本語と英語を並走させる（翻訳ではなく、それぞれの言語で書き直す）。
- 説明しない。体験させる。

---

## sitemap / サイトマップ

```
shiga_craft/
├── index.html          # TOP — hero + concept statement + featured
├── works.html          # WORKS — 工芸品ギャラリー（カテゴリ別）
├── artisans.html       # ARTISANS — 職人紹介
├── about.html          # ABOUT — ブランドの思想・滋賀について
└── contact.html        # CONTACT — 問い合わせ・取り扱い
```

### top page structure (index.html)

```
[HERO]
  — full viewport
  — キャッチコピー大見出し（EN）+ 日本語サブ
  — grain overlay
  — scroll indicator

[CONCEPT STATEMENT]
  — 2〜3行のブランドステートメント（日英）
  — 左寄せ、余白多め

[FEATURED WORKS]
  — 工芸品 3点をグリッドで表示
  — 画像 + 素材名 + 産地のみ。説明文なし

[FOOTER]
  — ナビゲーション + SNS + copyright
```

---

## brand alignment check (Jobs)

- [ ] モノクロームを守っているか
- [ ] テキスト量は最小限か
- [ ] grain textureは主張しすぎていないか
- [ ] 日英どちらも「翻訳」ではなく「書き直し」か
- [ ] 余白は恐れずに取れているか
