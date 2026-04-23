# 本音・建前付き日本語対話データセット

## 概要 (Overview)
本データセットは、日本語の対話データに対して「**本音**」と「**建前**」の応答を付与したものです。 
対話に対して、本音と建前を付与した対話ID（dialogue_id）と対話のターン番号（turn_num），本音（honne）と建前（tatemae）を示しています。
曖昧な日本語の言語表現を識別する研究が可能です。


### 元データ
- [JDD (Japanese Daily Dialogue)](https://github.com/jqk09a/japanese-daily-dialogue)  
- [BSD (The Business Scene Dialogue corpus)](https://github.com/tsuruoka-lab/BSD)

## データ件数 (Statistics)

| データ | 本音 & 建前 (件数) |
|------------|--------------|
| JDD: Japanese Daily Dialogue | 7,040 |
| BSD: The Business Scene Dialogue corpus | 924 |

---

## データ例
```
{
    "dialogue_id": "190329_J05_02",
    "topic_name": "Dailylife",
      {
        "turn_num": 3,
        "speaker": "A",
        "honne": "郵便局にいくのは手間です。",
        "tatemae": "メールやSMSの方が便利です。"
      }
    ]
  },
```
