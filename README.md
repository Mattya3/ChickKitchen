

日程

```mermaid
gantt
    title ひよっこキッチン
    dateFormat  MM-DD
    excludes    weekends

    section  
        プロジェクト開始 : milestone, m1, 07-08, 0d
        α版完成 : milestone, m2, after a1, 0d
        β版完成 : milestone, m3, after a4, 0d
        最終完成 : milestone, m3, after b4, 0d

    section フロンサイド
        開発準備 :avtive, a1, 07-08, 2d
        開発A :active, a2, after a1, 7d
        開発B :active, a3, after a2, 7d
        開発C :active, a4, after a3, 5d

    section フロンサイド
        開発準備 :avtive, b1, 07-08, 2d
        開発A :active, b2, after b1, 7d
        開発B :active, b3, after b2, 7d
        開発C :active, b4, after b3, 5d
```