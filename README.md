# Rii Intelligence

Rii（RiiOS）プロジェクトの Windows 向け AI PC 分析・最適化アプリ（体験版）の配布用リポジトリです。

## Rii Intelligence ってなに？
PC が「重い」「遅い」「不安定」といったときに、AI と日本語で会話しながら原因を探し、改善する Windows 11 向けのアプリです。
- PC の状態や履歴、使い方を分析して、何が原因かを説明します
- 改善案はあなたが承認したときだけ実行し、前後の速さをベンチマークで比べます。うまくいかなければ元に戻せます（ロールバック）
- API キーがなくても、ローカルの診断モードで使えます。外部 AI（Gemini、OpenAI、Ollama など）は、自分で設定したときだけ通信します

- ダウンロード: [Releases](../../releases/latest)
- ⚠ 実験的ソフトウェアです。VM または検証専用PCでの利用を推奨します。利用は自己責任でお願いします。
- フィードバック・不具合報告: Rii Discord サーバーのフィードバックチャンネル

<!-- 配布手順（Hark）: parts/ に RiiIntelligence-<ver>-win-x64.zip.partNN（90MB 分割）と RELEASE_NOTES_<ver>.md を置き、最後に VERSION（1行目=版、2行目=ZIPのSHA256）を更新して push すると Actions がリリースを作る。 -->
