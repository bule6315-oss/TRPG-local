# TRPG ろ〜かる！ (TRPG Local)

軽量・単一HTMLで動作する、ローカル＆身内セッション向けのシンプルなTRPG支援ツールです。
A lightweight, single-file HTML tool for tabletop RPG sessions, designed for local and private use.

---

## 主な機能 / Features

- **ダイスボット / Dice Bot**: 
  - クトゥルフ神話TRPG（CCB, 1D100, RES対抗判定など）
  - 通常ダイス（1D6, 2D6+1 など）
  - ランダム選択（choice コマンド）
- **盤面＆コマ管理 / Board & Tokens**: 
  - ドラッグ操作対応のキャラクタートークン
  - ココフォリア / いあきゃら形式のコマデータ取り込み対応
- **チャット＆ログ / Chat & Logs**: 
  - タブ切り替えチャット
  - タイムスタンプ（月日/時刻）付きログ抽出（TXT / HTML）
- **データ保存 / Data Storage**: 
  - ブラウザの LocalStorage による自動保存
  - 部屋データの JSON エクスポート / インポート

---

## 使い方 / How to Use

1. `index.html` をブラウザで開くだけで起動します。
2. 背景画像や立ち絵は、ローカルパスまたはGoogleドライブ等の画像直リンクを指定可能です。
3. セッション終了後は「部屋保存（💾）」からJSONファイルをダウンロードしてバックアップしてください。

1. Simply open `index.html` in your web browser.
2. Background and token images can be loaded via local paths or direct image URLs.
3. Use the save button (💾) to export your room data as a JSON file for backup.

---

## 開発方針 / Note
個人および友人とのセッション向けに開発されたプロトタイプです。
本プロジェクトのコード設計・実装・リファクタリングには、開発アシスタントとして生成AI（LLM）を活用しています。

This is a personal hobby project developed for private gaming sessions.
Generative AI was used as a coding assistant for the design and implementation of this project.

## 免責事項 / Disclaimer
個人制作のツールのため動作保証や個別サポートはありません。セッションデータの管理は自己責任（こまめな部屋保存）でお願いします。
Provided "as is" without warranty. Please ensure you export room backups regularly.
