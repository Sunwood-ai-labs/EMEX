<p align="center">
<img src="https://huggingface.co/datasets/MakiAi/IconAssets/resolve/main/EMEX.jpeg" width="100%">
<br>
<h1 align="center">EMEX</h1>
<h2 align="center">
  ～ Evolutionary Merge Experiment ～
<br>
  <img alt="PyPI - Version" src="https://img.shields.io/pypi/v/EMEX">
<img alt="PyPI - Format" src="https://img.shields.io/pypi/format/EMEX">
<img alt="PyPI - Implementation" src="https://img.shields.io/pypi/implementation/EMEX">
<img alt="PyPI - Status" src="https://img.shields.io/pypi/status/EMEX">
<img alt="PyPI - Downloads" src="https://img.shields.io/pypi/dd/EMEX">
<img alt="PyPI - Downloads" src="https://img.shields.io/pypi/dw/EMEX">
<a href="https://github.com/Sunwood-ai-labs/EMEX" title="Go to GitHub repo"><img src="https://img.shields.io/static/v1?label=EMEX&message=Sunwood-ai-labs&color=blue&logo=github"></a>
<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/Sunwood-ai-labs/EMEX">
<a href="https://github.com/Sunwood-ai-labs/EMEX"><img alt="forks - Sunwood-ai-labs" src="https://img.shields.io/github/forks/EMEX/Sunwood-ai-labs?style=social"></a>
<a href="https://github.com/Sunwood-ai-labs/EMEX"><img alt="GitHub Last Commit" src="https://img.shields.io/github/last-commit/Sunwood-ai-labs/EMEX"></a>
<a href="https://github.com/Sunwood-ai-labs/EMEX"><img alt="GitHub Top Language" src="https://img.shields.io/github/languages/top/Sunwood-ai-labs/EMEX"></a>
<img alt="GitHub Release" src="https://img.shields.io/github/v/release/Sunwood-ai-labs/EMEX?color=red">
<img alt="GitHub Tag" src="https://img.shields.io/github/v/tag/Sunwood-ai-labs/EMEX?sort=semver&color=orange">
<img alt="GitHub Actions Workflow Status" src="https://img.shields.io/github/actions/workflow/status/Sunwood-ai-labs/EMEX/publish-to-pypi.yml">
<br>
<p align="center">
  <a href="https://hamaruki.com/"><b>[🌐 Website]</b></a> •
  <a href="https://github.com/Sunwood-ai-labs"><b>[🐱 GitHub]</b></a>
  <a href="https://x.com/hAru_mAki_ch"><b>[🐦 Twitter]</b></a> •
  <a href="https://hamaruki.com/"><b>[🍀 Official Blog]</b></a>
</p>

</h2>

</p>

>[!IMPORTANT]
>このリポジトリのリリースノートやREADME、コミットメッセージの9割近くは[claude.ai](https://claude.ai/)や[ChatGPT4](https://chatgpt.com/)を活用した[AIRA](https://github.com/Sunwood-ai-labs/AIRA), [SourceSage](https://github.com/Sunwood-ai-labs/SourceSage), [Gaiah](https://github.com/Sunwood-ai-labs/Gaiah), [HarmonAI_II](https://github.com/Sunwood-ai-labs/HarmonAI_II)で生成しています。

EMEX (Evolutionary Merge Experiment) は、mergekit-evolve を使用して複数の言語モデルを組み合わせ、タスクに特化した強力な言語モデルを生成するためのプロジェクトです。

## 特徴

- mergekit-evolve を使用して、複数の言語モデルを組み合わせることができます。
- タスクに特化した言語モデルを生成することで、高いパフォーマンスを発揮します。
- Docker Compose を使用して、簡単に環境を構築できます。

## 設定ファイル

主要な設定ファイルである `evol_merge_config.yml` では、以下のような設定を行います。

- 組み合わせるモデルの指定 (例: NousResearch/Hermes-2-Pro-Mistral-7B, PocketDoc/Dans-AdventurousWinds-Mk2-7b, HuggingFaceH4/zephyr-7b-beta)
- マージ方法の指定 (例: task_arithmetic)
- ベースモデルの指定 (例: mistralai/Mistral-7B-v0.1)
- タスクの名前と重みの指定 (例: alpaca_prompt_format, spartqa_train)

## 含まれるファイル

- `eval_tasks/`: モデルの評価に使用するタスクの設定ファイルが含まれています。
- `script/`: 便利なスクリプトファイルが含まれています。
- `.aira/`: AIRA (AI Repository Assistant) の設定ファイルが含まれています。
- `.github/workflows/`: GitHub Actions の設定ファイルが含まれています。
- `.harmon_ai/`: HarmonAI_II (README 生成ツール) の設定ファイルが含まれています。

## 使い方

1. このリポジトリをクローンします。
2. Docker Compose を使用して環境を構築します。
3. `evol_merge_config.yml` を編集し、必要に応じて設定を変更します。
4. mergekit-evolve を実行して、タスクに特化した言語モデルを生成します。

## 貢献

このプロジェクトへの貢献を歓迎します。問題やプルリクエストを通じて、改善点やアイデアを共有してください。

## ライセンス

このプロジェクトは [MIT ライセンス](LICENSE) の下で公開されています。

## 謝辞

このプロジェクトは、以下のツールやサービスを活用して開発されました。

- [claude.ai](https://claude.ai/)
- [ChatGPT4](https://chatgpt.com/)
- [AIRA](https://github.com/Sunwood-ai-labs/AIRA)
- [SourceSage](https://github.com/Sunwood-ai-labs/SourceSage)
- [Gaiah](https://github.com/Sunwood-ai-labs/Gaiah)
- [HarmonAI_II](https://github.com/Sunwood-ai-labs/HarmonAI_II)

これらのツールやサービスの開発者の皆様に感謝いたします。