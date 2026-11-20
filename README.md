# Remotion Skills 13本セット（Muse用）

Museに「コードで動画を作る作法」を覚えさせるスキルファイル集です。
動画生成AIを使わず、プログラム（Remotion）でモーショングラフィックスや字幕つき動画を書き出すためのノウハウが入っています。

## 中身（13本）
- remotion-best-practices … 制作の型（バネの動き、補間、シーン構成）
- remotion-captions … 字幕の付け方
- remotion-create … プロジェクトの作り方
- remotion-docs … 公式ドキュメントの調べ方
- remotion-interactivity … 画面から操作できる動画の仕組み
- remotion-license … ライセンスの確認
- remotion-maps … 地図アニメーション
- remotion-markup … 動画の部品の書き方
- remotion-multimedia … 音声・動画素材の扱い（長さ取得など）
- remotion-render … 書き出しのやり方
- remotion-saas … サービス化の考え方
- remotion-studio … プレビュー画面の使い方
- remotion-upgrade … バージョン上げの手順

## Museへの入れ方
1. この一式（ZIPまたはフォルダ）を、自分のMuseに渡す
2. 「このSkillsを覚えて」と頼む
3. Museがカスタムスキルとして取り込む。あとは「この台本で30秒の紹介動画を作って」と頼むだけ

（このパックを作った鈴木さんのMuseには2026-11-20に取り込み済みで、下の実証動画2本はそのSkillsを使って作りました）

## 実証
2026-11-20、このセットとRemotionで実際に動画を書き出しました。
- Muse紹介動画（32秒・1920×1080、文字の動きと音楽まで全部コード生成）
- Threads用リール（12秒・縦型、カードとキャラがバネの動きで入る）

## Claude Code・Codex・Cursorに入れる場合
公式のコマンド1行で入ります。

npx skills add remotion-dev/skills

## 出典とライセンス
- スキル本体はRemotion公式の公開リポジトリ（github.com/remotion-dev/skills）のものです
- Remotion本体は、個人と従業員3人以下の会社は無料で使えます。それ以上の規模は有料ライセンスが必要です（remotion.pro/license）
