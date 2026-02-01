# AI Anime Ad Project

AI広告動画制作プロジェクト（ブラジル向け）

## 📁 ファイル構成

```
ai-anime-ad/
├── output_v3_final.mp4      ⭐ 完成版動画（25MB, 71秒）
├── audio/
│   ├── bgm_main.mp3         BGM（22秒、ループ用）
│   ├── bgm_looped_72s.mp3   BGM（72秒にループ済み）
│   ├── se_whoosh.mp3        トランジションSE
│   └── se_click.mp3         クリック音SE
├── narration/               ナレーション音声（16ファイル）
│   ├── 01_tres_cliques.mp3
│   ├── 02_anime_pronto.mp3
│   └── ... (全16ファイル)
├── source/
│   └── original.webm        元映像素材
└── scripts/
    ├── SCRIPT_v2.md         タイムライン脚本
    └── text_overlays.json   テキスト配置データ
```

## 🎬 人間が編集する場合

### Premiere Pro / DaVinci Resolve で編集

1. `source/original.webm` を読み込み
2. `narration/` の音声ファイルをタイムラインに配置
3. `scripts/SCRIPT_v2.md` のタイムラインを参照
4. `audio/` のBGM・SEを追加

### タイムライン（SCRIPT_v2.md参照）

| 時間 | 内容 |
|------|------|
| 0:00-0:06 | フック（3クリック） |
| 0:06-0:15 | アクションアニメ紹介 |
| 0:15-0:24 | エンタメアニメ紹介 |
| 0:24-0:35 | 3Dアニメ紹介 |
| 0:35-0:50 | ビジネスアニメ紹介 |
| 0:50-0:65 | 問題→解決 |
| 0:65-0:71 | CTA |

## 🔊 SE配置タイミング

- **Click**: 0.5秒（「3クリック」部分）
- **Whoosh**: 6秒, 15秒, 24秒, 35秒, 50秒, 65秒（シーン切り替え）

## 📤 YouTube

完成版: https://youtube.com/shorts/4PJb_Rcvtho

## 👥 担当

- **クロ**: 動画合成、ナレーション合成、BGM/SEミックス
- **OpenClaw**: BGM・SE生成、YouTubeアップロード
