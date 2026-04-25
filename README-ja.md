# HOTATE

## 概要
本データセットは、日本語の対話データに対して「**本音**」と「**建前**」の応答を付与したものです。  
対話に対して、本音と建前を付与した対話ID (`dialogue_id`) と対話のジャンル (`topic_name`)、対話のターン番号 (`turn_num`) に加え、本音 (`honne`) と建前(`tatemae`) を示しています。曖昧な日本語の言語表現を識別する研究が可能です。  


### 元データ
- [BSD (The Business Scene Dialogue corpus)](https://github.com/tsuruoka-lab/BSD)
- [JDD (Japanese Daily Dialogue)](https://github.com/jqk09a/japanese-daily-dialogue) 

## データ件数
| データ | 本音 & 建前 (件数) |
|------------|--------------|
| BSD: The Business Scene Dialogue corpus | 924 |
| JDD: Japanese Daily Dialogue | 7,040 |

---

## データ例
```
{
    "dialogue_id": "166",
    "topic_name": "Dailylife",
    "utterance": {
        "turn_num": 3,
        "honne": "郵便局にいくのは手間です。",
        "tatemae": "メールやSMSの方が便利です。"
    }
}
```

## 文献情報
* Yuko Toda, Daisuke Maekawa, Kota Manabe, Eito Yoneyama, Kanade Nonomura, Yuki Fujiwara, Tomoyuki Kajiwara.  
HOTATE: A Japanese Dialogue Corpus Annotated with Responses of Private Thoughts and Public Statements.  
In Proceedings of the 15th International Conference on Language Resources and Evaluation ([LREC 2026](https://lrec2026.info/)), Mallorca, Spain, May 2026. [to appear]

* 戸田裕子, 前川大輔, 眞鍋光汰, 米山瑛人, 野々村奏, 藤原有希, 梶原智之.  
HOTATE：本音と建前の応答対からなる対話コーパスの構築.  
言語処理学会第32回年次大会, pp.1748-1752, March 2026. \[[PDF](https://anlp.jp/proceedings/annual_meeting/2026/pdf_dir/P4-3.pdf)\]  
