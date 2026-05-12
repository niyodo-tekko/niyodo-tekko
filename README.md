# 仁淀鉄鋼株式会社 公式サイト

仁淀鉄鋼株式会社（NIYODO TEKKO CO.,LTD.）の公式コーポレートサイトのソースコードです。  
GitHub Pages にて公開しています。

## サイト構成

| セクション | 内容 |
|---|---|
| ニュースリリース | 最新情報 |
| ごあいさつ | 代表メッセージ |
| 会社概要 | 基本情報・取引先 |
| 沿革 | 1958年の創業から現在までの歩み |
| 営業品目 | 取り扱い製品一覧 |
| 生産設備 | 奈良工場・東京工場の設備仕様 |
| ISO14001 / ISO9001 | 環境・品質方針 |
| レジリエンス認証 | 認証取得について |
| 行動計画 | 次世代育成・女性活躍推進 |
| 反社会的勢力排除方針 | 基本方針 |
| SDGs宣言 / SDGs債 | サステナビリティへの取り組み |
| アクセス | 各拠点の所在地・連絡先 |

## ファイル構成

```
niyodo-tekko/
├── index.html              # メインページ（全コンテンツを1ページに収録）
├── map.html                # アクセスマップ
├── css/
│   ├── bootstrap.min.css           # Bootstrap 2.x
│   ├── bootstrap-responsive.min.css
│   ├── bootstrap-override_for_banner.css  # バナー用カスタムCSS
│   └── footer.css                  # フッター用CSS
├── js/
│   ├── jquery-1.10.2.min.js        # jQuery
│   ├── bootstrap.min.js            # Bootstrap JS
│   ├── jquery.bxslider.min.js      # バナースライダー
│   └── unslider.min.js             # スライダー
├── img/                    # 写真・ロゴ・アイコン等
├── video/                  # 工場設備の動画
│   ├── hagumi.mp4
│   ├── slitter.mp4
│   ├── tokyo_hagumi.mp4
│   └── video_*.html        # 動画再生用ページ
├── sdgs.pdf                # SDGs宣言
└── SustainabilityBond.pdf  # SDGs債関連資料
```

## 技術スタック

- HTML5（静的サイト、フレームワーク不使用）
- [Bootstrap 2.x](https://getbootstrap.com/)
- [jQuery 1.10.2](https://jquery.com/)
- [bxSlider](https://bxslider.com/)（バナースライダー）
- [Unslider](https://unslider.com/)（スライダー）
- 公開：[GitHub Pages](https://pages.github.com/)

## 更新方法

`main` ブランチに push すると、GitHub Pages に自動反映されます。

```bash
git add <変更ファイル>
git commit -m "変更内容の説明"
git push origin main
```

## 会社情報

| 項目 | 内容 |
|---|---|
| 商号 | 仁淀鉄鋼株式会社 / NIYODO TEKKO CO.,LTD. |
| 設立 | 昭和38年（1963年）11月 |
| 資本金 | 1億円 |
| 社員数 | 120名（令和7年3月末現在） |
| 売上高 | 139億円（令和7年3月期） |
| 事業内容 | 薄板・ステンレス・アルミ等のスリット加工販売 |

### 所在地

| 拠点 | 住所 | TEL |
|---|---|---|
| 大阪本社 | 〒550-0003 大阪市西区京町堀 2-5-12 | 06-6444-7001 |
| 奈良工場 | 〒636-0246 奈良県磯城郡田原本町千代1065-8 | 0744-32-4877 |
| 東京支社・東京工場 | 〒279-0025 千葉県浦安市鉄鋼通り1-4-1 | 047-304-3008 |

---

© NIYODO TEKKO CO.,LTD.
