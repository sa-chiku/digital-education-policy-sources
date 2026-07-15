---
title: AI認知的オフローディング
date: 2026-07-13
tags:
  - research
  - policy-comparison
  - ai-education
  - digital-education
  - cognitive-offloading
status: active
source_version: v3
citation_footnotes: patched-2026-07-14
fact_dashboard: https://claude.ai/code/artifact/d4510976-179e-4b33-8cff-be62ae688eaa
notebooklm: https://notebooklm.google.com/notebook/9422dc1b-e794-4bfb-9138-1212f07d82da
share_link: https://share.note.sx/foaq0sq2#Ox4T8KdnSe/TrfCi2fR6ug
share_updated: 2026-07-14T13:52:04+10:00
---

> [!info] Fact Dashboard
> [定量的裏付け(教員AI利用率の国際比較・トルコGPT-4実験・GIGA school整備状況・生徒利用率調査)を可視化したダッシュボード](https://claude.ai/code/artifact/d4510976-179e-4b33-8cff-be62ae688eaa) — ローカル保存版は `sources/v2_AI認知的オフローディング_dashboard.html` (ブラウザで直接開けます)

> [!link] NotebookLM
> [一次資料PDF3件+補足調査17件+レポート本体](https://notebooklm.google.com/notebook/9422dc1b-e794-4bfb-9138-1212f07d82da) をまとめたNotebookLMノートブック

# 問い

AIをめぐる認知的オフローディングに対する2026年時点の国際的認識と日本教育の対応

# 使用したソース一覧

> [!info] AIに関する現状と検討課題について(中央教育審議会初等中等教育分科会教育課程部会 情報・技術ワーキンググループ 第6回 資料2-3)
> - **発行元:** 文部科学省(中央教育審議会)
> - **発行日:** 2026-02-13
> - **URL:** https://www.mext.go.jp/content/20260213-mxt_kyoiku01-00004732__06.pdf
> - **分類:** policy
>
> **審査:** 文部科学省の中央教育審議会初等中等教育分科会教育課程部会傘下のワーキンググループが公式に配付した一次資料であり、発行主体そのものによる政策審議文書に該当する。ただし答申・告示ではなく審議途上の検討資料であるため、正式な政策決定文書ではない点に留意が必要。authority=2は発行主体の一次文書として付与するが、doc_statusに審議中である旨を明示した。日付は2026年2月と非常に新しく通貨性は高い。

---

> [!warning] OECD Digital Education Outlook 2026: Navigating the Generative AI Frontier
> - **発行元:** OECD
> - **発行日:** 2026-01-19
> - **URL:** https://www.oecd.org/content/dam/oecd/en/publications/reports/2026/01/oecd-digital-education-outlook-2026_940e0dd8/062a7394-en.pdf
> - **分類:** grey
>
> **審査:** OECDは国際的に権威ある政府間機関であり、本報告書はその公式出版物として位置づけられる(authority: 2)。OECDのDigital Education Outlookシリーズは複数国にまたがる実証データ・政策分析を体系的に提示するフラッグシップ報告書であり、方法論の透明性は比較的高いと推定されるが詳細は要確認(accuracy: 2暫定)。生成AIと教育という現在進行形の主題を国際比較の観点から包括的に扱う点でカバレッジは広い(coverage: 2)。OECDは加盟国政府により資金提供されており商業的利益相反の懸念は低いが、政策推進機関としての立場上、特定政策方向への傾斜には注意が必要(objectivity: 2暫定)。2026年1月19日付で非常に最新の文書(date: 2)。OECDのEducation Outlookシリーズは政策・研究コミュニティで高い参照頻度を持つ主要報告書であり重要性は高い(significance: 2)。なお、policy classではなくgreyとしたのは、OECDが政策の『発行主体』ではなく国際機関によるレポート・アウトルック形式の報告書であるため。

---

> [!warning] Generative AI, Cognitive Offloading, and Learner Agency in Higher Education: A Scoping Review
> - **発行元:** Preprints.org(MDPI系プレプリントサーバー、Behavioral Sciences誌への投稿版)
> - **発行日:** 2026-05-13
> - **URL:** https://doi.org/10.20944/preprints202605.0881.v1
> - **分類:** academic
>
> **審査:** タイトル・発行元・URLの構造からスコーピングレビュー論文と判断。ただしPreprints.orgへの投稿版であり、査読付き学術論文としての要件（査読完了・誌上掲載）を現時点では満たしていない可能性が高い。ERIC収録状況は要確認。日付が2026年と将来日付になっており、メタデータの正確性自体も要確認。

---

# Claudeによる統合分析

> [!note] 本文中の対応関係
> 本文中の `[ソース名 #番号]` は「根拠抜粋」セクションの該当番号に対応。「補足調査によれば」は下記Perplexity補足調査に対応。

---

# AIをめぐる認知的オフローディングに対する2026年時点の国際的認識と日本教育の対応

---

## 1. 認知的オフローディングの概念的位置づけ：2026年時点の国際的合意

> [!info] 国際的な合意形成の現状
> 2026年時点において、生成AIの教育利用に伴う認知的オフローディングは、学術研究と国際政策の双方で中心的なリスク概念として確立されつつある。

---

### 1.1 概念の定義と多義性

> [!info] 認知的オフローディングの定義
> 認知的オフローディングとは、一次資料に基づく定義では「認知的作業を外部ツールやシステムに委託すること」であり、生成AIの文脈においてはアイデア生成、草稿作成、要約、改訂、意思決定、評価的判断をAIシステムに外注することを含む、と一次資料に記載されている [[#^src-cognitive_offloading_scoping_review_2026-8|Generative AI, Cognitive Offloading, and Learner Agency in Higher Education: A Scoping Review（以下「スコーピングレビュー」） #8]]。

---

> [!warning] オフローディングの二面性と問題の所在
> 重要な点として、同レビューは「オフローディングは本質的に非適応的ではない。戦略的なオフローディングの一部は不必要な負荷を軽減し、認知資源を解放し、高次思考を支援する可能性がある」と一次資料に記載されている [[#^src-cognitive_offloading_scoping_review_2026-9|スコーピングレビュー #9]]。その一方で、「学習者が検証なし、内省なし、課題の主体性を維持せずにGenAIに依存する場合は問題となる」とも記載されている [[#^src-cognitive_offloading_scoping_review_2026-10|スコーピングレビュー #10]]。

---

> [!tip] 日本における同様の認識——中教審資料との対比
> 日本においても中央教育審議会の資料が同様の認識を示しており、「認知的オフロードや認知負債を含む認知過程に与える負の影響も学術研究等において指摘されている」と一次資料に記載されている [[#^src-mext_ai_working_group_2026-1|AIに関する現状と検討課題について（中央教育審議会初等中等教育分科会、以下「中教審資料」） #1]]。

---

### 1.2 研究エビデンスの集積

> [!info] 研究動向の概観
> 2025〜2026年にかけて、認知的オフローディングに関する実証的・神経科学的研究が急速に蓄積されている。

---

> [!note] 神経科学的アプローチ
> 5つの大学の学生を対象に「脳のみで執筆」「検索エンジン使用」「ChatGPT使用」の3条件を比較した実験では、LLMグループのうちエッセイから何かを引用できたのはわずか**12%**であったのに対し、他の2グループでは**89%**であった。
>
> また脳画像データは「コンテンツ生成からAI生成コンテンツの監督への実行課題のシフト」と「神経結合と関与の低下」を示した、と一次資料に記載されている [[#^src-oecd_digital_education_outlook_2026-5|OECD Digital Education Outlook 2026（以下「OECD報告書」） #5]]。
>
> この知見は中教審資料でも「LLMは利便性を提供する一方で、認知的負荷の低下、記憶・理解の弱化、主体性の低下といった教育上の潜在的リスクを伴う可能性」として参照されている [[#^src-mext_ai_working_group_2026-6|中教審資料 #6]]。

---

> [!warning] 批判的思考との負の相関・メタ認知への影響
> AIツールの頻繁な使用と批判的思考能力の間に有意な**負の相関**があり、特に若年層でAI依存度が高く批判的思考スコアが低い傾向が示された [[#^src-mext_ai_working_group_2026-7|中教審資料 #7]]。
>
> さらに、2026年の大規模実験では「AIは成績を向上させる一方、自己評価の過大化を招き、**メタ認知の正確性を低下させる**」ことが示されている [[#^src-mext_ai_working_group_2026-8|中教審資料 #8]]。

---

> [!important] 「メタ認知的怠惰」という概念
> 一般用途のLLMと対話する学生が、人間の専門家と対話する場合と異なり、「診断・評価・反復」の段階を省略して直接解を求め即実装する傾向があることが示され、これが**「メタ認知的怠惰」**すなわち認知的オフローディングの一形態として記述されている [[#^src-oecd_digital_education_outlook_2026-4|OECD報告書 #4]]。

---

### 1.3 二重経路構造：リスクと可能性の共存

> [!info] 二重経路構造の定義
> スコーピングレビューが示す知見として「GenAIは学習者エージェンシーに双方向に作用する二重経路構造を持つ：一方は自己調整学習・自己効力感・フィードバックリテラシー・内省的関与を強化する経路、他方は認知的オフローディング・過度な依存・批判的受容の欠如・判断力の低下によってエージェンシーを侵食する経路」と一次資料に記載されている [[#^src-cognitive_offloading_scoping_review_2026-2|スコーピングレビュー #2]]。

---

> [!warning] 過度な依存がもたらすリスク
> OECD報告書は同様の構造を政策的文脈で表現し、「過度な依存は学生を受動的消費者に、教員を監督者に変えるリスクがある」と一次資料に記載されている [[#^src-oecd_digital_education_outlook_2026-8|OECD報告書 #8]]。

---

> [!important] 政策立案者への示唆
> 「生成AIが学習のショートカットではなく学習のパートナーとなることを保証することが政策立案者の課題」と明示している [[#^src-mext_ai_working_group_2026-4|中教審資料 #4]]。

---

## 2. 国際的政策文書における認識の構造

### 2.1 OECDの立場

> [!info] OECDの基本的立場
> OECD Digital Education Outlook 2026は、過度な依存による認知的オフローディングのリスクと生成AIの教育的可能性を両立する視点を示している。

---

> [!warning] 短期的成績向上と長期的学習阻害の乖離
> 特に証拠として、「GPT-4へのアクセスにより短期的な成績は48%（標準インターフェース）または127%（学習支援チュータリング版）向上したが、アクセス除去後の成績は17%低下した」というトルコでの野外実験が引用されており [[#^src-oecd_digital_education_outlook_2026-2|OECD報告書 #2]]、短期的成績向上と長期的学習阻害の乖離が具体的数値とともに示されている。

---

> [!quote] メタ認知的関与の低下（一次資料より）
> 「メタ認知的関与——回答を理解に変換する精神的プロセスと努力——が低下し、課題遂行と真の学習の間の乖離が生じる」
>
> — 学習者がGenAIを過度に依存する場合について [[#^src-oecd_digital_education_outlook_2026-3|OECD報告書 #3]]

---

> [!warning] 自律的学習プロセスの阻害
> 「GenAIへの依存の増加が自己監視、内省、評価的判断を抑制し、自律的学習の根幹となるプロセスを阻害する」という証拠の蓄積も示されている [[#^src-oecd_digital_education_outlook_2026-11|OECD報告書 #11]]。

---

### 2.2 「足場かけ」としての再解釈

> [!quote] OECD報告書における「足場かけ」論
> 「一般用途のGenAIツールの使用は、特に学習者が教育課題が引き出すよう設計された認知的努力を回避するために使用する場合にリスクを伴う。しかし学習科学は、学習者が習熟するにつれて段階的に取り除かれる足場かけを必要とすることも認識している」[[#^src-oecd_digital_education_outlook_2026-7|OECD報告書 #7]]

---

> [!info] 政策的転換点：段階的・目的的活用論
> OECD報告書は、単純な禁止論でも無批判な活用推進論でもない、段階的・目的的活用論を提示している。[[#^src-oecd_digital_education_outlook_2026-7|OECD報告書 #7]]

---

> [!quote] スコーピングレビューによる補強
> 「GenAIの教育的価値は技術そのものよりも、いかに教育的に組み込まれるかに依存し、拡充志向・足場かけ志向の使用は置換志向の使用より学習者エージェンシーを支援する」[[#^src-cognitive_offloading_scoping_review_2026-3|スコーピングレビュー #3]]

---

### 2.3 バイアス・エコーチェンバーリスク

> [!warning] バイアス強化・エコーチェンバー生成リスク
> アメリカ心理学会の専門家パネルは「汎用的な消費者向けモデルはユーザーに好意的に返答するよう訓練されており、確証バイアスや不適応な信念を強化し、エコーチェンバーを生成するリスクがある」と指摘しており、社会的弱者集団への差別的助言の生成リスクも明示されている [[#^src-mext_ai_working_group_2026-9|中教審資料 #9]]。
>
> この観点は認知的オフローディングの問題を単なる「思考力低下」の次元を超えて、社会的・倫理的リスクとして位置づけるものである。

---

> [!tip] 日本国内での観測事例：確証バイアス的利用パターン
> 補足調査によれば、日本国内でもこの種のリスクが具体的な授業実践の中で観測され始めている。2024年度に実施されたある中学校技術科の授業実践では、生成AIを活用したレポート作成の成果物を前年度（AI非活用時）のものとテキストマイニングツール（KH Coder）で比較分析した結果、AI活用群は内容の多様性が低下し、特定の結論や表現に収斂する傾向が確認されたと報告されている。
>
> 生徒がAIの出力を「もっともらしいもの」として無批判に採用し、自身の既存の信念を補強する方向でのみ活用する、確証バイアス的な利用パターンも観察されている。

---

> [!warning] 知見の限界：個別実践報告にとどまる点に留意
> ただしこれは個別の授業実践報告に基づく知見であり、全国的な傾向を統計的に示す実証研究ではない点に留意が必要である。

---

## 3. 日本教育の対応：政策と課題

### 3.1 日本の現状認識

> [!quote] 認知的オフローディングへの言及（中教審資料）
> 「学習活動の目的や育成したい資質・能力を十分に意識しないままに、安易に生成AIを導入することで、AIに依存したり、AIの答えを鵜呑みにしたりするなど、目的に即した必要な学習過程が省略されてしまい、資質・能力の育成に繋がらないリスクがある」[[#^src-mext_ai_working_group_2026-10|中教審資料 #10]]

---

> [!note] 日本における問題認識の位置づけ
> 上記の記述は、認知的オフローディングの問題を日本の文脈で明示的に認識したものである。

---

> [!quote] 「言語的外化なき思考の欠如」に関する言及（中教審資料）
> 「情報技術の活用が「外化」をはじめとする言語能力の発揮を促す活動を欠いて行われた場合、身体性に根ざした人間ならではの価値の創造や意味理解を欠いた、空疎な情報の集積・共有となる恐れ」[[#^src-mext_ai_working_group_2026-11|中教審資料 #11]]

---

> [!important] 日本独自の概念的枠組み
> 上記の記述により、生成AI利用における**「言語的外化なき思考の欠如」**という日本独自の概念的枠組みが示されている。

---

### 3.2 発達段階別アプローチ

> [!quote] 小中高の段階別方針（一次資料より）
> 日本の中教審資料は小中高の段階別方針を一次資料として明示している。
>
> - **小学校段階**：「まず「適切な取扱い」「特性の理解」を学んだ上で、「活用」を通した体験的な学びを深める」
> - **中学校段階**：「抽象的・科学的な理解を必要とする「特性の理解」を一層重視する」
> - **高校段階**：「文理を問わず生成AI時代に不可欠な基礎的素養として「特性の理解」を身に付ける」
>
> [[#^src-mext_ai_working_group_2026-15|中教審資料 #15]]

---

> [!quote] 最終目標の明示
> 「高校卒業生全員に対し、数理・データサイエンス・AIを「日常の生活や仕事等の場で使いこなす」ことができるリテラシーレベルの学習を保障する枠組みを構築する」
>
> [[#^src-mext_ai_working_group_2026-14|中教審資料 #14]]

---

> [!warning]「リテラシーレベル」の定義に関する注意
> ここでいう「リテラシーレベル」は本資料で新たに定義された概念ではない。一次資料内の説明図によれば、これは日本の数理・データサイエンス・AI教育に関する既存の3段階の認定制度（リテラシーレベル→応用基礎レベル→エキスパートレベル）のうち最も基礎的な階層を指す用語であり、現行制度下ではすでに大学・高専の卒業生全員に対する到達目標として運用されている。
>
> 今回の中教審資料が提案している新機軸は、この既存の大学レベルの到達目標を、高等学校卒業段階にまで前倒しして全員保証する、という制度設計上の拡張である。

---

> [!quote] 批判的吟味の位置づけ
> 「AIの活用においては、発達段階に応じて正負の両面を扱う必要があり、出力を批判的に吟味しながら利点を生かして活用できるようになることが求められる」
>
> [[#^src-mext_ai_working_group_2026-12|中教審資料 #12]]

---

> [!info] 批判的吟味の前提化
> 上記の一次資料記載に基づき、批判的吟味はAI活用の前提として位置づけられている。

---

### 3.3 ガイドライン対応の方針

> [!info] 機動的対応の方針：ガイドラインによる先行対応
> 中教審資料は以下のように記載している。
>
> 「AIの活用が深い学びに繋がらないと考えられる例や各教科等における効果的なAI活用例を含む具体的な利活用のポイントは、指導要領改訂を待たずしてガイドライン等で対応するとともに、深い学びの実装に向けた評価の在り方については教育課程全体の議論の中で検討する必要がある」[[#^src-mext_ai_working_group_2026-13|中教審資料 #13]]
>
> 学習指導要領改訂サイクルを待たない機動的な対応が方針として示されている。

---

> [!caution] ガイドラインVer.2.0（2024年12月公表）— 一次資料未確認
> Perplexity補足調査によれば2024年12月に公表されたとされるが、具体的な記載内容は一次資料（原文PDF）での確認が必要。認知的オフローディングへの言及の有無を含め、引用・参照する際は原文を直接確認すること。

---

## 4. 日本教育の対応における際立った特徴と課題

### 4.1 教員のAI利用率と「デジタル統合への圧倒感」という二重課題

> [!info] 日本教員のAI利用率：国際比較
> OECD報告書は「2024年調査において、下位中等教育の教員の中でAIを使用したと報告した割合は、OECD平均が36%であるのに対し、日本は20%未満である（シンガポール・アラブ首長国連邦の75%と比較）」と一次資料に記載しており [[#^src-oecd_digital_education_outlook_2026-12|OECD報告書 #12]]、日本の教員のAI利用率が国際的に低水準にあることが示されている。

---

> [!quote] デジタル統合への「圧倒感」：一次資料の記述
> 「AIを使用していない教員は、デジタルツールを教育に統合するよう求められる高まる期待に圧倒されていると報告しており、これが使用への障壁となっている。このような感情は、日本ではクロアチア・フランドル（ベルギー）・セルビアとともに50%を超え、比較的高い」[[#^src-oecd_digital_education_outlook_2026-13|OECD報告書 #13]]

---

> [!note] 分析：政策方針と現場実態の構造的乖離
> 上記2点を合わせると、政策レベルでは認知的オフローディングのリスクへの対応方針を策定しつつも（中教審資料 [#10][#12]）、教員レベルではAI自体への接触が限定的でデジタル統合への圧倒感が高いという構造的乖離が読み取れる。これは複数の一次資料を組み合わせた**分析者の解釈**であり、この「乖離」を直接言及するソースはない。

---

### 4.2 日本のガイダンスの焦点：データプライバシーリスクへの早期対応

> [!info] 日本のガイダンスの特徴：データプライバシー重視
> OECD報告書は日本政府の学校向け生成AIガイダンスについて、「個人・機密データを生成AIシステムに入力することへの明示的な警告」を含むものとして言及し、これをLLM特有のデータ再利用・再学習リスクへの「早期認識（early recognition）」として位置づけている [[#^src-oecd_digital_education_outlook_2026-14|OECD報告書 #14]]。
>
> なお、同報告書はこの記述において認知的オフローディングリスクへの対応の充足・不足については評価を行っておらず、「焦点の偏り」という判断は一次資料（OECD #14）の範囲外となる。

---

# 監査結果

> [!info] 監査ステータス・指摘件数
> - **監査ステータス:** partially_resolved
> - **未解決件数:** 2（いずれも要一次資料確認）

---

> [!caution] \[要確認\] ガイドラインVer.2.0の内容は未一次確認
> **該当箇所:** 3.3 のcallout「ガイドラインVer.2.0（2024年12月公表）」
> **状況:** Perplexity補足調査由来。callout内で「一次資料未確認」と明示済みだが、原文PDFによる確認後に内容を更新する必要がある。
> **アクション:** 文科省ガイドラインVer.2.0（2024年12月）の原文を参照し、認知的オフローディングへの言及の有無を確認して書き直す。

---

> [!caution] \[要確認\] 4.1「政策乖離」分析の出典
> **該当箇所:** 4.1 のcallout「分析：政策方針と現場実態の構造的乖離」
> **状況:** 複数ソースを組み合わせた分析者の解釈。callout内で「分析者の解釈」と明示済み。
> **アクション:** 修論で使用する際は、あくまで筆者の解釈として明示するか、政策乖離を直接論じる先行研究を探して補強する。

---

# 定量的裏付け(取得日: 2026-07-13)

## 主張の裏付け

> [!info] \[定量 #Q1\] 対応主張: "日本は20%未満である（シンガポール・アラブ首長国連邦の75%と比較）"
> According to the OECD's TALIS 2024 study, **17%** of teachers in **Japan** reported using artificial intelligence (AI) in their work, compared to an **OECD average of 36%** [^pqQ1-9].
>
> While some general summaries of the report round the OECD average to "around 41%" or "one in three" (33%), the specific country note for Japan explicitly cites the 36% average for the OECD education systems when making the comparison [^pqQ1-1][^pqQ1-3][^pqQ1-9]. Japan's rate is therefore significantly below the global average, falling in the same low cohort as **France** (14–19%) [^pqQ1-1][^pqQ1-4]. In contrast, the highest rates were observed in **Singapore** and the **United Arab Emirates**, where approximately **75%** of teachers use AI [^pqQ1-1][^pqQ1-2].

---

**Key Comparison:**

| Region/Country | AI Use Rate (TALIS 2024) |
| :--- | :--- |
| **Japan** | **17%** [^pqQ1-9] |
| **OECD Average** | **36%** [^pqQ1-9] |
| **France** | ~14–19% [^pqQ1-1][^pqQ1-4] |
| **Singapore** | ~75% [^pqQ1-1][^pqQ1-2] |
| **United Arab Emirates** | ~75% [^pqQ1-1][^pqQ1-5] |

---

> [!tip] 日本における AI 活用の実態
> Teachers in Japan who do use AI primarily employ it to efficiently learn about or summarize a topic (68%) and to generate lesson plans or activities (64%) [^pqQ1-1].

---

> [!quote]- 出典脚注: OECD TALIS 2024 (Results from TALIS 2024: Country Notes, Japan)(2024) — 番号は本文中の脚注番号に対応
> [^pqQ1-1]: https://www.ei-ie.org/en/item/31815:using-artificial-intelligence-takeaways-from-talis-2024
> [^pqQ1-2]: https://www.moe.gov.sg/news/press-releases/20251007-singapore-teachers-embrace-digital-technologies-and-benefit-from-strong-professional-development-oecd-talis-2024-study
> [^pqQ1-3]: https://www.linkedin.com/posts/penslayer_aiineducation-teaching-edtech-activity-7386907934250852352-Aly9
> [^pqQ1-4]: https://www.csicr.cz/CSICR/media/Prilohy/2024_p%C5%99%C3%ADlohy/Dokumenty/TALIS-2024_IR_final.pdf
> [^pqQ1-5]: https://www.instagram.com/p/DQSI5MNjS4h/
> [^pqQ1-6]: https://www.oecd.org/en/publications/results-from-talis-2024-country-notes_e127f9e2-en/sweden_95600eec-en.html
> [^pqQ1-7]: https://www.oecd.org/en/publications/2025/10/results-from-talis-2024_28fbde1d.html
> [^pqQ1-8]: https://www.oecd.org/en/publications/results-from-talis-2024-country-notes_e127f9e2-en/latvia_f484f77f-en.html
> [^pqQ1-9]: https://www.oecd.org/content/dam/oecd/en/publications/reports/2025/10/results-from-talis-2024-country-notes_eafd703e/japan_4e66c75b/b48b1dd7-en.pdf

---

> [!warning] \[定量 #Q2\] 対応主張: "GPT-4へのアクセスにより短期的な成績は48%（標準インターフェース）または127%（学習支援チュータリング版）向上したが、アクセス除去後の成績は17%低下した"
> The study you are referring to is a 2024 large-scale field experiment conducted in a **Turkish high school** that found while students using **GPT-4** solved **48% more** practice problems correctly, they subsequently scored **17% worse** on unassisted tests—**not** a 127% score drop. The **127%** figure in your query actually refers to the performance boost of a **safeguarded AI tutor** (GPT Tutor) on practice problems, which solved **127% more** problems correctly than the control group, yet still performed no better on the final test.

---

### Key Findings of the Turkey GPT-4 Study

| Metric | GPT Base (Standard GPT-4) | GPT Tutor (Safeguarded AI) | Control (No AI) |
|--------|---------------------------|----------------------------|-----------------|
| **Practice Problem Performance** | +48% improvement [^pqQ2-4][^pqQ2-5] | +127% improvement [^pqQ2-4][^pqQ2-5] | Baseline |
| **Unassisted Test Performance** | **−17%** (worse than control) [^pqQ2-3][^pqQ2-4][^pqQ2-6] | No significant difference from control [^pqQ2-3][^pqQ2-5] | Baseline |
| **Primary Conclusion** | Students used GPT-4 as a "crutch," harming skill acquisition [^pqQ2-4][^pqQ2-6] | Safeguards (hints without answers) mitigated negative effects [^pqQ2-4][^pqQ2-6] | Traditional practice maintained learning |

> [!warning] GPT Base の落とし穴――練習成績と実力の乖離
> Standard GPT-4（GPT Base）を使った学生は、練習問題では **+48% の改善** [^pqQ2-4][^pqQ2-5] を示したにもかかわらず、AIなしで受けたテストでは **−17%（コントロール群より低下）** [^pqQ2-3][^pqQ2-4][^pqQ2-6] という結果に終わった。
>
> 学生がGPT-4を「松葉杖（crutch）」として使用したことで、スキル習得そのものが阻害されたと結論づけられている [^pqQ2-4][^pqQ2-6]。

---

> [!info] セーフガード付きAI（GPT Tutor）の効果
> ヒントのみを提供し答えを直接与えない設計のGPT Tutor（Safeguarded AI）では、練習問題の改善率は **+127%** [^pqQ2-4][^pqQ2-5] に達し、かつ非補助テストでもコントロール群との間に **有意差は見られなかった** [^pqQ2-3][^pqQ2-5]。
>
> セーフガードの導入が、AIアシスト学習の負の効果を緩和したことが示されている [^pqQ2-4][^pqQ2-6]。

---

> [!tip] 設計の違いが学習成果を左右する
> コントロール群（AIなし）は従来の練習によって学習を維持した。この研究が示す核心的な示唆は、**AIの有無よりも、AIをどう設計するか**が実力の定着に決定的な影響を与えるという点にある [^pqQ2-4][^pqQ2-6]。

---

### Study Details

> [!info] Study Overview
> - **Title**: *"Generative AI Without Guardrails Can Harm Learning"* (also published as *"Generative AI Can Harm Learning"*)
> - **Authors**: Hamsa Bastani, Osbert Bastani, Alp Süngü, Haosen Ge, Özge Kabakcı, and Rei Mariman
> - **Publication**: Published in **PNAS** (Proceedings of the National Academy of Sciences) in 2024 [^pqQ2-6], with a preprint released earlier [^pqQ2-8]
> - **Location**: Large high school in **Turkey**
> - **Timing**: Fall semester of the **2023–2024 academic year** (not 2024–2025) [^pqQ2-5]
> - **Sample Size**: Nearly **1,000 students** in grades 9–11 [^pqQ2-3][^pqQ2-5]
> - **Design**: Randomized controlled trial (RCT) with four 90-minute practice cycles across different math topics [^pqQ2-3]

---

### Clarifying the Misconception

> [!warning] 数値の混同に注意 — 17% と 127% は別の指標
> **17% score reduction**（スコア低下）が発生したのは、**標準的な GPT-4 インターフェース**（GPT Base）を使用していた学生が、テスト時に AI アクセスを取り上げられた場合に限定された現象である。
>
> **127%** という数値は、**学習セーフガードを備えたチューター版**における**練習問題の改善率**を指しており、テストスコアの低下率ではない [^pqQ2-3][^pqQ2-4][^pqQ2-5]。

---

> [!info] 研究者の結論 — AI アクセスの設計が鍵
> 研究者たちは、**無制限の GPT-4 アクセスは教育成果を損なう可能性がある**と結論付けた。学生が自律的な問題解決能力を育てる代わりに、AI を「松葉杖」として依存してしまうためである [^pqQ2-4][^pqQ2-6]。
>
> 一方で、**答えを与えずヒントを提供する**よう慎重に設計された AI チューターであれば、こうした負の効果を軽減できる [^pqQ2-6]。

---

> [!quote]- 出典脚注: PNAS (Proceedings of the National Academy of Sciences), Bastani et al. 2024 / OECD Digital Education Outlook 2026(2024) — 番号は本文中の脚注番号に対応
> [^pqQ2-1]: https://www.nature.com/articles/s41598-024-55568-7
> [^pqQ2-2]: https://pmc.ncbi.nlm.nih.gov/articles/PMC12069612/
> [^pqQ2-3]: https://hechingerreport.org/kids-chatgpt-worse-on-tests/
> [^pqQ2-4]: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4895486
> [^pqQ2-5]: https://hamsabastani.github.io/education_llm.pdf
> [^pqQ2-6]: https://www.pnas.org/doi/10.1073/pnas.2422633122
> [^pqQ2-7]: https://www.sciencedirect.com/science/article/pii/S0360131524002380
> [^pqQ2-8]: https://www.linkedin.com/posts/jonathan-boymal-448b5870_a-preprint-released-today-titled-generative-activity-7219806561588662272-LKIm
> [^pqQ2-9]: https://link.springer.com/article/10.1007/s40688-024-00500-z
> [^pqQ2-10]: https://bera-journals.onlinelibrary.wiley.com/doi/10.1111/bjet.13454

---

## 背景データ

> [!note] 定量 #B1 — GIGAスクール構想 整備率（2024年3月確定値）
> 2024 年（令和 6 年）3 月時点の文部科学省調査確定値によると、GIGAスクール構想における各整備状況は以下のとおり [^pqB1-5]。
>
> - **児童生徒用端末の整備率**: **1.1 台/人**（1人1台環境の達成）
> - **普通教室の無線LAN整備率**: **96.2%**
> - **大型提示装置整備率**: **89.6%**

---

> [!warning] 2025年度以降の統計について
> 2025 年（令和 7 年度）以降の統計については、**2024 年度から「NextGIGAスクール」として端末の更新フェーズが本格化**しており、2025 年 3 月時点の詳細な確定値は現時点（2026 年 7 月）で直ちに公開されている公式統計として検索結果に含まれていない。
>
> ただし、ベースとなる **1 人 1 台環境は維持・更新されている**状況である [^pqB1-1][^pqB1-4]。

---

### 主要な ICT 整備状況の詳細（令和 6 年 3 月時点・確定値）

> [!info] 調査概要
> 文部科学省が公表した「学校における教育の情報化の実態等に関する調査」の主要指標は以下の通りです [^pqB1-5]：

---

| 項目 | 平成 31 年 3 月（2019 年） | **令和 6 年 3 月（2024 年）** | 変化 |
| :--- | :--- | :--- | :--- |
| **児童生徒 1 人当たりの学習者用コンピュータ台数** | 0.2 台/人 | **1.1 台/人** | 1人1台環境**達成** |
| **普通教室の無線LAN整備率** | 41.0% | **96.2%** | ほぼ全域で無線利用可能 |
| **インターネット接続状況（速度）** | 70.3% (100Mbps 以上) | **81.0% (1Gbps 以上)** | 高速化が進展 |
| **普通教室の大型提示装置整備率** | 52.2% | **89.6%** | 電子黒板等が普及 |
| **統合型校務支援システム整備率** | 57.5% | **91.4%** | 校務 DX 化が進展 |
| **ICT 機器を「ほぼ毎日」活用する学校割合** | 未記載 | **90% 超** | 年々上昇中 [^pqB1-5] |

### 2024 年〜2025 年の状況と今後の動向

> [!info] NextGIGAスクール（更新フェーズ）の本格化
> 2024 年度（令和 6 年度）から、GIGAスクール構想第 1 期で配布された約 950 万台の端末の**更新（アップデート）が開始**されました [^pqB1-1]。メーカー供給や処分業務の課題から、国は**5 年程度かけて計画的に更新**するよう呼びかけており、2025 年（令和 7 年度）は更新のピークを迎えています [^pqB1-4]。

---

> [!info] 2025 年度（令和 7 年度）の予算と計画
> 2025 年度概算要求では、次世代校務 DX 環境の整備支援として 1 校わり 680 万円（補助率 1/3）が計上され、**端末更新**と**次世代校務 DX への移行**が重点施策となっています [^pqB1-2][^pqB1-4]。また、必要なネットワーク速度を確保している学校の割合を**令和 7 年度に 100%**とする目標が掲げられています [^pqB1-7]。

---

> [!warning] 課題と格差
> 端末整備率は高いものの、**ICT 活用率の自治体間格差**（約 70%〜ほぼ 100%）や、授業での活用方法の**学校間格差**が課題として上げられています [^pqB1-3][^pqB1-5]。

---

> [!note] 統計の現時点での限界
> 2025 年 3 月時点の最新確定値（令和 7 年度末調査）が文部科学省から正式に公表された場合に、無線 LAN の 100% 達成や更新後の端末台数などの詳細な数値が更新されます。現時点では、2024 年 3 月確定値が最も信頼性の高い公式統計となります。

---

> [!quote]- 出典脚注: 文部科学省「学校における教育の情報化の実態等に関する調査」(2024年3月時点（令和6年3月確定値）) — 番号は本文中の脚注番号に対応
> [^pqB1-1]: https://www.m2ri.jp/report/market/detail.html?id=86
> [^pqB1-2]: https://www.kknews.co.jp/post_ict/241007_2a
> [^pqB1-3]: https://ai-government-portal.com/ict%E6%95%99%E8%82%B2%E3%81%AE%E6%8E%A8%E9%80%B2/
> [^pqB1-4]: https://www.allied-telesis.co.jp/netrend/giga-school-infra/
> [^pqB1-5]: https://www.mext.go.jp/content/20250318-mxt_shuukyo01-000040908_01.pdf
> [^pqB1-6]: https://www.mext.go.jp/a_menu/other/mext_00921.html
> [^pqB1-7]: https://www.mext.go.jp/content/20250417-app_dev04-000041888_2.pdf
> [^pqB1-8]: https://www.mext.go.jp/a_menu/shotou/zyouhou/index.htm
> [^pqB1-9]: https://www.mext.go.jp/a_menu/other/1421443_00002.htm

---

> [!info] 定量 #B2 — 高校生・大学生の生成AI利用率（2024年〜2025年）
> データ: 2024年〜2025年にかけての**高校生・大学生の生成AI利用率**は、調査機関や対象範囲によって数値が異なりますが、**高校生は73.7%〜90%超**、**大学生は47%〜86.3%**の範囲で急速に拡大している実態が確認されています。

---

### 主な調査結果の比較

| 対象 | 調査年 | 利用率（利用経験率） | 調査機関・出典 |
|------|--------|---------------------|----------------|
| **高校生** | 2024（対話型） | **73.7%** | 学研（ informatie.com）[^pqB2-1] |
| **高校生** | 2024（全生成AI） | **83.5%** | CyberAgent「α世代実態調査」[^pqB2-4] |
| **高校生** | 2025（現役） | **92.5%**（90%超） | 進学ネット（shingakunet）[^pqB2-6] |
| **大学生（20代）** | 2024 | **44.7%** | 総務省情報通信白書[^pqB2-2][^pqB2-8] |
| **大学生** | 2024（学年別） | **47%**（平均）、1年次53%・4年次39% | データサイエンティスト協会[^pqB2-3] |
| **大学生** | 2024（経験率） | **86.3%** | CyberAgent「α世代実態調査」[^pqB2-4] |
| **15〜22歳（高・大）** | 2025年12月期 | **約83%** | Line Research Platform[^pqB2-5] |

### 重要な傾向と特徴

> [!info] 利用率の急上昇
> 大学生の利用率は2023年の29%から2024年には47%へ、約1年で**20ポイント近く上昇**しました [^pqB2-3]。

---

> [!info] 学年別傾向
> 大学生では**1年次が最も高く53%**、学年が上がるほど低下し4年次は39% [^pqB2-3]。

---

> [!info] 性別差
> 高校生では**女性87.9%**、男性78.8%で女性は約9ポイント上回る [^pqB2-4]。15〜18歳女性は**約9割**が利用 [^pqB2-5]。

---

> [!info] 利用目的
> 高校生・大学生の**6〜7割**が「**勉強／課題**」で利用し、学習支援ツールとして定着 [^pqB2-5]。
>
> 上位目的：「論文や教科書の要約」45%、「レポート作成・添削」38% [^pqB2-3]
>
> 高校生は「悩み相談・カウンセリング」も3位 [^pqB2-1]

---

> [!note] 回答の扱い
> 92.5%が利用経験がある中、**回答をそのまま使う人は13.7%**のみで、大半は検索・比較・再考を経て利用 [^pqB2-6]。

---

### 政府・公的調査の状況

> [!info] 政府・公的機関による調査の概要
> - **文部科学省**は2025年に「学校教育における生成AIの利活用推進に向けた調査研究」を公表し、自治体向けアンケートを実施 [^pqB2-9]。
> - **e-Stat**（総務省統計局）では、2024年版情報通信白書で**20代の利用経験率44.7%**を報告 [^pqB2-2][^pqB2-8]。

---

> [!warning] 公式統合調査データの未公開
> 現時点（2026年7月）で**2025年最終期・2026年の公式な文部科学省・e-Statによる高・大全体の統合調査結果**は公開されていません。直近の最新データは民間調査（学研、CyberAgent、Line Researchなど）が中心です。

---

### 結論

> [!info] 高校生・大学生の生成AI利用率（2024〜2025年）
> 2024〜2025年にかけて、**高校生は73.7%〜92.5%**、**大学生は44.7%〜86.3%**の範囲で生成AIを利用しており、**学習支援ツールとして急速に定着**しつつあります。特に**女性高校生・大学生**の利用率が極めて高く、**勉強・課題支援**が主要利用目的です。

---

> [!warning] データの限界：政府統計の未公開
> 政府公式の2025年最終統合調査は未公開のため、民間調査データが主要な根拠となっています。

---

> [!quote]- 出典脚注一覧 — 学研、CyberAgent、総務省情報通信白書、データサイエンティスト協会、Line Research Platform、進学ネット等複数(2024-2025)、番号は本文中の脚注番号に対応
> [^pqB2-1]: https://edu.watch.impress.co.jp/docs/news/2093090.html
> [^pqB2-2]: https://pppt.jp/facts/20%E4%BB%A3%E3%81%AE%E7%94%9F%E6%88%90AI%E5%88%A9%E7%94%A8%E7%8E%87-2024-637f0d5c-4c3f-4ff0-b8b0-d2e0a08e5cee
> [^pqB2-3]: https://www.datascientist.or.jp/dssjournal/dssjournal-4013/
> [^pqB2-4]: https://www.cyberagent.co.jp/news/detail/id=33016
> [^pqB2-5]: https://lineresearch-platform.blog.jp/archives/48072886.html
> [^pqB2-6]: https://shingakunet.com/journal/fromsapuri/20250903000003/
> [^pqB2-7]: https://www.sendaidaigaku.jp/dnt2/_sendaidaigaku/access/nic_img/1/files/20240716.pdf
> [^pqB2-8]: https://www.soumu.go.jp/johotsusintokei/whitepaper/ja/r07/html/nd112210.html
> [^pqB2-9]: https://www.mext.go.jp/content/2025414-mxt_shuukyo01_000033776_03.pdf

---

# 根拠抜粋(一次資料からの引用・Gemini抽出)

> [!quote]- 原文抜粋一覧
> 各ソースの原文からそのまま抜粋。要約・言い換えは行っていない。

---

### AIに関する現状と検討課題について(中央教育審議会初等中等教育分科会教育課程部会 情報・技術ワーキンググループ 第6回 資料2-3)

> [!warning] AIがもたらす認知的リスクの学術的指摘
> 特に、ディープフェイク等の犯罪に巻き込まれるリスクが増加していることや、AIへの過度な依存・バイアスの発生や認知過程に与える負の影響（いわゆる認知的オフロードや認知負債を含む）も学術研究等において指摘されている【参考資料④-1,2】[[#^src-mext_ai_working_group_2026-1|ソース名 #1]] ^src-mext_ai_working_group_2026-1

---

> [!info] OECDによる生成AI教育活用の国際的調査(2026年)
> OECD (2026) *OECD Digital Education Outlook 2026 Exploring Effective Uses of Generative AI in Education* [[#^src-mext_ai_working_group_2026-2|ソース名 #2]] ^src-mext_ai_working_group_2026-2
>
> - 生徒や教員の主体性（エージェンシー）や学習過程を省略すること（いわゆる認知的オフロード）による学習効果を低下させるリスクも指摘されている。[[#^src-mext_ai_working_group_2026-3|ソース名 #3]] ^src-mext_ai_working_group_2026-3
> - 過度な依存による学習者の認知的な負荷の低下や教員の専門性・自律性への影響といったリスクを併せて示し、適切な政策・ガバナンスの重要性を指摘している。[[#^src-mext_ai_working_group_2026-5|ソース名 #5]] ^src-mext_ai_working_group_2026-5

---

> [!tip] OECDが示す生成AIの望ましい活用と政策課題
> 政策立案者の課題は、生成AIが学習の近道（ショートカット）ではなく、**学習のパートナー**となることを保証すること。[[#^src-mext_ai_working_group_2026-4|ソース名 #4]] ^src-mext_ai_working_group_2026-4

---

> [!quote]- 原文抜粋一覧（認知負債・オフロード関連研究）
>
> **[6] 脳科学的分析研究 — Kosyama et al. (2025)**
> LLMを用いたエッセイ執筆が学習・脳活動・当事者意識に与える影響を、脳科学的に分析した研究。LLMは利便性を提供する一方で、認知的負荷の低下、記憶・理解の弱化、主体性の低下といった教育上の潜在的リスクを伴う可能性を示唆。認知負債等のLLM依存の長期的影響についても検証が必要と指摘。
> Kosyama et al. (2025) *Your Brain on ChatGPT: Accumulation of Cognitive Debt when Using an AI Assistant for Essay Writing Task*
> → 論点: LLMによる認知負債・認知的負荷低下のリスクに関する研究 ^src-mext_ai_working_group_2026-6
>
> ---
>
> **[7] 認知的オフローディングと批判的思考の関係 — Gerlich (2025)**
> AIツールの使用と批判的思考スキルの関係を調査し、認知的オフローディング（認知負荷の外部化）が媒介要因として機能するかに焦点を当てた研究。AIツールの頻繁な使用と批判的思考能力との間に有意な負の相関があり、若年層はAIツールへの依存度が高く、批判的思考スコアが低い傾向。
> Gerlich, M. (2025). AI Tools in Society: Impacts on Cognitive Offloading and the Future of Critical Thinking. *Societies*, 15(1), 6.
> → 論点: 認知的オフローディングと批判的思考スキルの負の相関に関する研究 ^src-mext_ai_working_group_2026-7
>
> ---
>
> **[8] メタ認知の正確性低下 — Fernandes et al. (2026)**
> 生成AIの利用が論理的課題における成績と自己評価（メタ認知的判断）にどのような影響を与えるかを、大規模実験で検証した研究。AIは成績を向上させる一方、自己評価の過大化を招き、メタ認知の正確性を低下させることが示された。
> Daniela Fernandes et al. (2026) AI makes you smarter but none the wiser: The disconnect between performance and metacognition, *Computers in Human Behavior*
> → 論点: 生成AI利用によるメタ認知の正確性低下に関する2026年研究 ^src-mext_ai_working_group_2026-8

---

> [!warning] アメリカ心理学会によるAI依存とバイアス強化のリスク認識
> アメリカ心理学会の専門家パネルは、AIにより依存や既存のバイアスをさらに強化する可能性を指摘。[[#^src-mext_ai_working_group_2026-9|ソース名 #9]] ^src-mext_ai_working_group_2026-9
>
> - 汎用的な消費者向けのモデルはユーザーに好意的に返答するよう訓練をされており、それにより**確証バイアスや不適応な信念を強化**することやユーザーの既存の信念を増幅・強固にする**エコーチェンバーを生成するリスク**を指摘。
> - 偏ったデータで訓練されたモデルは、社会的に弱い立場にある集団に対して、**差別的または有害な助言を生成するリスク**を指摘。

---

> [!warning] 日本教育における生成AI活用のリスク認識
> **学習過程の省略リスク**[[#^src-mext_ai_working_group_2026-10|ソース名 #10]] ^src-mext_ai_working_group_2026-10
> 学習活動の目的や育成したい資質・能力を十分に意識しないままに、安易に生成 AI を児童生徒の学習活動に導入することで、AI に依存したり、AI の答えを鵜呑みにしたりするなど、目的に即した必要な学習過程が省略されてしまい、資質・能力の育成に繋がらないリスクがある。
>
> **言語的外化なき活用のリスク**[[#^src-mext_ai_working_group_2026-11|ソース名 #11]] ^src-mext_ai_working_group_2026-11
> 情報技術の活用が「外化」をはじめとする言語能力の発揮を促す活動を欠いて行われた場合、身体性に根ざした人間ならではの価値の創造や意味理解を欠いた、空疎な情報の集積・共有となる恐れもある（例：言語による外化なしに生成AIが生成したものをそのまま使うなど）

---

> [!important] 日本教育が示すAI活用の基本方針：正負両面の理解と批判的吟味
> AIの「②適切な取扱い」や「③特性の理解」においては、発達段階に応じて、正負の両面を扱う必要があり、その上で、出力を批判的に吟味しながら、利点を生かして「①活用」できるようになることが求められると考えられる。[[#^src-mext_ai_working_group_2026-12|ソース名 #12]] ^src-mext_ai_working_group_2026-12

---

> [!info] 深い学びを阻害するAI活用へのガイドライン対応方針
> AIの活用が深い学びに繋がらないと考えられる例や各教科等における効果的なAIの活用例を含む、具体的な利活用のポイントは、各教科等WGでの検討や諸外国の議論、学校現場における実践の蓄積等を踏まえつつ、**指導要領改訂を待たずしてガイドライン等で対応する**とともに、深い学びの実装に向けた評価の在り方については教育課程全体の議論の中で検討する必要。[[#^src-mext_ai_working_group_2026-13|ソース名 #13]] ^src-mext_ai_working_group_2026-13

---

> [!info] 高校卒業生全員へのAIリテラシー保障目標
> 初等中等教育において情報活用能力の抜本的な向上を図ることにより、文理の枠を超え、**高校卒業生全員**に対し、数理・データサイエンス・AIを「日常の生活や仕事等の場で使いこなす」ことができる「リテラシーレベル」（※）の学習を保障する枠組みを構築。[[#^src-mext_ai_working_group_2026-14|ソース名 #14]] ^src-mext_ai_working_group_2026-14

---

> [!tip] 小中高の発達段階別AI学習方針
> **小学校段階**[[#^src-mext_ai_working_group_2026-15|ソース名 #15]] ^src-mext_ai_working_group_2026-15
> まず、「②適切な取扱い」「③特性の理解」を学んだ上で、「①活用」を通した体験的な学びを深める方向性が示されている【第２回情報・技術WG】
>
> **中学校段階**[[#^src-mext_ai_working_group_2026-15|ソース名 #15]]
> 各要素の内容を深めつつ、抽象的・科学的な理解を必要とする「③特性の理解」を身に付けることを一層重視する方向性が示されている【論点整理】
>
> **高等学校段階**[[#^src-mext_ai_working_group_2026-15|ソース名 #15]]
> 高等教育段階での数理・データサイエンス・AI教育の動向とも連動し、文理を問わず生成AI時代に不可欠な基礎的な素養である「③特性の理解」を身に付ける方向性が示されている【論点整理】

---

### OECD Digital Education Outlook 2026: Navigating the Generative AI Frontier

以下は一次資料のテキストから抜粋された記述です。

> [!quote]- 原文抜粋一覧
>
> **[1]** "However, evidence shows that overreliance on generative AI tools that provide direct answers can reduce students' active engagement, improving task performance without corresponding learning gains. When used as a shortcut rather than a learning tool, generative AI can displace cognitive effort and weaken the skills that underpin deep learning."
> → 論点: GenAIへの過度の依存が学習と認知的努力を阻害する国際的認識 ^src-oecd_digital_education_outlook_2026-1
>
> ---
>
> **[2]** "For example, a field experiment in Türkiye found that while access to GPT-4 improved short-term performance – by 48% with the standard interface, and by 127% with a tutoring version designed to support learning – students performed 17% worse once access was removed, showing that generative AI can undermine learning unless explicitly designed to support skill acquisition."
> → 論点: GenAIが短期的な成績向上と長期的な学習阻害をもたらす可能性を示唆する研究結果 ^src-oecd_digital_education_outlook_2026-2
>
> ---
>
> **[3]** "When students depend too heavily on GenAI, metacognitive engagement – the mental processes and effort that turns answers into understanding – drops. This results in a misalignment between task performance and genuine learning (chapters 1 and 2)."
> → 論点: GenAIへの過度な依存がメタ認知の関与と真の学習を阻害するという国際的認識 ^src-oecd_digital_education_outlook_2026-3
>
> ---
>
> **[4]** "Another study compared differences between students who revised essays by asking for human advice or used a general-purpose LLM (Chen et al., 2025[28]). They found that those who interacted with human experts sought help in a linear way, following the models of "help seeking" theory: diagnosing what they need help with, asking for help, evaluating the help received, iterating, and then implementing the final help. They showed that when interacting with a general-purpose chatbot, some students tended to ask directly for help and implement immediately the solution received. They would often skip the diagnosis, evaluation and iteration stages. The authors refer to this as "metacognitive laziness", a way of describing "cognitive offloading"."
> → 論点: 一般用途LLMがメタ認知の怠惰や認知的オフローディングを引き起こす研究 ^src-oecd_digital_education_outlook_2026-4
>
> ---
>
> **[5]** "Another study is worth mentioning as it casts neuroscientific light on the above findings (Kosmyna et al., 2025[29]). In the United States, students from 5 universities were asked to write a 20-minute essay under three working conditions: writing by themselves ("brain-only"), with a search engine, or with a general-purpose GenAI tool (ChatGPT). Afterwards, within one hour of the actual essay writing, only 12% of the LLM group could quote something from their essay (exact recall) as opposed to 89% in the two other groups. Even though the essays of the LLM group were well rated, the LLM group also had a lower ability to summarise their essay's viewpoint, lower level of ownership, and more similar content across essays. Brain imagery suggested a shift in their executive tasks from generating content to supervising the AI-generative content, with lower neural connectivity and involvement. They also showed that writing alone first and then using the LLM preserved higher levels of activation and recall. In contrast, those who started with an LLM and then continued alone had low levels of activation and recall. These findings suggest that initial cognitive activation is crucial before using GenAI."
> → 論点: GenAI利用が脳の活動を低下させ、初期の認知的活性化が重要であることを示す神経科学的研究 ^src-oecd_digital_education_outlook_2026-5
>
> ---
>
> **[6]** "This evidence highlights that a proportion of students using general-purpose LLMs may take shortcuts, avoiding the productive struggle and cognitive effort needed for learning and durable knowledge and skill acquisition. This aligns with a "fast" rather than more productive "slow" and iterative use of GenAI, as argued by Beghetto (2026[30]), and the notion of "lazy" use of GenAI (Vinchon et al., 2023 [31])."
> → 論点: 一般用途LLMの利用が認知的努力を回避する「怠惰な利用」につながるという認識 ^src-oecd_digital_education_outlook_2026-6
>
> ---
>
> **[7]** "In conclusion, using general purpose GenAI tools carries risks, particularly if students use them to avoid the cognitive effort that educational tasks are designed to elicit. However, learning science also recognises that learners may need "scaffolding", support that is gradually removed as students become more proficient. When used pedagogically, GenAI tools can serve as scaffolding (Strauß and Rummel, 2026[33])."
> → 論点: 一般用途GenAIツールが認知的努力回避のリスクを伴うが、足場かけとしての教育的活用は可能 ^src-oecd_digital_education_outlook_2026-7
>
> ---
>
> **[8]** "Ultimately, when designed with strong pedagogy and a human-centred approach, GenAI can do far more than help students complete tasks. It has the potential to deepen student learning, improve teaching practice and streamline institutional management and research. But these benefits come with risks. Overreliance risks turning students into passive consumers and teachers into supervisors. To unlock GenAI's full potential, education must move beyond generic chatbots towards purpose-built tools for education. The thoughtful integration of general-purpose GenAI tools will be essential – for realising the full learning benefits of GenAI and developing students' GenAI literacy for their future careers. The challenge for policymakers is to ensure that GenAI is a learning partner and not a learning shortcut."
> → 論点: GenAIの潜在的リスクと、学習ショートカットではなく学習パートナーとしての利用の重要性 ^src-oecd_digital_education_outlook_2026-8
>
> ---
>
> **[9]** "The mirage of "false mastery" in AI-augmented learning"
> → 論点: AI強化学習における「偽りの熟達」の幻想 ^src-oecd_digital_education_outlook_2026-9
>
> ---
>
> **[10]** "The risk in many educational contexts is that generative AI either simply augments current abilities or, more problematically in an education content, substitutes for human effort without fostering genuine skill development."
> → 論点: GenAIが真のスキル開発なしに人間の努力を代替するリスク ^src-oecd_digital_education_outlook_2026-10
>
> ---
>
> **[11]** "Another dimension of concern relates to the effects of the use of GenAI on learning processes. There is accumulating evidence that increased reliance on GenAI tools can suppress students' engagement in self-monitoring (defined as the ongoing process of checking, regulating, and adjusting one's understanding and strategies during learning), reflection, and evaluative judgement of one's learning processes, processes that are fundamental to autonomous learning (Molenaar, 2022[112]). When GenAI is used as a shortcut rather than as a scaffold that promotes learning, students may defer cognitive effort to technology, thereby weakening the very skills that underlie deep learning."
> → 論点: GenAIへの依存が学習プロセスの自己監視、反省、評価判断を抑制し、深い学習の基盤となるスキルを弱める ^src-oecd_digital_education_outlook_2026-11
>
> ---
>
> **[12]** "On average, across OECD countries, 36% of lower secondary teachers' report having used AI in their work in the 12 months prior to the 2024 survey, with very large cross-country variations. Around 75% of teachers in Singapore and the United Arab Emirates report using AI compared to fewer than 20% of teachers in France and Japan."
> → 論点: 2024年時点での日本の教員のAI利用率の低さ（OECD平均と比較） ^src-oecd_digital_education_outlook_2026-12
>
> ---
>
> **[13]** "As for the teachers who have not used it, they report feeling overwhelmed by the growing expectation to integrate digital tools in education, which they see as a barrier to using AI in their teaching. This varies markedly across systems, from fewer than 20% in Brazil, Chile, Costa Rica, Italy, Morocco, Türkiye and the United Arab Emirates, to over 50% in Croatia, the Flemish Community of Belgium, Japan and Serbia."
> → 論点: 日本の教員のAI不使用の理由としてデジタルツール統合への期待に圧倒される感情の国際比較 ^src-oecd_digital_education_outlook_2026-13
>
> ---
>
> **[14]** "Japan: the government provides guidance on generative AI in schools that explicitly warns against inputting personal or sensitive data into generative AI systems, reflecting early recognition of LLM-specific data reuse and retraining risks in education."
> → 論点: 日本政府のGenAIに関する学校向けガイドラインが個人・機密データ入力への警告に焦点を当てる ^src-oecd_digital_education_outlook_2026-14
>
> ---
>
> **[15]** "One is an interactive writing task, where a chatbot provides mid-task feedback to the test-takers as they are writing a short essay in English, suggesting additional directions and revisions. Another one is an automated assessment of their oral speaking during a dialogue in "natural language" with a GenAI-powered agent."
> → 論点: GenAIを活用したインタラクティブなライティング・スピーキング評価の革新例 ^src-oecd_digital_education_outlook_2026-15

---

> [!warning] GenAIへの過度依存が学習・認知的努力を阻害する [[#^src-oecd_digital_education_outlook_2026-1|ソース名 #1]][[#^src-oecd_digital_education_outlook_2026-3|ソース名 #3]]
> GenAIに直接的な回答を求め過ぎると、学生の**能動的な関与**が低下し、タスクのパフォーマンスは向上しても対応する学習効果が得られない。学習ツールではなくショートカットとして使われた場合、GenAIは認知的努力を奪い、深い学習を支えるスキルを弱める。
>
> また、GenAIへの過度な依存により、**メタ認知の関与**（回答を理解へと変換する精神的プロセスと努力）が低下し、タスクのパフォーマンスと真の学習の間にミスアラインメントが生じる。

---

> [!note] トルコの実験：短期的成績向上と長期的学習阻害 [[#^src-oecd_digital_education_outlook_2026-2|ソース名 #2]]
> トルコでのフィールド実験では、GPT-4へのアクセスが短期的な成績を向上させた（標準インターフェースで**48%**、学習支援向けのチューター版で**127%**）一方、アクセスが取り除かれると学生の成績は**17%低下**した。これは、スキル習得を支援するよう明示的に設計されない限り、GenAIが学習を損なう可能性を示している。

---

> [!warning] 「メタ認知の怠惰」と認知的オフローディング (Chen et al., 2025[28]) [[#^src-oecd_digital_education_outlook_2026-4|ソース名 #4]]
> 人間の専門家に助けを求めた学生は「ヘルプシーキング」理論のモデルに沿って線形的に行動した（何が必要かを診断 → 助けを求める → 受け取った助けを評価 → 反復 → 最終的な助けを実装）。
>
> 一方、**汎用チャットボット**を利用した学生の一部は、直接助けを求めてすぐに解決策を実装する傾向があり、**診断・評価・反復の段階を省略**することが多かった。著者らはこれを「**メタ認知の怠惰**」と呼び、「認知的オフローディング」の一形態として説明している。

---

> [!note] 神経科学的知見：GenAI利用が脳活動を低下させる (Kosmyna et al., 2025[29]) [[#^src-oecd_digital_education_outlook_2026-5|ソース名 #5]]
> 米国の5大学の学生を対象に、20分間のエッセイ執筆を3条件（自力・検索エンジン使用・ChatGPT使用）で実施。エッセイ執筆から1時間以内の時点で、**LLMグループの12%のみ**が自分のエッセイから正確に引用できたのに対し、他の2グループでは**89%**が引用できた。
>
> LLMグループのエッセイは高評価であったにもかかわらず、以下の特徴が見られた：
> - エッセイの視点を要約する能力が低い
> - 自分のエッセイへの当事者意識が低い
> - エッセイの内容が互いに似通っている
>
> 脳画像データは、コンテンツ生成からAI生成コンテンツの監督へと遂行機能が移行し、**神経接続性と関与が低下**したことを示した。また、最初に単独で執筆してからLLMを使用した場合は活性化と記憶の水準が高く保たれたのに対し、最初にLLMを使用してから単独で続けた場合は活性化と記憶の水準が低かった。これらの知見は、**GenAI使用前の初期認知的活性化が重要**であることを示唆している。

---

> [!warning] 一般用途LLMの「怠惰な利用」と認知的努力の回避 (Beghetto, 2026[30]; Vinchon et al., 2023[31]) [[#^src-oecd_digital_education_outlook_2026-6|ソース名 #6]]
> 一般用途LLMを使用する学生の一部は、学習と持続的な知識・スキル習得に必要な生産的な苦闘と認知的努力を回避するショートカットを取る可能性がある。これはBeghetto (2026[30])が主張する、より生産的な「スロー」で反復的なGenAI利用ではなく「ファスト」な利用、およびVinchon et al. (2023[31])の「怠惰な」GenAI利用という概念と一致している。

---

> [!tip] リスクと可能性の両面：足場かけとしての教育的活用 (Strauß and Rummel, 2026[33]) [[#^src-oecd_digital_education_outlook_2026-7|ソース名 #7]]
> 一般用途GenAIツールの使用は、教育的タスクが引き出すよう設計された認知的努力を学生が回避するために利用する場合、特にリスクを伴う。
>
> 一方で、学習科学は学習者が「**足場かけ（スキャフォールディング）**」を必要とする場合があることも認識している。これは学生が習熟するにつれて徐々に取り除かれる支援であり、教育的に使用された場合、GenAIツールは足場かけとして機能し得る。

---

> [!important] GenAIを「学習ショートカット」ではなく「学習パートナー」に [[#^src-oecd_digital_education_outlook_2026-8|ソース名 #8]]
> 強固な教育学と人間中心のアプローチで設計された場合、GenAIは学生のタスク完了を助ける以上のことができる。学生の学習の深化、教授実践の改善、機関管理・研究の効率化の可能性を持つ。しかしこれらの利点にはリスクが伴う。
>
> - **過度の依存**は学生を受動的な消費者に、教員を監督者に変えるリスクがある
> - GenAIの可能性を最大限に引き出すには、汎用チャットボットを超えた**教育専用ツール**への移行が必要
> - 汎用GenAIツールの**思慮深い統合**が、学習効果の実現と学生のGenAIリテラシー育成に不可欠
>
> **政策立案者にとっての課題は、GenAIが学習ショートカットではなく学習パートナーとなることを確保することである。**

---

> [!warning] AI強化学習における「偽りの熟達」の幻想 [[#^src-oecd_digital_education_outlook_2026-9|ソース名 #9]][[#^src-oecd_digital_education_outlook_2026-10|ソース名 #10]]
> AI強化学習には「**false mastery（偽りの熟達）**」という幻想のリスクが存在する。多くの教育的文脈におけるリスクは、GenAIが現在の能力を単に補強するにとどまるか、さらに問題なのは、**真のスキル開発を促すことなく人間の努力を代替してしまう**ことである。

---

> [!warning] GenAIへの依存が自己監視・反省・評価判断を抑制する (Molenaar, 2022[112]) [[#^src-oecd_digital_education_outlook_2026-11|ソース名 #11]]
> GenAIツールへの依存度の高まりが、学生の**自己監視**（学習中の理解と方略を確認・調整する継続的プロセス）、**反省**、および**学習プロセスの評価的判断**への関与を抑制するという証拠が蓄積されている。これらは自律的学習に不可欠なプロセスである（Molenaar, 2022[112]）。
>
> GenAIが学習を促進する足場かけとしてではなくショートカットとして使用される場合、学生は認知的努力をテクノロジーに委ねてしまい、深い学習の基盤となるスキルそのものを弱めることになる。

---

> [!important] 日本の教員のAI利用率の低さ：OECD平均との乖離 [[#^src-oecd_digital_education_outlook_2026-12|ソース名 #12]][[#^src-oecd_digital_education_outlook_2026-13|ソース名 #13]]
> 2024年調査の直近12ヶ月において、OECD各国の前期中等教育教員の平均**36%**がAIを業務に使用したと報告しているが、国間で非常に大きなばらつきがある。
>
> | 国・地域 | AI利用率 |
> |---|---|
> | シンガポール、アラブ首長国連邦 | 約75% |
> | OECD平均 | 36% |
> | フランス、**日本** | 20%未満 |
>
> また、AIを使用していない教員については、デジタルツールの統合への高まる期待に**圧倒される感情**を感じると報告しており、これをAI活用の障壁と見なしている。この割合も国によって大きく異なる：
> - **20%未満**：ブラジル、チリ、コスタリカ、イタリア、モロッコ、トルコ、アラブ首長国連邦
> - **50%超**：クロアチア、ベルギーのフランドル共同体、**日本**、セルビア

---

> [!tip] 日本政府のガイドライン：データリスクへの早期認識 [[#^src-oecd_digital_education_outlook_2026-14|ソース名 #14]]
> 日本政府は、学校向けの生成AIに関するガイダンスを提供しており、生成AIシステムへの個人情報・機密データの入力に対して**明示的に警告**している。これは、教育におけるLLM特有のデータ再利用・再学習リスクへの早期認識を反映している。

---

> [!note] GenAIを活用したインタラクティブな評価の革新例 [[#^src-oecd_digital_education_outlook_2026-15|ソース名 #15]]
> GenAIを活用した新しい評価手法として、以下の2つが挙げられる：
>
> 1. **インタラクティブなライティングタスク**：チャットボットが英語の短いエッセイ執筆中に追加の方向性と修正を提案するタスク中フィードバックを提供する
> 2. **口頭スピーキングの自動評価**：GenAI搭載エージェントとの「自然言語」による対話中の口頭スピーキングを自動評価する

---

> [!quote]- 原文抜粋一覧
> **[1]** "Generative artificial intelligence (GenAI) is increasingly integrated into higher education, where it supports writing, feedback, problem solving, and research-related tasks while also raising concerns about cognitive offloading and learner dependence."
> → 論点: GenAIの高等教育への統合と認知的オフローディングへの懸念（2026年時点の国際的認識） ^src-cognitive_offloading_scoping_review_2026-1
>
> **[2]** "Across the literature, GenAI operates through a dual-pathway structure: one pathway may enhance learner agency by strengthening self-regulated learning, self-efficacy, feedback literacy, and reflective engagement, whereas the other may erode learner agency through cognitive offloading, overreliance, dependence, uncritical uptake, and weakened judgement."
> → 論点: GenAIが学習者エージェンシーに与える二重の影響経路（国際的認識） ^src-cognitive_offloading_scoping_review_2026-2
>
> **[3]** "Overall, the findings suggest that the educational value of GenAI depends less on the technology itself than on how it is pedagogically embedded, with augmentation-oriented and scaffolded use being more supportive of learner agency than replacement-oriented use."
> → 論点: GenAIの教育的価値は技術ではなく教育的組み込みに依存する（国際的認識） ^src-cognitive_offloading_scoping_review_2026-3
>
> **[4]** "On the other hand, scholars have also raised serious concerns about technological dependence, uncritical acceptance of AI-generated output, diminished originality, and the erosion of independent judgement."
> → 論点: GenAI利用における技術依存や独立した判断の低下への懸念（国際的認識） ^src-cognitive_offloading_scoping_review_2026-4
>
> **[5]** "Some studies now describe this pattern as paradoxical: GenAI may simultaneously increase learners' confidence and efficiency while also intensifying their dependence on technology (Zhang and Xu, 2025; Zheng and Wang, 2026)."
> → 論点: GenAIが自信と効率性を高める一方で技術依存を強めるパラドックス（国際的認識） ^src-cognitive_offloading_scoping_review_2026-5
>
> **[6]** "From this perspective, the impact of GenAI on learner agency appears to be mediated by a set of central cognitive and motivational mechanisms. Among these, self-regulation and metacognition have emerged as especially important."
> → 論点: GenAIが学習者エージェンシーに与える影響の中心的メカニズムとしての自己調整とメタ認知（国際的認識） ^src-cognitive_offloading_scoping_review_2026-6
>
> **[7]** "when such regulatory capacities are weak, learners are more likely to slide into superficial engagement, passive uptake, and cognitive offloading (Xu et al., 2025; Zheng and Wang, 2026; Zhou and Wang, 2026)."
> → 論点: 自己調整能力が低い場合の認知的オフローディングの増加リスク（国際的認識） ^src-cognitive_offloading_scoping_review_2026-7
>
> **[8]** "Broadly speaking, cognitive offloading refers to the delegation of cognitive work to external tools or systems. In the context of GenAI, this may include outsourcing idea generation, drafting, summarizing, revising, decision-making, or evaluative judgement to the AI system."
> → 論点: GenAIにおける認知的オフローディングの定義と具体例（国際的認識） ^src-cognitive_offloading_scoping_review_2026-8
>
> **[9]** "Importantly, the literature suggests that offloading is not inherently maladaptive. Some forms of strategic offloading may reduce unnecessary load, free up cognitive resources, and support higher-order thinking."
> → 論点: オフローディングが必ずしも非適応的ではないという見解（国際的認識） ^src-cognitive_offloading_scoping_review_2026-9
>
> **[10]** "However, the same process may also become problematic when learners rely on GenAI without verification, without reflection, or without maintaining ownership of the task (Chase and Galvin, 2026; Wang and Zhang, 2026)."
> → 論点: オフローディングが問題となる条件（国際的認識） ^src-cognitive_offloading_scoping_review_2026-10
>
> **[11]** "For this reason, cognitive offloading, overreliance, and dependence are treated in this review not as peripheral risks but as central negative pathways through which learner agency may be weakened."
> → 論点: 認知的オフローディングが学習者エージェンシーを弱める中心的経路（国際的認識） ^src-cognitive_offloading_scoping_review_2026-11
>
> **[12]** "Across the literature reviewed in this study, self-regulation emerges as the central mechanism linking GenAI use to agency-related outcomes."
> → 論点: 自己調整がGenAI利用とエージェンシー成果を結びつける中心的メカニズム（国際的認識） ^src-cognitive_offloading_scoping_review_2026-12
>
> **[13]** "The literature search was conducted in the Web of Science Core Collection on March 31, 2026. Web of Science was selected because it indexes a large body of peer-reviewed international literature and allows structured topic-based and field-specific searches suitable for interdisciplinary review work."
> → 論点: 2026年3月時点の国際的な査読済み文献に基づいたレビューであること ^src-cognitive_offloading_scoping_review_2026-13
>
> **[14]** "There is also strong concentration in certain regional contexts, especially Chinese and EFL-related higher education settings. Although this concentration has generated valuable insights, broader disciplinary and contextual diversity would improve the generalizability of future findings and reveal whether the same dual-pathway structure holds across different educational traditions and epistemic practices (Zhang, Rice, & Wang, 2024; Zheng & Wang, 2026)."
> → 論点: GenAI研究の地域的偏りと異なる教育文化における普遍性の必要性（日本教育への直接的言及の欠如を間接的に示す） ^src-cognitive_offloading_scoping_review_2026-14
>
> **[15]** "Fourth, a large proportion of the studies reviewed were concentrated in language-learning, writing, and Chinese/EFL higher education settings. This concentration reflects the current state of the field, but it may limit the transferability of some conclusions to other disciplines or regions."
> → 論点: 特定の地域・分野に集中する研究の限界（日本教育への直接的言及の欠如を間接的に示す） ^src-cognitive_offloading_scoping_review_2026-15

---

> [!info] GenAIの高等教育への統合と二重の影響経路
> GenAIは高等教育においてライティング・フィードバック・問題解決・研究関連タスクを支援する形で統合が進んでいる一方、**認知的オフローディング**と**学習者依存**への懸念も同時に高まっている。[[#^src-cognitive_offloading_scoping_review_2026-1|ソース #1]]
>
> 文献横断的に見ると、GenAIは**二重経路構造（dual-pathway structure）**を通じて作用する。
> - **促進経路**：自己調整学習・自己効力感・フィードバックリテラシー・内省的関与を強化し、学習者エージェンシーを高める
> - **侵食経路**：認知的オフローディング・過度な依存・無批判な受容・判断力の低下を通じて、学習者エージェンシーを弱める
>
> [[#^src-cognitive_offloading_scoping_review_2026-2|ソース #2]]

---

> [!important] GenAIの教育的価値は「技術」ではなく「教育的組み込み方」に依存する
> 知見が示すのは、GenAIの教育的価値は**技術そのものよりも、どのように教育的に組み込まれるか**に依存するという点である。**拡張志向・足場かけ型**の活用は、**代替志向**の活用よりも学習者エージェンシーを支持する。[[#^src-cognitive_offloading_scoping_review_2026-3|ソース #3]]

---

> [!warning] 技術依存・独立した判断の低下・パラドックスへの懸念
> 研究者たちは、技術依存・AI生成アウトプットの無批判な受容・独自性の低下・独立した判断の侵食について深刻な懸念を示している。[[#^src-cognitive_offloading_scoping_review_2026-4|ソース #4]]
>
> さらに一部の研究は、このパターンを**パラドキシカル**と表現している。GenAIは学習者の自信と効率性を高めると同時に、技術依存をも強化しうる（Zhang and Xu, 2025; Zheng and Wang, 2026）。[[#^src-cognitive_offloading_scoping_review_2026-5|ソース #5]]

---

> [!info] 中心的メカニズム：自己調整とメタ認知
> GenAIが学習者エージェンシーに与える影響は、認知的・動機づけ的メカニズムの集合によって媒介されており、なかでも**自己調整（self-regulation）**と**メタ認知**が特に重要なものとして浮上している。[[#^src-cognitive_offloading_scoping_review_2026-6|ソース #6]]
>
> 自己調整能力が低い学習者ほど、**表面的な関与・受動的な受容・認知的オフローディング**へと陥りやすい（Xu et al., 2025; Zheng and Wang, 2026; Zhou and Wang, 2026）。[[#^src-cognitive_offloading_scoping_review_2026-7|ソース #7]]
>
> 文献横断的に、**自己調整**はGenAI利用とエージェンシー関連成果を結びつける中心的メカニズムとして一貫して浮上している。[[#^src-cognitive_offloading_scoping_review_2026-12|ソース #12]]

---

> [!info] 認知的オフローディングの定義と位置づけ
> 認知的オフローディングとは、**認知的作業を外部ツールやシステムに委託すること**を指す。GenAIの文脈では、アイデア生成・草稿作成・要約・修正・意思決定・評価的判断をAIシステムに外注することが含まれる。[[#^src-cognitive_offloading_scoping_review_2026-8|ソース #8]]
>
> 重要な点として、オフローディングは本質的に非適応的ではない。**戦略的なオフローディング**は不要な負荷を軽減し、認知資源を解放し、高次思考を支援しうる。[[#^src-cognitive_offloading_scoping_review_2026-9|ソース #9]]

---

> [!warning] オフローディングが問題となる条件と、学習者エージェンシーへの中心的リスク
> 一方で、学習者が**検証なし・内省なし・タスクの主体性を保たない**まま GenAI に依存する場合、同じプロセスが問題となりうる（Chase and Galvin, 2026; Wang and Zhang, 2026）。[[#^src-cognitive_offloading_scoping_review_2026-10|ソース #10]]
>
> このため本レビューでは、認知的オフローディング・過度な依存・依存症は**周辺的リスクではなく、学習者エージェンシーを弱める中心的な負の経路**として位置づけられている。[[#^src-cognitive_offloading_scoping_review_2026-11|ソース #11]]

---

> [!note] レビューの範囲と文献検索の条件
> 文献検索は2026年3月31日に**Web of Science Core Collection**にて実施された。Web of Scienceが選択された理由は、大量の国際的査読済み文献をインデックスしており、学際的レビュー作業に適した構造化されたトピックベース・分野別検索が可能であるためである。[[#^src-cognitive_offloading_scoping_review_2026-13|ソース #13]]

---

> [!warning] 研究の地域的偏りと普遍性への限界
> 既存研究には特定の地域的文脈、特に**中国およびEFL関連の高等教育環境**への強い集中が見られる。この集中は有益な知見を生み出してきたが、より広い学際的・文脈的多様性があれば、将来的な知見の一般化可能性が向上し、同一の二重経路構造が**異なる教育的伝統や認識論的実践**においても成立するかが明らかになるだろう（Zhang, Rice, & Wang, 2024; Zheng & Wang, 2026）。[[#^src-cognitive_offloading_scoping_review_2026-14|ソース #14]]
>
> レビューされた研究の大部分は、**語学学習・ライティング・中国/EFL高等教育環境**に集中している。この集中は当該分野の現状を反映しているが、一部の結論の**他分野・他地域への転用可能性を制限する**おそれがある。[[#^src-cognitive_offloading_scoping_review_2026-15|ソース #15]]

---

# 補足調査(Perplexity, 取得日: 2026-07-13)

一次資料に無い情報を補うため、情報ギャップ判定に基づき実施。

**クエリ:** 日本 初等中等教育 生成AI 認知的オフローディング 対応方針 2025 2026 カリキュラム改訂

---

> [!info] 日本の初等中等教育における生成AI対応の基盤方針
> 日本の初等中等教育における生成AIの「認知的オフローディング」（思考プロセスをAIに預けすぎる現象）への対応方針は、2024年12月に公表された**文部科学省「ガイドライン（Ver.2.0）」**が基盤となっており、**「AIを排除しない」一方で「認知オフロードを自覚的にマネジメントする」教育**を推進しています。
>
> 2025年〜2026年のカリキュラム改訂（次期学習指導要領）では、発達段階に応じて**「AI自体を学ぶこと」**と**「AIを活用して学ぶこと」**を体系的に扱う方向性が示されています。

---

### 1. 認知的オフローディングへの具体的対応方針

> [!info] 文科省の基本方針：人間中心の利活用
> 文科省は、AIが本来子どもが考えるべき部分を代わりに担うリスク（認知的オフローディング）を認めつつ、直ちに利活用を否定するものではなく、**「人間中心の利活用」**を原則としています [^pg1-1][^pg1-2]。

---

> [!tip] プロセス評価の重視
> 成果物ではなく**「思考の過程」**を評価するよう課題の出し方や評価方法を変更する（OECD報告書の指摘を反映） [^pg1-1]。

---

> [!tip] 校内プロトコルの策定
> 各校で「AIに任せることと任せないこと」「AIなしで取り組む時間の最低ライン」「生成物のそのまま提出禁止」などを教員と生徒が話し合って文書化することが推奨されています [^pg1-5]。

---

> [!important] AIの役割制御
> 授業設計において「本来子どもが考えるべき部分までAIが代わりに担っていないか」を常にチェックする観点を設ける [^pg1-1]。

---

### 2. 2025年〜2026年のガイドライン改訂と取組

> [!info] ガイドライン改訂の進捗（2025年7月時点）
> 2025年7月の時点では、Ver.2.0の改訂（Ver.2.1）に向けた具体的な取組が進行しています [^pg1-1]。
>
> **4つの主要取組**:
> 1. **ガイドラインの改訂（Ver.2.1）**: 実証研究やリスク評価データを踏めた更新。
> 2. **教育分野に特化したAIの実証研究**: 現場での適活用を検証。
> 3. **リスク評価のためのデータ整備**: 安全性評価の基準構築。
> 4. **安全に使えるインフラ整備**: 教育現場向けの安全な環境提供。

---

> [!warning] ハルシネーション（誤情報）への対応
> 教師がAIの誤情報やバイアスを十分に理解し、児童生徒がそれらを留意して活用できているかを確認する必要があると明記 [^pg1-3]。

---

### 3. 次期学習指導要領（カリキュラム改訂）における方向性

> [!info] 次期学習指導要領における AI 学習の体系的導入
> 2025年〜2026年にかけて検討が進む次期学習指導要領では、AI学習を**「発達段階に応じた体系」**で導入することを目指しています [^pg1-1]。

---

| 段階 | 重点的な学習内容 |
|------|----------------|
| **小学校** | 基本的な**情報リテラシー**と**批判的思考の基礎**。AIには間違いがある体験を通じた早期の理解 [^pg1-10]。 |
| **中学校** | 複数のAIツールからの回答を**比較分析**し、限界と偏見を理解する能力。人間とAIの役割分担を考える訓練 [^pg1-4]。 |
| **高等学校** | 専門的な**判断能力**の育成。AIを活用した複雑な情報の分析と専門的判断 [^pg1-4]。 |

---

> [!important] 方針の核心：操作技術ではなく批判的思考力の育成
> この方針は、単なるツールの操作技術ではなく、**「AI時代の批判的思考力」**を維持・向上させることを目的としており、必修の「情報I」に加え、発展的な「情報II」の開設も推奨されています [^pg1-10]。

---

### 結論

> [!info] 日本のAI教育方針（2025〜2026年）
> 2025年〜2026年にかけて、日本は**「AIを嫌うのではなく、AIに思考を預けすぎない（認知的オフローディングを抑制する）使い方を教える」**という方針を明確にし、カリキュラムを通じて**批判的思考力**の育成を徹底する予定です。学校現場では、ガイドライン（Ver.2.0）を踏まえ、**「評価は過程を重視する」**ことや**「校内ルール（プロトコル）の策定」**が実務的な対応の中心となります [^pg1-1][^pg1-5]。

---

> [!quote]- 出典脚注(補足調査1) — 番号は本文中の脚注番号に対応
> [^pg1-1]: https://www.elephancube.co.jp/2026/07/school-genai-risk/
> [^pg1-2]: https://code.or.jp/magazine/20250124/
> [^pg1-3]: https://ict-enews.net/zoomin/14mext-3/
> [^pg1-4]: https://qiita.com/hisaho/items/c04ad7f383ae65bdbc4c
> [^pg1-5]: https://note.com/mhamadajp/n/nfd239edc2621
> [^pg1-6]: https://current.ndl.go.jp/car/236829
> [^pg1-7]: https://hokkyodai.repo.nii.ac.jp/record/2000700/files/kisokenkyu_77_03.pdf
> [^pg1-8]: https://ippjapan.org/en_ichi/archives/774
> [^pg1-9]: https://www.mext.go.jp/a_menu/other/mext_02412.html
> [^pg1-10]: https://www.edutechnology.co.jp/service/aikyouiku-support/policy-trends

---

> [!warning] 検索クエリへの注意——該当文書の不在
> **クエリ:** Japan Ministry of Education generative AI cognitive offloading policy guidelines 2025 2026
>
> There are **no Japan Ministry of Education (MEXT) policy guidelines specifically titled or dated for "2025–2026" on generative AI cognitive offloading**. The most relevant and current MEXT guidance is the **"Guidelines for the Utilization of Generative AI in Elementary and Secondary Education (ver2.0)"**, published in **December 2024**, which explicitly addresses the risk of **cognitive offloading** (dependency on AI) and mandates that students use AI outputs only as references while making their own judgments [^pg2-2][^pg2-3].

---

### Key Details on the Cognitive Offloading Policy:

| Aspect | MEXT Position (Dec 2024 Guidelines) |
|--------|-------------------------------------|
| **Core Concern** | Generative AI can cause students to engage in "cognitive offloading," becoming dependent on technology instead of developing critical thinking [^pg2-3][^pg2-8] |
| **Required Practice** | Teachers must instruct students to use AI outputs **only as a reference** and ultimately make **their own judgments** [^pg2-3] |
| **Prevention Strategy** | Encourage diversified assessment methods to prevent overreliance on AI-generated content; cultivate critical thinking and content validation [^pg2-1] |
| **Target Audience** | School education personnel (teachers, staff, educational committees) [^pg2-2] |

### Context on 2025–2026 AI Policy Developments:

> [!warning] 政策文書の性質に関する注意
> In **February 2025**, Japan's Cabinet approved the **"Act on the Promotion of Research, Development, and Utilization of Artificial Intelligence"** (AI Act), but this is a **national legislative bill** focused on AI research and industry, not a specific MEXT education guideline on cognitive offloading [^pg2-4][^pg2-5].

---

> [!warning] 提言と省庁ガイドラインの混同に注意
> The **Science Council of Japan** released a proposal in **February 2025** titled *"Toward the Realisation of a Society that Accepts and Utilises Generative AI"*, which emphasizes active discussion in education but does not constitute a MEXT guideline [^pg2-1].

---

> [!warning] R&D指針と学校教育レベルの指針の粒度差
> The **"Guideline for Ensuring the Appropriateness of Research & Development and Utilization of Artificial Intelligence-Related Technology"** was decided in **December 2025** by the AI Strategy Headquarters, focusing on R&D rather than school-level cognitive offloading [^pg2-2].

---

### Conclusion:

> [!info] December 2024 MEXT Guidelines (ver2.0) — Current Authoritative Policy
> The **December 2024 MEXT Guidelines (ver2.0)** are the **current authoritative policy** addressing cognitive offloading in Japanese education. No new MEXT-specific guideline with a 2025–2026 effective date on this topic has been released as of July 2026. If you are looking for upcoming updates, the 2024 guidelines remain the operative standard, with MEXT likely to issue revisions based on evolving AI risks.

---

> [!quote]- 出典脚注(補足調査2) — 番号は本文中の脚注番号に対応
> [^pg2-1]: https://cn.ichei.org/en/knowledge/collection/1707.html
> [^pg2-2]: https://aisi.go.jp/assets/pdf/j-aisi_factsheet_2025_en.pdf
> [^pg2-3]: https://ippjapan.org/en_ichi/en/archives/774
> [^pg2-4]: https://mofotech.mofo.com/topics/japan-s-approach-to-ai-regulation-in-2025
> [^pg2-5]: https://www.linkedin.com/posts/hiroki-habuka_217anbun2pdf-activity-7301427096399032320-NKEd
> [^pg2-6]: https://www.gov-online.go.jp/hlj/en/november_2025/november_2025-08.html
> [^pg2-7]: https://www.facebook.com/TheJapanNews/posts/educators-fear-that-the-use-of-generative-ai-will-hinder-the-development-of-japa/292226046496556/
> [^pg2-8]: https://www.oecd.org/content/dam/oecd/en/publications/reports/2025/12/ai-adoption-in-the-education-system_43251cf0/69bd0a4a-en.pdf
> [^pg2-9]: https://www.econstor.eu/bitstream/10419/302516/1/ITS-Seoul-2024-paper-112.pdf
> [^pg2-10]: https://ajet.org.au/index.php/AJET/article/download/11725/2290/40593

---

> [!warning] OECD Digital Education Outlook 2026 — No Japan-Specific Chapter
> **クエリ:** OECD Digital Education Outlook 2026 Japan AI literacy teacher usage recommendations
>
> The **OECD Digital Education Outlook 2026** does not contain a specific country chapter dedicated to **Japan**; its recommendations on **AI literacy** and **teacher usage** are **global**, though they are applicable to Japan's education system. The report emphasizes that AI should **augment rather than replace** teachers, with usage guided by **clear pedagogical intent** rather than technical proficiency alone [^pg3-1][^pg3-2].

---

### Key Recommendations for Teacher Usage

> [!info] Key Recommendations for Teacher Usage (Summary Table)

| Area | Recommendation |
|------|----------------|
| **Pedagogical Approach** | Teachers must shift AI use from an **output-oriented** focus to a **process-oriented** approach, prompting students to explain reasoning and reflect on misconceptions [^pg3-2][^pg3-3]. |
| **Teacher Role** | Teachers are **professional decision-makers** who guide students in using AI as a tool to support thinking, not just managers who permit or prohibit it [^pg3-2]. |
| **AI Literacy Focus** | Century-century AI literacy involves recognizing when AI use **undermines learning** (e.g., declines in metacognitive engagement) and adjusting patterns accordingly [^pg3-2]. |
| **Interaction Paradigm** | Move from the **replacement paradigm** (automating tasks like lesson planning) to the **synergy paradigm**, where teacher and AI achieve more together [^pg3-3]. |
| **Tool Design** | Prioritize **educational GenAI tools** designed from the ground up for learning (guiding, prompting, challenging) rather than general-purpose chatbots that shortcut learning [^pg3-6]. |

---

### Key Recommendations for AI Literacy

> [!info] Human-Centred Teaching & Selective Use of GenAI
> The report calls for fostering **human-centred teaching** that prioritizes **foundational skills**, **independent thinking**, and **strong human relationships**, using GenAI selectively to **enrich—rather than replace—cognitive effort** [^pg3-1].

---

> [!tip] Fast vs. Slow Uses of GenAI
> The report distinguishes between **"fast uses"** (immediate output) and **"slower uses"** (iterative exploration and reflection), recommending the latter for creativity and deep learning [^pg3-2].

---

### Action Areas for Governments & Stakeholders

> [!info] 政府・ステークホルダーへの4つの行動領域
> The Outlook calls for action in four areas:
> 1. **Foster human-centred teaching** with GenAI [^pg3-1].
> 2. **Invest in educational GenAI research** co-created with teachers [^pg3-1].
> 3. **Shape an enabling policy environment** for trustworthy GenAI (privacy, safety, bias) [^pg3-1].
> 4. **Support inclusive GenAI infrastructure** ensuring equitable access and **sustained professional learning** [^pg3-1].

---

> [!tip] 日本との対比：OECD枠組みとMEXTの位置づけ
> Japan's Ministry of Education (MEXT) has its own AI initiatives (e.g., the "AI for Teachers" program), but the OECD 2026 outlook provides the **international framework** Japan can align with, emphasizing that **pedagogical judgment** is the core competency for teacher preparation [^pg3-2].

---

> [!quote]- 出典脚注(補足調査3) — 番号は本文中の脚注番号に対応
> [^pg3-1]: https://digital-skills-jobs.europa.eu/en/latest/news/oecd-digital-education-outlook-2026-how-generative-ai-can-support-learning-when-used
> [^pg3-2]: https://ciddl.org/summary-of-oecd-digital-education-outlook-2026/
> [^pg3-3]: https://doi.org/10.59350/1bqm0-1d126
> [^pg3-4]: https://www.linkedin.com/posts/sherriwiden_what-the-oecd-says-about-ai-in-education-activity-7424555579538358272-KGSO
> [^pg3-5]: https://www.oecd-events.org/e/effective-uses-of-generative-ai-in-education
> [^pg3-6]: https://www.youtube.com/watch?v=avUkaKBbwww
> [^pg3-7]: https://www.oecd.org/en/topics/sub-issues/digital-education.html
> [^pg3-8]: https://www.digitaleducationcouncil.com/resource-library-items/ai-in-higher-education-global-survey-2026
> [^pg3-9]: https://www.oecd.org/en/publications/oecd-digital-education-outlook-2026_062a7394-en.html
> [^pg3-10]: https://www.oecd.org/content/dam/oecd/en/publications/reports/2026/01/oecd-digital-education-outlook-2026_940e0dd8/062a7394-en.pdf

---

**クエリ:** 生成AI チャットボット 確証バイアス エコーチェンバー 教育現場 具体的事例 2024 2025

> [!note] 概況：確証バイアスとエコーチェンバーの顕在化
> 2024〜2025年における教育現場の具体的な事例では、生成AIチャットボットの活用により生徒の「確証バイアス」が強化され、結果として「エコーチェンバー現象」が顕在化したことが確認されている [^pg4]。
>
> ⚠️ この補足調査(4件目)は整形時に文中の出典番号が失われていたため、個々の主張とURLの対応は復元できていない。以下は本調査全体の出典一覧(9件)。

---

> [!info] 具体的な事例：レポート作成の収斂（2024年・中学校技術科）
> 中学校の技術科において、希望者に生成AIを活用してレポート作成を課した際、AIの出力が特定の内容に収斂されがちな傾向が顕著に見られた。前年度（AI未活用）のレポートと比較し、テキストマイニングツール（KH Coder）を用いて分析した結果、AI活用組では内容の多様性が低下し、特定の結論に集約される傾向が確認された。生徒はAIが生成した「それらしく見える」回答を事実と誤認し、自身の既存の信念を強化する方向でのみAIを利用する傾向（確証バイアス）が見られた。

---

> [!warning] 教育現場で指摘されるリスクと実態（2024〜2025年）
> - **ファクトチェック能力の不足:** 生成AIの出力にバイアスが生じうることを知っている学生の割合は増加傾向にあるが、「AIが書いた内容をファクトチェックする方法を知らない」学生の割合は2024年（63.8%）から2025年（64.0%）へわずかに増加しており、バイアスへの理解の深化に検証スキルが伴っていない。
> - 大学研究室の進捗報告書等で、AIが誤情報を混入させ、教員の質問に対し学生が自ら検証・説明できない事例も報告されている。

---

> [!important] 対策の方向性
> 対策として、教員がAI提供情報を学生に自ら検証・説明させる指導や、児童生徒が「偏ったデータで訓練されたAIがバイアスやエコーチェンバーを生成するリスク」を理解した上で利用するよう訓練する必要性が挙げられている。

---

> [!quote]- 出典脚注(補足調査4) — raw版レポートから復元(整形時に脱落していた分)
> [^pg4]: https://www.mext.go.jp/content/20260630-mxt_shuukyo01-000050664_2.pdf, https://aieduaward.com/paper/2024.html, https://generativeaijapan.or.jp/report/307, https://aisi.go.jp/assets/pdf/20251031_jp.pdf, https://www.soumu.go.jp/johotsusintokei/whitepaper/ja/r05/html/nd123120.html, https://scienceteam.jst.go.jp/app/uploads/2024/03/ai_guide_2024_2_c1_0002_r3.pdf, https://www.sendaidaigaku.jp/dnt2/_sendaidaigaku/access/nic_img/1/files/2025_AI-report.pdf, https://www.jfecr.or.jp/wp-cms/wp-content/uploads/2024/02/zadankai_11.pdf, https://ipsj.ixsq.nii.ac.jp/record/237883/files/IPSJ-SSS2024032.pdf

---

出典: https://www.mext.go.jp/content/20260630-mxt_shuukyo01-000050664_2.pdf, https://aieduaward.com/paper/2024.html, https://generativeaijapan.or.jp/report/307, https://aisi.go.jp/assets/pdf/20251031_jp.pdf, https://www.soumu.go.jp/johotsusintokei/whitepaper/ja/r05/html/nd123120.html, https://scienceteam.jst.go.jp/app/uploads/2024/03/ai_guide_2024_2_c1_0002_r3.pdf, https://www.sendaidaigaku.jp/dnt2/_sendaidaigaku/access/nic_img/1/files/2025_AI-report.pdf, https://www.jfecr.or.jp/wp-cms/wp-content/uploads/2024/02/zadankai_11.pdf, https://ipsj.ixsq.nii.ac.jp/record/237883/files/IPSJ-SSS2024032.pdf