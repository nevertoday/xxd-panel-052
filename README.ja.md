<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 052 project banner" width="1200"></p>

<div align="center">

# 🦁 XXD Panel 052

### 手作りのミニチュア世界を一本の風景線に浮かべる

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Modes](https://img.shields.io/badge/Modes-4-EF805E?style=flat-square)](#)
[![Output](https://img.shields.io/badge/Output-PNG-4AA1AE?style=flat-square)](#)

<a href="README.md">简体中文</a> ペーパークラフト · 横長の浮島 · 本物の手仕事 · 空気感のある寒色ブルー · 広い余白

元写真で最も識別しやすい主体と根拠のある少数の環境要素を、紙、カード紙、柔らかい粘土、薄い木片のミニチュアとして一本の細長い浮遊景観帯に再構成します。手仕事の細部、マクロ光、淡い大きな余白が上質なアートインスタレーションを作ります。

## この Skill が必要な理由

このスタイルは元写真に依存し、内容を差し替えられる装飾プリセットではありません。変換は次の因果鎖に従います：

```text
lock identity, silhouette, pose, direction, and relation → preserve three cues → select one primary subject and limited supported elements → rebuild paper, cardstock, soft-clay, and thin-wood miniatures → place them on one long horizontal floating strip → establish scale depth, overlap, and calm balance → reveal authentic craft through macro light → retain airy cool blue and generous space → add one signature-like short title
```

無関係な写真に替えても識別、模型構造、補助要素、浮島の輪郭、素材、均衡、色、余白、文案が実質的に変わらないなら、本 Panel の成果ではありません。

## ビジュアル契約

- シルエット、比率、姿勢、方向、動作、構造、色、素材、関係から元写真固有の手掛かりを三つ以上保つ。
- 主役一つと根拠のある少数の補助模型を、一本の長く細く軽い横長浮遊景観帯に置く。
- 尺度差、重なり、静かな前後景で奥行きを作り、概ね中央に置きつつ機械的対称や第二焦点を避ける。
- 紙繊維、折り目、切断跡、層の厚み、粗い縁、小さな手作りの不完全さを見せ、滑らかなプラスチックCGを拒む。
- 空気感のある寒色ブルー、象牙色、淡いベージュ、くすみ緑、ごく少量のくすみピンクを、柔らかなマクロ光と広い淡色余白で整える。

完全な美的制約と拒否項目は Skill と生成プロンプトにあります。原文の美的動機を守りつつ、歴史的な3:4画布を隠れた既定値にはしません。 [SKILL.md](SKILL.md) · [production prompt](references/xxd-panel-052-prompt.en.md)

## 作例

作例はまだ提供されていません。予約場所は [assets/examples](assets/examples/README.md) に記載しています。今後の作例は美的意図だけを示し、生成参照、固定された被写体、構図、配色、文案、既定画布にはなりません。

## 組み合わせ可能な4つの出力

`1`、`1+3`、`1,2,4`、`全部` で一つまたは複数を選べます。`全部` は元写真1枚につき通常3点と壁紙4点、計7点のPNGを出力します。

| モード | 未指定時の寸法 | 成果物 |
| --- | --- | --- |
| `top-bottom` | 元画像適応 `W×2H` | 上に完全な元写真、下に変換デザイン、厳密な50/50 |
| `left-right` | 元画像適応 `2W×H` | 左に完全な元写真、右に変換デザイン、厳密な50/50 |
| `design-only` | 元画像適応 `W×H` | 変換デザインのみ。元写真は表示しない |
| `wallpaper-pack` | 端末別に指定 | スマートフォン、iPad、デスクトップ、子ども用ウォッチの個別PNG |

壁紙は連動または独立を選べます。連動は一つの基準作を承認し、全端末が元写真と同じ基準作を参照します。切り抜きも派生連鎖もしません。独立は各端末が元写真だけを参照します。

## 文案と言語

生成前に自動文案、正確な指定文案、文字なしを確定します。言語は指示文ではなく対象読者に従い、完成稿は一字一句保持します。

本プロジェクトの文案規則：場所、主体のアイデンティティ、主題、感情から短い題名を一つだけ抽出し、小さく洗練された僅かな手書き感のある文字を景観帯の下、基部の流れ、または模型空間に置き、商業見出しでなく作家の署名として見せます。

## 幾何、ラスター、信頼

通常モードは指定がなければ元画像に適応し、二連は厳密な50/50、成果物はPNGラスターです。毎回 `~/Desktop/xxd/` に新規タスクを作り、非公開の生成経路情報を開示しません。

設定済みの画像ブリッジは匿名化された状態だけを返し、提供元、接続先、認証情報、ヘッダー、プロンプト、応答、アカウント情報を開示しません。SVG、HTML、Canvas、図解、プログラム描画は最終ラスター作品の代替になりません。

## 使い始める

```bash
git clone https://github.com/nevertoday/xxd-panel-052.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-052" ~/.codex/skills/xxd-panel-052
```

Claude Code では同じフォルダを次へリンクできます： `~/.claude/skills/xxd-panel-052`. インストール後に Agent セッションを再起動してください。

```text
$xxd-panel-052
Use this photograph, ask me for the modes and copy setting, then generate fresh raster outputs.
```

完全仕様: [Skill ワークフロー](SKILL.md) · [原始スタイル資料](references/052-source.md) · [英語生成プロンプト](references/xxd-panel-052-prompt.en.md) · [中国語生成プロンプト](references/xxd-panel-052-prompt.zh-CN.md)

## XXD について

XXD は Xiaoxiaodong のブランド名略称です。作成・管理： [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## サポートとメンバーシップ

### 個別コンサルティング · 299元／時間

Skills の使用とワークフローに関する一対一の相談です。WeChat で Xiaoxiaodong にご連絡ください。 [WeChat](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

### Xiaoxiaodong Skills ユーザー交流グループ · 99元

一回の支払いで Skills ユーザー交流グループに参加できます。時間制の個別相談は別料金です。

### Knowledge Planet＋会員プロンプトライブラリ · 699元／年

Knowledge Planet と会員プロンプトライブラリは年額699元の一回の支払いで両方を利用できます。Knowledge Planet から加入した場合は WeChat で Xiaoxiaodong に連絡してプロンプトライブラリの引換コードを受け取り、プロンプトライブラリで自動開通した場合は WeChat で連絡して Knowledge Planet への招待を受けてください。

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) · [Member Prompt Library](https://vip.xiaoxiaodong.ai/)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<div align="center"><strong>軽やかな一本の風景帯に、写真の中で記憶すべき日常を載せる。</strong></div>

---

<div align="center">

## ☕ オープンソースを支援

中国語圏以外では Buy Me a Coffee を利用できます。支援は任意で、オープンソースへのアクセスを変えません。


<p align="center"><a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee" width="180"></a></p>

</div>
</div>
