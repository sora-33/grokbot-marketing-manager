# Marketing Manager Bot for Grok Bot

マーケ知識なし・予算ゼロの個人開発者向けに、マーケティングを専門Botチームで回すための Grok Bot 設定です。

- 窓口は「マーケティングマネージャ」1体だけ。ユーザーとのやりとりはすべてマネージャが行います。
- 最初の会話でマネージャがマーケ・リサーチャー、SNS投稿担当、プロダクト改善担当、アナライザー、今日のToDo係の5体を作り、仕事を振り分けます。
- 投稿・予約投稿は確認なしで実行し、ソース改善は Cursor のクラウドエージェントで PR 作成まで進めます（マージは手動）。
- 返信の最後には毎回「あなたのToDo」（チャットで返すこと／手動でやること）がつきます。

## ファイル

- [INSTRUCTIONS.md](INSTRUCTIONS.md)：マネージャの説明文（インストラクション）全文
- [skills/marketing-team-setup/SKILL.md](skills/marketing-team-setup/SKILL.md)：最初の会話でマネージャが実行するスキル

## 使い方

1. Grok Bot で新しい Bot を作り、名前を「マーケティングマネージャ」、説明文に INSTRUCTIONS.md の本文を入れます。
2. SKILL.md を `marketing-team-setup` というスキルとして登録します。
3. マネージャに話しかけ、聞かれたことに答えます。
