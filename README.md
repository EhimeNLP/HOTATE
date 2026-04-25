[English](README.md) | [日本語(Japanese)](README-ja.md)
# HOTATE

## Overview
This dataset consists of Japanese dialogue data annotated with both **Honne** (Private Thoughts) and **Tatemae** (Public Statements) responses.  
Each entry includes the dialogue ID (`dialogue_id`), the dialogue genre (`topic_name`), the turn number (`turn_num`), and the corresponding `honne` and `tatemae` expressions.   
This dataset enables research into identifying and analyzing ambiguous linguistic expressions in Japanese. 

### Source data
- [BSD (The Business Scene Dialogue corpus)](https://github.com/tsuruoka-lab/BSD)
- [JDD (Japanese Daily Dialogue)](https://github.com/jqk09a/japanese-daily-dialogue)  

## Dataset size
| Data | Private Thoughts & Public Statements (Dataset Size) |
|------------|--------------:|
| BSD: The Business Scene Dialogue corpus | 924 |
| JDD: Japanese Daily Dialogue | 7,040 |

---

## Example
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

## Citation
* Yuko Toda, Daisuke Maekawa, Kota Manabe, Eito Yoneyama, Kanade Nonomura, Yuki Fujiwara, Tomoyuki Kajiwara.  
HOTATE: A Japanese Dialogue Corpus Annotated with Responses of Private Thoughts and Public Statements.  
In Proceedings of the 15th International Conference on Language Resources and Evaluation ([LREC 2026](https://lrec2026.info/)), Mallorca, Spain, May 2026. [to appear]

* 戸田裕子, 前川大輔, 眞鍋光汰, 米山瑛人, 野々村奏, 藤原有希, 梶原智之.  
HOTATE：本音と建前の応答対からなる対話コーパスの構築.  
言語処理学会第32回年次大会, pp.1748-1752, March 2026. \[[PDF](https://anlp.jp/proceedings/annual_meeting/2026/pdf_dir/P4-3.pdf)\]  
