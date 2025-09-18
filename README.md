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
  "dialogue_id": "daily_001",
  "turn_id": 0,
  "speaker": "A",
  "utterance": "今度の飲み会、楽しみだね。",
  "label": "tatemae"
}
{
  "dialogue_id": "daily_001",
  "turn_id": 1,
  "speaker": "B",
  "utterance": "うん、でも正直あんまり行きたくないんだよね。",
  "label": "hon-ne"
}
```
