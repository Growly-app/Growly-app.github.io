# リスニング（`courses/リスニング/`）

英文法と **同じ 6 教材・同じステージ名・同じ `sentence_ids`** の `course.json` を置いています（本文・音声パスも同じ）。

| フォルダ | 対応する英文法 |
|----------|----------------|
| `yarinaoshi_basic1/` | `../英文法/yarinaoshi_basic1/` |
| `yarinaoshi_basic2/` | `../英文法/yarinaoshi_basic2/` |
| `yarinaoshi_basic3/` | `../英文法/yarinaoshi_basic3/` |
| `jh_grammar_1/` | `../英文法/jh_grammar_1/` |
| `jh_grammar_2/` | `../英文法/jh_grammar_2/` |
| `jh_grammar_3/` | `../英文法/jh_grammar_3/` |

各 `course.json` には **`mirror_of`**（英文法側の相対パス）と、リスニング用である旨の **`notes_ja`** があります。

**運用**: ステージや文 ID を変えるときは **英文法を正**として編集し、必要なら同内容をこちらへコピーして同期する。

`catalog.json` では `course_id` が `listening_*`（例: `listening_yarinaoshi_basic1`）で、英文法の `yarinaoshi_basic1` とは別エントリです。
