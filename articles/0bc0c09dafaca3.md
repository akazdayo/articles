---
title: "Proton上のVRChatで動画/配信を再生する"
emoji: "🐾"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: ["Linux", "Proton", "VRChat"]
published: true
---

## 問題
Linux上のVRChatで動画プレイヤーを再生できない。または、動画は再生できるけどRTSP/RTSPT(リアルタイム配信)が再生できない

## 解決
GE-Protonまたは、GE-Proton-RTSPを使う
動画が再生したいだけであればGE-Protonで対応できますが、RTSPをサポートしていないため、何か問題が発生しない限りはGE-Proton-RTSPを使うと良さそうです。

### ProtonUpQtを使う
GE-Protonであれば、左下の`Add version`ボタンから簡単に追加できます。
RTSP版は、右下の`About`->`Enable advanced mode`を有効にし、GE-Protonと同様の方法で追加できます。
![](/images/0bc0c09dafaca3/advanced-mode.png)

追加後、Steamを完全に再起動し、`VRChat`->`プロパティ`->`互換性`->`特定のSteamPlay互換ツールの使用を強制する`で、追加したProtonを選べます。
