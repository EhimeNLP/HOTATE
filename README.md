# 本音・建前付き日本語対話データセット

## 概要 (Overview)
本データセットは、日本語の対話データに対して「**本音**」と「**建前**」の応答を付与したものです。  
曖昧な日本語の言語表現を識別する研究が可能です。


### 元データ
- [Japanese Daily Dialogue](https://github.com/jqk09a/japanese-daily-dialogue)  
- [BSD (Balanced Scenario Dialogue)](https://github.com/tsuruoka-lab/BSD)

## データ件数 (Statistics)

| データ | 本音 & 建前 (件数) |
|------------|--------------|
| BSD: Business Sence Dialogue | 924 |
| JDD: Japanese Daily Dialogue | 7,040 |

---

## データ例
```
{
    "dialogue_id": "190329_J05_02",
    "topic_name": "Dailylife",
    "utterances": [
      {
        "turn_num": 1,
        "speaker": "A",
        "utterance": "あなたは、郵便局で年賀状を出したことはありますか？",
        "honne": "",
        "tatemae": ""
      },
      {
        "turn_num": 2,
        "speaker": "B",
        "utterance": "ありません。そもそも、郵便局に行く機会自体がほとんどありません。",
        "honne": "",
        "tatemae": ""
      },
      {
        "turn_num": 3,
        "speaker": "A",
        "utterance": "確かにそうかもしれませんね。僕も普段はメールやSMSで済ませてしまいます。",
        "honne": "郵便局にいくのは手間です。",
        "tatemae": "メールやSMSの方が便利です。"
      }
    ]
  },
```
