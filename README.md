# このチュートリアルについて
Anthropic社が公開している[プロンプトエンジニアリングチュートリアル](https://github.com/anthropics/prompt-eng-interactive-tutorial)を株式会社Lbose内で日本語化したものです。
Claude3.5を利用した機械翻訳のため、一部不正確な日本語表現になっている可能性があります。

うまく動かない、意味がつかめない場合は、元リポジトリを参照してください。

このチュートリアルの、ライセンス、著作権についてはAnthropic社に帰属するものします。

# Anthropicのプロンプトエンジニアリング対話型チュートリアルへようこそ

## コースの紹介と目標

このコースは、Claude内で最適なプロンプトを構築する方法について、包括的かつ段階的な理解を提供することを目的としています。

**このコースを修了すると、以下のことができるようになります**:
- 良いプロンプトの基本構造を習得する
- 一般的な失敗パターンを認識し、それらに対処するための「80/20」テクニックを学ぶ
- Claudeの長所と短所を理解する
- 一般的なユースケースに対して、ゼロから強力なプロンプトを構築する

## コースの構成とコンテンツ

このコースは、プロンプトの作成とトラブルシューティングを自ら実践する機会を多く設けた構成になっています。コースは**9つの章と付随する演習**、さらに高度な手法に関する付録で構成されています。**章の順番に沿って学習を進めること**を想定しています。

**各レッスンの下部には「Example Playground」エリア**があり、レッスンの例を自由に試し、プロンプトの変更がClaudeの応答にどのように影響するかを確認できます。また、[解答集](https://docs.google.com/spreadsheets/d/1jIxjzUWG-6xBVIa2ay6yDpLyeuOh_hR_ZB75a47KX_E/edit?usp=sharing)も用意されています。

注意: このチュートリアルでは、最小・最速・最安のモデルであるClaude 3 Haikuを使用しています。Anthropicには[他に2つのモデル](https://docs.anthropic.com/claude/docs/models-overview)、Claude 3 SonnetとClaude 3 Opusがあり、これらはHaikuよりも知能が高く、Opusが最も知能が高いモデルです。

*このチュートリアルは[Google SheetsのAnthropic's Claude for Sheets拡張機能を使用したバージョン](https://docs.google.com/spreadsheets/d/19jzLgRruG9kjUQNKtCg1ZjdD6l6weA6qRXG5zLIAhC8/edit?usp=sharing)でも利用可能です。より使いやすいため、そちらのバージョンをお勧めします。*

準備ができたら、`01_Basic Prompt Structure`に進んでください。

## 目次

各章はレッスンと一連の演習で構成されています。

### 初級
- **第1章:** 基本的なプロンプト構造

- **第2章:** 明確で直接的な表現

- **第3章:** 役割の割り当て

### 中級
- **第4章:** データと指示の分離

- **第5章:** 出力のフォーマットとClaudeの代弁

- **第6章:** 予知（ステップバイステップの思考）

- **第7章:** 例の使用

### 上級
- **第8章:** 幻覚の回避

- **第9章:** 複雑なプロンプトの構築（産業用途）
  - ゼロからの複雑なプロンプト - チャットボット
  - 法務サービスのための複雑なプロンプト
  - **演習:** 金融サービスのための複雑なプロンプト
  - **演習:** コーディングのための複雑なプロンプト
  - おめでとうございます＆次のステップ

- **付録:** 標準的なプロンプト以上のテクニック
  - プロンプトのチェーン
  - ツールの使用
  - 検索と取得