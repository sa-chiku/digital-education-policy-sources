---
title: 日豪AI教育政策比較
date: 2026-07-12
tags: [research, policy-comparison, ai-education, digital-education]
status: active
source_version: v3
notebooklm: https://notebooklm.google.com/notebook/a384e8d6-b78e-40f7-b0f9-b6ce43134f8a
---

> [!link] NotebookLM
> [一次資料PDF4件+補足調査3件+レポート本体](https://notebooklm.google.com/notebook/a384e8d6-b78e-40f7-b0f9-b6ce43134f8a) をまとめたNotebookLMノートブック

# 問い

日本とオーストラリアのAI・デジタルの教育利用(特に高等学校におけるポリシー)の相違点は何か

# 使用したソース一覧

> [!info] 初等中等教育段階における生成AIの利活用に関するガイドライン Ver.2.0
> - 発行元: 文部科学省初等中等教育局
> - 発行日: 2024-12-26
> - URL: https://www.mext.go.jp/content/20241226-mxt_shuukyo02-000030823_001.pdf

---

> [!info] 学校現場における生成AIの利活用〜ガイドラインとその実践例〜
> - 発行元: 文部科学省初等中等教育局学校情報基盤・教材課
> - 発行日: 2025-10-06
> - URL: https://www.mext.go.jp/content/20251006-mext_kyoiku01-000042806_07.pdf

---

> [!info] Australian Framework for Generative Artificial Intelligence (AI) in Schools
> - 発行元: Department of Education, Australian Government (Education Ministers)
> - 発行日: 2023-10-05
> - URL: https://www.education.gov.au/download/17416/australian-framework-generative-artificial-intelligence-ai-schools/35400/document/pdf

---

> [!info] 2024 Review of the Australian Framework for Generative Artificial Intelligence in Schools
> - 発行元: National AI in Schools Taskforce / Department of Education, Australian Government
> - 発行日: 2025-06
> - URL: https://www.education.gov.au/download/17416/australian-framework-generative-artificial-intelligence-ai-schools/41436/2024-review-australian-framework-generative-ai-schools/pdf

---

# Claudeによる統合分析

> [!note] 本文中の参照について
> 本文中の `[ソース名 #番号]` は「根拠抜粋」セクションの該当番号に対応。「補足調査によれば」は下記Perplexity補足調査に対応。

---

# 日本とオーストラリアにおける高等学校の生成AI教育ポリシーの相違点

## 1. フレームワークの性格と法的位置付け

### 日本

> [!info] ガイドラインの基本的性格
> 日本の「初等中等教育段階における生成AIの利活用に関するガイドライン Ver.2.0」は、「学校現場における生成 AI の利活用を一律に禁止したり義務付けたりするものではない」と一次資料に記載されている [MEXTガイドラインVer.2.0 #1]。

---

> [!tip] 制度設計の方向性と運用上の留意点
> 「教育委員会が主導して制度設計や利活用の方向性を示すことが重要」としつつも、「一律に禁止したり、義務付けたりするような硬直的な運用は望ましくない」と一次資料に明記されており [MEXTガイドラインVer.2.0 #12]、あくまで**参考資料**としての性格が明確に示されている。

---

### オーストラリア

> [!info] フレームワークの性格と適用範囲
> Australian Framework for Generative Artificial Intelligence (AI) in Schoolsは、「aspirational in nature（理念的性格）」であり、安全・倫理的・責任ある利用の**あるべき姿を定義するもの**と一次資料に記載されている [Australian Framework #3]。補足調査によれば、このフレームワークは2024年1月より全州・準州の教育大臣が正式に承認して発効しており、K-12（小学校から高校まで）の全学校段階に一律に適用される国家統一的な基盤となっているが、具体的実施は各州・準州に委ねられている。

---

> [!tip] 比較上の注意点：政治的コミットメントの明示度
> 両国のガイドラインはいずれも「強制力のない指針」という点で共通するが、日本では教育委員会単位での裁量が強調されているのに対し、オーストラリアでは全教育大臣が合意した**国家優先事項**として位置付けられており [2024 Review #12]、政治的コミットメントの明示度に差がある。

---

## 2. 高等学校段階に特化した規定の有無

### 日本

> [!info] 高等学校に固有のガイドライン規定
> 日本のガイドラインは高等学校に固有の規定を持ち、例えば「情報セキュリティの重要性とその具体的対策について考えさせる学習活動（高等学校段階のみ）」と一次資料に記載されており [MEXTガイドラインVer.2.0 #7]、発達段階に応じた段階的な学習活動の差異化が国レベルのガイドラインに明記されている。

---

> [!note] 高等学校段階の実践事例の収集・共有
> 実践事例も複数の高等学校（竜ヶ崎第一高等学校でのPythonプログラミング、酒田光陵高等学校でのゲーム開発、情報科学高等学校でのデータベース構築）が具体的に示されており [学校現場における生成AIの利活用 #10, #11, #12]、国レベルで高校段階の実践例が収集・共有されている。

---

### オーストラリア

> [!info] 国家フレームワークの構造
> 補足調査によれば、オーストラリアの国家フレームワークには**高等学校特有のセクションや章は存在しない**。6つのコア原則と25のガイド文はK-12全体に適用されるものであり、高校段階の具体的規定は各州の政策や各学校のローカルポリシーに委ねられている。
>
> ただし、補足調査では年齢帯として「中等教育生徒（Year 7–12）はブレインストーミングや概念説明への利用が帰属明示付きで可能」とする基準が示されているが、これは一次資料には直接記載されておらず、あくまで補足調査によれば州レベルの実施ガイダンスで言及されているにとどまる。

---

> [!warning] 粒度差の指摘
> 日本側の一次資料は高校段階の固有規定と具体的実践事例を豊富に含む一方、オーストラリア側の一次資料は原則的記述にとどまり、高校段階の具体的運用は補足情報に依存せざるを得ない。この情報粒度の差それ自体が、両国の政策設計思想の違い（日本＝中央集権的な詳細ガイダンス、オーストラリア＝原則重視・現場委任）を反映している可能性がある（本抜粋からの推測）。

---

## 3. 学習指導要領・カリキュラムとの接続

### 日本

> [!info] 学習指導要領とAI利活用の関係
> 「現行の学習指導要領は、AIの存在を前提として」資質・能力育成を目指していると一次資料に記載されており [MEXTガイドラインVer.2.0 #2]、「生成AIの利活用は、学習指導要領に示す資質・能力の育成に寄与するかを吟味した上で行うべき」という明確な判断基準が設けられている [MEXTガイドラインVer.2.0 #5]。
>
> すなわち、**生成AIの利活用適否を判断する規範的基準として学習指導要領が機能**している。

---

### オーストラリア

> [!info] AIコンテンツのカリキュラム位置付け
> オーストラリアでは「AIコンテンツのエラボレーション（具体化）」として、AI をオーストラリア・カリキュラム内に明確に位置付け、教員が活用できるオプショナルな内容詳細を提供すると一次資料に記載されている [2024 Review #8]。また「カリキュラムコネクション：人工知能」として、教員・学校がカリキュラム全体の関連性を把握できるよう全校的計画を支援すると記載されている [2024 Review #7]。

---

> [!warning] オプション的・支援的な性格にとどまる点
> これらは**オプション的・支援的な性格**であり、日本のように「カリキュラム適合性の判断基準」として機能するものではない。

---

> [!tip] 補足調査における留意点
> 補足調査によれば、デジタルテクノロジーカリキュラムへのAIリテラシー統合が Year 1（小学1年）から求められているが、この点の一次資料上の根拠は確認できない。

---

## 4. 学術的誠実性（Academic Integrity）と評価への対応

### 日本

> [!warning] 不適切使用の明示的列挙
> 「各種コンクールの作品やレポート・小論文等について、生成AI による生成物をほぼそのまま自己の成果物として応募・提出する」ことが不適切例として挙げられ [MEXTガイドラインVer.2.0 #10]、「定期考査や小テスト等で使わせる」ことも不適切例として明記されている [MEXTガイドラインVer.2.0 #11]。

---

> [!quote] 指導方針の根拠
> 「生成AIによる生成物をそのまま自己の成果物として使用することは自分のためにならない」と指導を求めている [学校現場における生成AIの利活用 #14]。

---

### オーストラリア

> [!quote] 一次資料の記述
> 「学習設計および評価において、AIツールをどのように使用すべきか・すべきでないかを明記し、生徒の能力を公平に評価できるようにする」[Australian Framework #10]
>
> 「学術的誠実性として、生徒が適切な帰属明示を含めた倫理的な利用ができるよう支援する」[Australian Framework #11]

---

> [!tip] 日本との対比――「禁止の列挙」vs「倫理的利用の設計」
> 日本が「使わせない場面」を具体的列挙で規定するのに対し、オーストラリアは「倫理的に使わせる方法の設計」に重点を置くという方向性の相違がある。

---

> [!info] 帰属明示を条件とした利用許容
> 補足調査によれば、オーストラリアでは**帰属明示（attribution）を条件にした利用許容**の考え方が採用されており、一律禁止よりも責任ある利用の教育を優先する方針が州レベルでも共通している。

---

## 5. プライバシー・データ保護規定

### 日本

> [!note] 利活用上の注意点
> 「氏名や写真等の個人情報を入力させないこと、著作権侵害につながるような使い方をさせないこと」という注意点が一次資料に示されており [学校現場における生成AIの利活用 #9]、「年齢制限等の最新の利用規約を確認・遵守し、教師の適切な指導監督の下で利活用させること」も明記されている [学校現場における生成AIの利活用 #9]。

---

### オーストラリア

> [!info] プライバシーとデータ保護の規定
> 「プライバシーとデータ保護として、生成AIツールはプライバシーとデータの権利を尊重し、オーストラリア法を遵守し、不必要な収集を避け、保持を制限し、流通防止と生徒データの販売禁止を行う形で使用される」と一次資料に具体的に規定されている [Australian Framework #15]。

---

> [!tip] 保護者のオプトイン同意義務と日本との対比
> 補足調査によれば、**学校メール＋パスワード以上の個人データを必要とするツールについては保護者のオプトイン同意取得**が義務付けられており、日本より詳細な同意取得手続きが規定されている。

---

## 6. 人間中心の原則と説明責任

> [!info] 日本における人間中心の原則
> 日本では「人々の能力を拡張し、多様な幸せの追求を可能とするためにAIは活用されるべき」という人間中心の原則が一次資料に記載されており [MEXTガイドラインVer.2.0 #4]、「出力はあくまでも参考の一つであり、最後は人間が判断し責任を持つことが重要」とも記されている [学校現場における生成AIの利活用 #3]。

---

> [!info] オーストラリアにおける人間中心の原則と説明責任
> オーストラリアでも「教師と学校リーダーが意思決定の制御を保持し、生成AIツールの支援による決定に対して説明責任を持つ」と一次資料に明記されており [Australian Framework #14]、「生成AIツールは人間の意思決定における説明責任と人間の主体性を保持する形で使用される」とも記載されている [Australian Framework #13]。

---

## 7. 保護者・地域コミュニティへの関与

### 日本

> [!info] 保護者への周知・理解獲得の要件
> 「児童生徒が学校外で生成AIを利活用する可能性も踏まえ、生成AIの不適切な利活用が行われないよう、保護者に対し周知し、理解を得ているか」と一次資料に記載されており [学校現場における生成AIの利活用 #15]、保護者への**周知・理解獲得**が求められている。

---

### オーストラリア

> [!info] フレームワークの対象者と保護者の位置付け
> フレームワークの目的・対象者として「policy makers, school leaders, teachers, support staff, parents and students」が明示されており [Australian Framework #2]、保護者が政策の対象として正面から位置付けられている。

---

> [!tip] 日本との対比：同意手続きの積極性
> 補足調査によれば、個人データを要するツール利用に際して**オプトイン同意**が必要とされており、日本の「周知・理解」よりも積極的な同意手続きが求められている。

---

## 8. EdTech製品への供給側規制:「National Product Expectations」

### 日本

> [!warning] 規制対象の限定性——供給側への言及不在
> 日本の一次資料には、EdTech開発者・提供事業者側に向けた規制や認証制度への言及は見当たらない。ガイドラインの読者は「教職員や教育委員会等の学校教育関係者」に限定されており [MEXTガイドラインVer.2.0 #1]、生成AIツールを開発・提供する事業者そのものを名宛人とする基準は、少なくとも本ソースの範囲では確認できない。

---

> [!important] 日本の規律構造の核心
> すなわち日本の規律は**需要側（学校・教員の利用実践）**に一貫して焦点が当てられている。

---

### オーストラリア

> [!quote] 一次資料：AI Compliance and Standards 作業部会の役割
> 「AI Compliance and Standards作業部会がAI教育製品の全国的な期待値の設定という重要プロジェクトを監督している」 [2024 Framework Review #10]
>
> 「このプロジェクトはEdTech開発者・適応者・展開者に対し、学校用に開発されたAI製品についての一貫した全国的な期待値を伝えることを目的とする」 [2024 Framework Review #11]

---

> [!info] National Product Expectations の概要
> 補足調査によれば、この"National Product Expectations"は、Education Services Australia（ESA）が連邦政府から **100万豪ドルの投資** を受けて主導しており、以下の3つの柱で構成される：
>
> 1. **プライバシー・情報セキュリティ技術基準フレームワーク** — 既存の「ST4S（Safer Technologies for Schools）」を、AI対応教育技術製品向けに拡張・更新したもの
> 2. **人権・ウェルビーイング基準** — 事業者側が主張する「説明可能性」「非差別性」「異議申し立て可能性」等を、第三者が実際に検証できるようにする基準
> 3. **教育効果の評価手法** — Australian Education Research Organisation（AERO）と共同で、AI対応教育技術製品の教育的効果を厳密に評価する手法を策定
>
> 現時点では、この基準は一部のソフトウェアベンダーを対象とした **パイロット試行段階** にあり、先住民データ主権（Indigenous Data Sovereignty）への配慮も組み込まれている。
>
> 出典（補足調査）: [ESA — Education Services Australia Receives Investment to Guide Generative AI Technology in Schools](https://www.esa.edu.au/resources/news-articles/article-detail/education-services-australia-receives-investment-to-guide-generative-ai-technology-in-schools), [Paul Ramsay Foundation — Australia needs quality assurance to harness benefits of AI and edtech](https://www.paulramsayfoundation.org.au/news-resources/australia-needs-quality-assurance-to-harness-benefits-of-ai-and-edtech-for-students-and-schools)

---

> [!important] 日本との対比：規制の射程の非対称性
> これは日豪の規制アーキテクチャの最も明確な非対称性の一つである。オーストラリアは学校・教員向けの利用ガイダンス（Australian Framework本体）に加えて、**製品そのものを認証・検証する供給側の仕組みを国家レベルで別途構築中**である。日本のMEXTガイドラインには、これに相当する「AI教育製品自体の基準策定」という発想がソース上確認できない——日本の議論が専ら「教員がどう使うべきか」という利用実践に集中しているのに対し、オーストラリアは「そもそもどんな製品が学校に入ってよいか」という市場側の入り口を規律しようとしている点で、規制の射程が一段階手前にまで及んでいる。

---

> [!warning] 対比の解釈上の留意点
> 補足調査によれば、この基準はまだパイロット段階であり法的拘束力を持つ全国統一制度としては未確立である。したがって現時点での対比は「制度の有無」ではなく「**規制哲学の方向性の違い**」として理解すべきである。

---

## まとめ：主要な相違点の整理

| 観点 | 日本 | オーストラリア |
|------|------|----------------|
| **文書の性格** | 参考資料（禁止・義務付けなし）[MEXTガイドラインVer.2.0 #1] | 理念的フレームワーク（全大臣合意）[Australian Framework #3] |
| **高校段階の固有規定** | 国レベルで明記（情報セキュリティ等）[MEXTガイドラインVer.2.0 #7] | 国レベルでは規定なし（補足調査） |
| **カリキュラムとの関係** | 学習指導要領が判断基準として機能 [MEXTガイドラインVer.2.0 #5] | オプション的内容詳細として位置付け [2024 Review #8] |
| **評価での不使用規定** | 定期考査等での使用を不適切例として列挙 [MEXTガイドラインVer.2.0 #11] | 帰属明示付きの倫理的利用を推奨 [Australian Framework #11] |
| **データ保護** | 個人情報入力禁止 [学校現場における生成AIの利活用 #9] | オプトイン同意・データ販売禁止を明規 [Australian Framework #15] |
| **実施主体の裁量** | 教育委員会単位での柔軟対応 [MEXTガイドラインVer.2.0 #12] | 州・準州および学校単位（補足調査） |
| **EdTech製品への供給側規制** | ソース上、該当する枠組みなし | ESA主導「National Product Expectations」策定中（パイロット段階、補足調査）[2024 Review #10][#11] |

> [!note] 両国比較の総括
> 両国はいずれも生成AIの一律禁止を避け、責任ある利用の促進という基本姿勢を共有しているが、日本が **国レベルの詳細ガイダンスと学習指導要領との整合性** を軸とするのに対し、オーストラリアは **原則の国家統一と実施の州・学校委任** という構造を採用している点が最大の相違点である。

---

> [!warning] 情報の粒度差について
> オーストラリアの高校段階の具体的運用の詳細については、一次資料の記述が原則論にとどまり補足調査への依存が大きいため、情報の確実性において両国間で粒度差があることに留意が必要である。

---

# 根拠抜粋(一次資料からの引用・Gemini抽出)

> [!quote]- 原文抜粋一覧
> 各ソースの原文からそのまま抜粋。要約・言い換えは行っていない。

---

### 初等中等教育段階における生成AIの利活用に関するガイドライン Ver.2.0

> [!info] ガイドラインの位置付けと目的
> 「本ガイドラインは、教職員や教育委員会等の学校教育関係者を主たる読み手として、学校現場における生成 AI の適切な利活用を実現するための参考資料となるよう、利活用に当たっての基本的な考え方や押さえるべきポイントをまとめたものであり、学校現場での生成 AI の利活用を一律に禁止したり義務付けたりするものではない。」[ソース名 #1]
>
> **論点:** 日本の生成AIガイドラインの位置付けと目的

---

> [!info] AI時代に育成すべき資質・能力に関する学習指導要領の理念
> 「現行の学習指導要領は、AI の存在を前提として、生きて働く「知識及び技能」、未知の状況にも対応できる「思考力、 判断力、表現力等」、学びを人生や社会に生かそうとする「学びに向かう力、人間性等」といった、社会の変化が加速し、複雑となるこれからの時代に必要な資質・能力を確実に育成することを目指している。」[ソース名 #2]
>
> **論点:** AI時代に育成すべき資質・能力に関する学習指導要領の理念

---

> [!info] 生成AIの教育利用への期待とガイドライン策定の背景
> 「AI 時代を生きる子供たちが生成 AI をはじめとするテクノロジーをツールとして使いこなし、一人一人が才能を開花できるようになることは重要であり、生成 AI の学校における利活用は、そのための助けになり得るものである。学校現場が混乱したり、不安を感じたりすることなく、学習指導要領に示す資質・能力の育成に向けて適切に生成 AI と向き合い、利活用することができるよう、学校現場の視点から基本的な方針及び実務的なポイントを示すことが求められている。」[ソース名 #3]
>
> **論点:** 生成AIの教育利用への期待とガイドライン策定の背景

---

> [!quote] AI利用における人間中心の原則
> 「AI の利用は、憲法及び国際的な規範の保障する基本的人権を侵すものであってはならない。AI は、人々の能力を拡張し、多様な人々の多様な幸せの追求を可能とするために開発され、社会に展開され、活用されるべきである。」という「人間中心の原則」9がある。」[ソース名 #4]
>
> **論点:** AI利用における人間中心の原則

---

> [!important] 児童生徒の学習における生成AI利活用の判断基準
> 「児童生徒の学びにおいては、学習指導要領に示す資質・能力の育成に寄与するか、教育活動の目的を達成する観点から効果的であるかを吟味した上で利活用するべきであり、生成 AI を利活用することが目的であってはならない。」[ソース名 #5]
>
> **論点:** 児童生徒の学習における生成AI利活用の判断基準

---

> [!info] 生成AI時代における情報活用能力の育成強化
> 「情報活用能力の育成に当たっては、生成 AI が社会の中で果たす役割や影響、生成 AI に関する法・制度やマナー等について科学的な理解に裏打ちされた形で理解すること、問題の発見・解決等に向けて生成 AI を適切かつ効果的に利活用し、情報社会に主体的に参画する態度を身に付けていくことが期待される。」[ソース名 #6]
>
> **論点:** 生成AI時代における情報活用能力の育成強化

---

> [!note] 高等学校における情報モラル教育での情報セキュリティ対策の強化
> 「生成 AI の普及も念頭に置きつつ、発達の段階に応じて以下のような学習活動を強化することが求められる。11
> • 情報セキュリティの重要性とその具体的対策について考えさせる学習活動（高等学校段階のみ）」[ソース名 #7]
>
> **論点:** 高等学校における情報モラル教育での情報セキュリティ対策の強化

---

> [!tip] 教職員による校務での生成AI積極的利活用の方針
> 「教職員が生成 AI の仕組みや特徴を理解した上で、生成された内容の適切性を判断できる範囲内で利用するという前提で、校務において生成 AI を積極的に利活用することは有用であると考えられる。」[ソース名 #8]
>
> **論点:** 教職員による校務での生成AI積極的利活用の方針

---

> [!info] 児童生徒の学習における生成AI利活用場面の具体例
> 「児童生徒の生成 AI の利活用場面としては、「生成 AI 自体を学ぶ場面（生成 AI の仕組み、利便性・リスク、留意点）」、「使い方を学ぶ場面（より良い回答を引き出すための生成 AI との対話スキル、ファクトチェックの方法等）」、「各教科等の学びにおいて積極的に用いる場面（問題を発見し、課題を設定する場面、自分の考えを形成する場面、異なる考えを整理したり、比較したり、深めたりする場面等での利活用）」等 が考えられる。」[ソース名 #9]
>
> **論点:** 児童生徒の学習における生成AI利活用場面の具体例

---

> [!warning] 児童生徒による生成AI利用の不適切例（成果物としての提出）
> 「各種コンクールの作品やレポート・小論文等について、生成 AI による生成物をほぼそのまま自己の成果物として応募・提出する（コンクールへの応募を推奨する場合は応募要項等を踏まえた十分な指導が必要）」[ソース名 #10]
>
> **論点:** 児童生徒による生成AI利用の不適切例（成果物としての提出）

---

> [!warning] 児童生徒による生成AI利用の不適切例（評価場面での使用）
> 「定期考査や小テスト等で使わせる（学習の進捗や成果を把握・評価するという目的に合致しない。CBT で行う場合も、フィルタリング等により、生成 AI が使用し得る状態とならないよう十分注意すべき）」[ソース名 #11]
>
> **論点:** 児童生徒による生成AI利用の不適切例（評価場面での使用）

---

> [!important] 教育委員会の役割と柔軟な運用方針
> 「教育委員会が主導して制度設計や利活用の方向性を示すことが重要である。生成 AI の実践を積み重ねているかどうかは学校や教職員によって大きな差があるため、域内の各学校の実態を十分に踏まえた柔軟な対応を講じることが必要であり、一律に禁止したり、義務付けたりするような硬直的な運用は望ましくない。」[ソース名 #12]
>
> **論点:** 教育委員会の役割と柔軟な運用方針

---

> [!note] オーストラリアにおけるAI教育フレームワークの存在
> 「Australian Framework for Generative Artificial Intelligence (AI) in Schools（豪州、Department of Education、2023 年 11 月）」[ソース名 #13]
>
> **論点:** オーストラリアにおけるAI教育フレームワークの存在

---

### 学校現場における生成AIの利活用〜ガイドラインとその実践例〜

> [!info] 日本の生成AIガイドラインの対象と目的
> 初等中等教育段階における生成AIの利活用に関するガイドライン(Ver.2.0) 教職員や教育委員会等の学校教育関係者を主たる読み手として、学校現場における生成AIの適切な利活用を実現するための参考資料となるよう、生成AIの概要や基本的な考え方、場面や主体に応じて押さえておくべきポイントをまとめたもの。令和5年7月に暫定的なガイドライン(Ver.1.0)を公表し、令和6年12月にガイドライン(Ver.2.0)へと改訂。[ソース名 #1]

---

> [!warning] 日本のガイドラインにおける生成AIのリスク認識と利用の考え方
> ※ ここで取り上げるリスクや懸念は代表的なものであって、生成 AI が有するリスクを網羅したものではない。
>
> ※ また、このようなリスクや懸念の存在が直ちに生成 AI の利用を妨げるものではなく、スマートフォン等が広く普及し、既に一定数の児童生徒が学校外で生成 AI に触れているとの指摘もある中においては、リスクを正しく認識した上で、学校現場において正しく向き合っていくことが重要である。[ソース名 #2]

---

> [!important] 日本の生成AI教育利用の人間中心原則
> - 生成AIを人間の能力を補助、拡張し、可能性を広げてくれる有用な道具になり得るものと捉えるべきである。
> - その上で、出力はあくまでも「参考の一つである」ことを認識するとともに、リスクや懸念を踏まえつつ、最後は人間が判断し、責任を持つことが重要である。[ソース名 #3]

---

> [!info] 日本における児童生徒の生成AI利用の目的と基準
> 学習指導要領に示す資質・能力の育成に寄与するか、教育活動の目的を達成する観点から効果的であるかを吟味した上で利活用するべきであり、生成AIを利活用することが目的であってはならない。[ソース名 #4]

---

> [!tip] 日本の教師に求められるAIリテラシーと役割
> - 指導計画や学習環境の設定、丁寧な見取りと支援といった、学びの専門職としての教師の役割は、より重要なものになる。
> - 生成AIの仕組みや特徴を理解するなど、教師には一定の AI リテラシーを身に付けることが求められる。[ソース名 #5]

---

> [!info] 日本における生成AIを通じた情報活用能力育成の重視
> - 生成AIの仕組みの理解、学びに生かしていく視点、近い将来生成AIを使いこなすための力を、各教科等の中において意識的に育てていく姿勢は重要である。
> - 生成AIが社会生活に組み込まれていくことを念頭に、発達の段階等を踏まえつつ、情報モラルを含む情報活用能力の育成を充実させていくことが必要である。[ソース名 #6]

---

> [!note] 日本の児童生徒が生成AIを学習に利用する際の考慮点
> - 発達の段階や情報活用能力の育成状況に留意しつつ、リスクや懸念に対策を講じた上で利活用を検討すべき
> - その際、学習指導要領に定める資質・能力の育成に寄与するか、教育活動の目的を達成する観点から効果的であるかを吟味することが必要[ソース名 #7]

---

> [!quote]- 原文抜粋一覧
> **[ソース名 #8] 論点: 日本における児童生徒の生成AI学習利用の具体例**
>
> - 情報モラル教育の一環として、生成AIが生成する誤りを含む出力を教材に、その性質や限界に気付く
> - グループの考えをまとめる、アイディアを出す活動の途中段階で、一定の議論やまとめをした上で、足りない視点を見つけ議論を深める目的で活用する
> - 英会話の相手として活用したり、より自然な英語表現への改善や一人一人の興味関心に応じた単語リストや例文リストの作成に活用したりする
> - プログラミングの授業において、児童生徒のアイディアを実現するためのプログラムの制作に活用する 等

---

> [!warning] 日本の児童生徒が生成AIを学習に利用する際の注意点
> - 年齢制限等の最新の利用規約を確認・遵守し、教師の適切な指導監督の下で利活用させることが必要
> - 氏名や写真等の個人情報を入力させないこと、著作権侵害につながるような使い方をさせないこと
> - 出力に偏りがないかなど、教育目的に照らして適切かを教師が随時判断することが必要[ソース名 #9]

---

> [!quote]- 原文抜粋一覧
> **[ソース名 #10] 論点: 日本の高等学校における生成AIプログラミング学習事例**
>
> 茨城県立 竜ヶ崎第一高等学校 高等学校 デスクトップアプリの作成（１年次・情報科）
> Pythonを用いたアプリの作成時にAIを活用してコードを作成。プロンプトを工夫しながら、目的に見合うコードを組み込みアプリを完成させる。
>
> ---
>
> **[ソース名 #11] 論点: 日本の高等学校における生成AIシステム設計学習事例**
>
> 山形県立 酒田光陵高等学校 高等学校 生成AIを活用したシステムの設計（情報Ⅱ）
> JavaScriptでゲームの開発を行う授業。実際のゲームの動作を考え、生成AIに繰り返し指示し、何が不足するのかを考えながら理想を目指す。
>
> ---
>
> **[ソース名 #12] 論点: 日本の高等学校における生成AIデータベース構築学習事例**
>
> 大分県立 情報科学高等学校 高等学校 データベースの構築（情報科）
> データベースのSQLを扱う実習において、作成する構文やエラーの解読に活用。40人一斉の実習で、生成AIが各生徒にアドバイスを提供。

---

> [!tip] 日本の教育委員会における生成AI利用推進の役割
> - 教育委員会が主導して制度設計や利活用の方向性を示すことが重要
> - 各学校の実態を十分に踏まえた柔軟な対応を講じることが必要であり、一律に禁止・義務付けるなどの硬直的な運用は望ましくない
> - 先行事例や教材・ノウハウの周知・共有、効果的な活用を促進する研修の実施により、生成AIの適切な利活用を推進する環境を整備することが必要[ソース名 #13]

---

> [!note] 日本の生成AIガイドラインにおける成果物利用に関する指導要点
> 生成AIによる生成物をそのまま自己の成果物として使用することは自分のためにならないこと、使用方法によっては不適切又は不正な行為になることを十分に指導しているか。[ソース名 #14]

---

> [!note] 日本の生成AIガイドラインにおける保護者への周知要点
> 児童生徒が学校外で生成 AIを利活用する可能性も踏まえ、生成AIの不適切な利活用が行われないよう、保護者に対し周知し、理解を得ているか[ソース名 #15]

---

### Australian Framework for Generative Artificial Intelligence (AI) in Schools

> [!info] フレームワークの包括的な目的
> "The Australian Framework for Generative Artificial Intelligence (AI) in Schools (the Framework) seeks to guide the responsible and ethical use of generative AI tools in ways that benefit students, schools and society." [ソース名 #1]

---

> [!info] フレームワークの目的と対象者
> "The purpose of the Framework is to provide guidance on understanding, using and responding to generative AI in Australian school-based education. It supports policy makers, school leaders, teachers, support staff, parents and students." [ソース名 #2]

---

> [!info] フレームワークの性質と目指す理想像
> "The Framework is aspirational in nature, defining what safe, ethical and responsible use of generative AI should look like to support better school outcomes." [ソース名 #3]

---

> [!info] 教育成果向上への生成AI利用の目標
> "The Framework aims to recognise how the appropriate use of generative AI tools can enhance teaching and learning outcomes for all members of Australian school communities." [ソース名 #4]

---

> [!info] 学校における生成AIの安全で倫理的な利用目標
> "The Framework aims to achieve the safe, responsible and ethical use of generative AI tools in Australian schools." [ソース名 #5]

---

> [!note] 生成AIが教育にもたらす機会
> "Generative AI technology has great potential to assist teaching and learning and reduce administrative workload in Australian schools." [ソース名 #6]

---

> [!warning] 生成AI利用における主なリスクとリスク管理の必要性
> "Risk management should also be appropriate for the potential consequences. These consequences include the potential for errors and algorithmic bias in generative AI content; the misuse of personal or confidential information; and the use of generative AI for inappropriate purposes, such as to discriminate against individuals or groups, or to undermine the integrity of student assessments." [ソース名 #7]

---

> [!important] 生成AI対応が国家的な教育優先事項であること
> "In February 2023, Education Ministers agreed that responding to the risks and harnessing opportunities for Australian schools and students arising from generative AI technologies is a national education priority." [ソース名 #8]

---

> [!quote]- 原文抜粋一覧（原則・方針関連）
>
> **[9] 論点: 生成AIを教育と学習の支援・強化に用いる原則**
> "1. Teaching and Learning Generative AI tools are used to support and enhance teaching and learning."
>
> ---
>
> **[10] 論点: 学習設計および評価における生成AIツールの使用規定**
> "1.5 Learning design: work designed for students, including assessments, clearly outlines how generative AI tools should or should not be used and allows for a clear and unbiased evaluation of student ability."
>
> ---
>
> **[11] 論点: 学術的誠実性と倫理的な生成AIツールの使用**
> "1.6 Academic integrity: students are supported to use generative AI tools ethically in their schoolwork, including by ensuring appropriate attribution."
>
> ---
>
> **[12] 論点: 生成AIツールの機能と影響に関する透明性の原則**
> "3. Transparency School communities understand how generative AI tools work, how they can be used, and when and how these tools are impacting them."
>
> ---
>
> **[13] 論点: 生成AI利用における説明責任と人間の意思決定の保持**
> "5. Accountability Generative AI tools are used in ways that are open to challenge and retain human agency and accountability for decisions."
>
> ---
>
> **[14] 論点: 教師と学校リーダーの意思決定における人間の責任**
> "5.1 Human responsibility: teachers and school leaders retain control of decision making and remain accountable for decisions that are supported by the use of generative AI tools."
>
> ---
>
> **[15] 論点: プライバシーとデータ保護に関する具体的な方針**
> "6.1 Privacy and data protection: generative AI tools are used in ways that respect and uphold privacy and data rights, comply with Australian law, and avoid the unnecessary collection, limit the retention, prevent further distribution, and prohibit the sale of student data."

---

### 2024 Review of the Australian Framework for Generative Artificial Intelligence in Schools

> [!info] フレームワークの設立と目的
> "In October 2023, Education Ministers published the Australian Framework for Generative Artificial Intelligence in Schools (the Framework) to address the opportunities and challenges presented by generative artificial intelligence (GenAI)." [ソース #1]
>
> → 論点: オーストラリアにおけるAI教育フレームワークの設立と目的

---

> [!info] フレームワークの実施主体と開始時期
> "States, territories, and non-government schooling sectors began work to implement the Framework into their own education systems from Term 1, 2024." [ソース #2]
>
> → 論点: フレームワークの実施主体と開始時期

---

> [!info] フレームワークの年次レビュー方針
> "Education Ministers agreed that a review of the Framework should take place annually to keep up with the rapidly evolving nature of GenAI." [ソース #3]
>
> → 論点: フレームワークの年次レビュー方針

---

> [!note] オーストラリアのGenAIフレームワークの評価
> "The Taskforce is satisfied that the Framework provides an evidence-informed, best practice framework for the use of GenAI in Australian schools." [ソース #4]
>
> → 論点: オーストラリアのGenAIフレームワークの評価

---

> [!info] AI教育における国の重点分野
> "The Taskforce's two working groups (AI in Practice and AI Compliance and Standards) deliver and oversee national work in six focus areas to enhance teaching and learning: workload, data security and privacy, equity, market power, research, and copyright." [ソース #5]
>
> → 論点: AI教育における国の重点分野

---

> [!info] AI実践に関する主要な取り組み
> "The AI in Practice working group, co-led by the Australian Institute for Teaching and School Leadership (AITSL) and the Australian Education Research Organisation (AERO) has three nationally-funded projects and initiatives in the Taskforce's 2024-25 Workplan." [ソース #6]
>
> → 論点: AI実践に関する主要な取り組み
>
> **i. カリキュラムにおけるAIの連携支援**
> "Curriculum connections: Artificial Intelligence: Supports whole school planning for AI by helping teachers and schools to see the interrelationships across the dimensions of the Australian Curriculum." [ソース #7]
> → 論点: カリキュラムにおけるAIの連携支援
>
> **ii. AIのカリキュラムへの具体化と教員へのガイダンス**
> "Artificial intelligence content elaborations: Clearly positions AI within the Australian Curriculum and provides teachers with optional content elaborations about AI that can be used to enhance learning." [ソース #8]
> → 論点: AIのカリキュラムへの具体化と教員へのガイダンス
>
> **iii. 生成AIの教育利用に関する研究課題**
> "Scoping of potential research into Generative AI: Scoping potential research into the use of GenAI in education and its impact on learning outcomes (particularly for students from historically disadvantaged cohorts)." [ソース #9]
> → 論点: 生成AIの教育利用に関する研究課題

---

> [!info] AI製品のコンプライアンスと基準に関する取り組み
> "The AI Compliance and Standards working group, led by Education Services Australia (ESA) is overseeing one key project in the Taskforce's 2024-25 Workplan: National Product Expectations." [ソース #10]
>
> → 論点: AI製品のコンプライアンスと基準に関する取り組み
>
> "This project aims to communicate to Edtech developers, adaptors and deployers of AI consistent national expectations for AI products developed for school use." [ソース #11]
> → 論点: AI教育製品に対する全国的な期待値の設定

---

> [!important] AI教育への継続的な国家優先度と評価メカニズム
> "National and jurisdictional work in the AI in schools space will continue as a national priority throughout 2025." [ソース #12]
>
> → 論点: AI教育への継続的な国家優先度
>
> "These efforts will continue to be developed and refined by Taskforce members to align with emerging GenAI technologies, educational priorities and regulatory considerations, and will be assessed through the 2025 Framework Review." [ソース #13]
> → 論点: AI教育の継続的な発展と評価メカニズム

---

# 補足調査(Perplexity, 取得日: 2026-07-12)

一次資料に無い情報を補うため、情報ギャップ判定に基づき実施。

**クエリ:** Australian Framework for Generative AI in Schools high school specific policy guidelines 2024

---

> [!info] Australian Framework for Generative AI in Schools — 基本的性格
> The **Australian Framework for Generative Artificial Intelligence in Schools** (released December 2023) is a **national, aspirational framework** that does **not contain high school-specific policy guidelines** or separate chapters for different secondary levels [1][5]. Instead, it provides **six core principles and 25 guiding statements** applicable to *all* Australian school levels (K–12), including high schools, to guide safe, ethical, and responsible use of generative AI [1][2].

---

### Key Points for High Schools:

| Aspect | Details |
|--------|---------|
| **Nature** | Aspirational guidance (not mandatory legislation) [1] |
| **Scope** | Universal across K–12; no high school-specific section [1][5] |
| **Core Principles** | 1. Teaching & learning, 2. Wellbeing & safety, 3. Information & support, 4. Equitable access, 5. Academic integrity, 6. Governance [1][2] |
| **High School Application** | Schools must adapt the framework into their own **local policies** with age-appropriate rules for secondary students [2][7] |

### Critical Requirements Schools Must Implement (Including High Schools):

> [!warning] Data Privacy & Consent
> - **Data Privacy**: Do not upload personal student/staff information (names, reports, contact details) to AI tools [2][6].
> - **Consent**: Obtain opt-in parental consent before using AI tools requiring data beyond a school email + password [2].

---

> [!warning] Prohibited Uses
> - No media depictions of students/staff/parents (photos, audio, video) [2][6].
> - No disrespectful cultural mimicry (e.g., copying Koorie artwork) [2].
> - No AI replacing teacher-student communication or professional judgment [2].

---

> [!warning] Academic Integrity
> AI must support but not replace human judgment in assessments [8].

---

### How High Schools Should Proceed:

> [!info] 各州・学校が独自ポリシーを策定
> 国家フレームワークには学年別の具体的ルールがないため、**各州および学校が独自の高校向けポリシーを策定**しています。
>
> - **Victoria**: 年齢・科目に関する明示的なガイドラインを含むローカルポリシーの策定を各校に義務付け [2]
> - **NSW**: NSWEduChat（教育省開発ツール）を推奨し、職員によるAI出力の批判的レビューを義務付け [6]
> - **Virtual School Victoria (VSV)**: 教師がAIの限界・バイアスを生徒に説明すること、および氏名・メール以上の情報を要する登録には保護者の同意取得を明示 [8]

---

> [!tip] 実務上の参照先
> 高校段階の具体的なガイドラインについては、**各州教育委員会**（例：Victoria → [education.vic.gov.au](https://www2.education.vic.gov.au/pal/generative-artificial-intelligence/policy)、NSW → [education.nsw.gov.au](https://education.nsw.gov.au/teaching-and-learning/education-for-a-changing-world/guidelines-regarding-use-of-generative-ai)）または**学校のローカルポリシー文書**を参照してください。国家フレームワークは意図的に具体的な内容をローカル実装に委任しています [2][6][7]。

---

> [!warning] フレームワークの版に関する注意
> このフレームワークは2023年末に公開されており、2024年時点で高校段階に特化した改訂版はリリースされていません。各校は2023年版フレームワークを自校の文脈に適応させることが求められています [1][7]。

---

> [!note] 国家フレームワークの概要と州裁量の構造
> オーストラリアの高等学校（Senior Secondary）における生成AIの「年齢別・学校段階別」の単一の規定は存在せず、国が策定した**「教育における生成AIのためのオーストラリア・フレームワーク（Australian Framework for Generative AI in Education）」**が基本的方針として示されています。具体的な運用（年齢や段階に応じた制限や許可）は**各州の教育委員会や学校裁量**で決定されています [3]。
>
> このフレームワークは小学校から大学を対象として策定され（2023年12月策定）、生徒がAIを「責任ある倫理的な方法」で利用することを目的としています。具体的な年齢制限や段階別の規定は各州レベルで異なる場合があります [3]。

---

出典:
- https://apo.org.au/node/325203
- https://www2.education.vic.gov.au/pal/generative-artificial-intelligence/policy
- https://manuelgarcia.info/media/full_paper/generative-ai-policy-k-12-education.pdf
- https://www.academy.vic.gov.au/resources/collections/ai-in-schools
- https://www.education.gov.au/schooling/resources/australian-framework-generative-artificial-intelligence-ai-schools
- https://education.nsw.gov.au/teaching-and-learning/education-for-a-changing-world/guidelines-regarding-use-of-generative-ai
- https://leonfurze.com/2024/03/06/video-understanding-the-australian-framework-for-genai-in-schools/
- https://www.vsv.vic.edu.au/wp-content/uploads/2024/08/VSV_AI_Policy.pdf
- https://link.springer.com/article/10.1007/s13384-025-00801-z

**クエリ:** オーストラリア 高等学校 生成AI ポリシー 年齢別 学校段階別 規定

### 1. 国の基本方針（フレームワークの内容）

> [!info] フレームワークの中心原則
> オーストラリア政府が策定したフレームワークの中心は以下の原則です[3]。
>
> - **人間中心の原則**: AIは人間の学習を支援するものであり、依存することではない。
> - **アセスメント（評価）の誠実性**: 不正防止と学術的誠実性の維持が最重要テーマ。
> - **透明性と説明責任**: AI利用の範囲や方法を明記し、生徒・教師・社会に対して説明する。
> - **対象範囲**: 主に小学校から大学までの教育分野[3]。

---

### 2. 州・学校段階別・年齢別の運用規定（実態）

> [!info] 規定の前提：州の教育方針が実質的ルールを形成
> 国が詳細な年齢制限を定めていないため、各州の教育方針が実質的な「規定」となります。

---

| 学校段階・年齢 | 主要な州の対応例 | 規定・運用の特徴 |
| :--- | :--- | :--- |
| **小学校・低学年**<br>(K-6) | **ニューサウスウェールズ州 (NSW)** | 独自開発の学齢期適応チューター**「NSWEduChat」**を提供。一般のChatGPT等の利用は、教員の管理下または推奨されるツールに限定される傾向[5]。 |
| **中等教育・高校**<br>(7-12) | **全国的・州共通** | **教員の指示がない限り、AI利用は「他人からの支援」とみなされる**（学術的不正に触れる可能性）[2]。<br>・高校では、試験や宿題での利用を**禁止**する学校もあれば、**利用を認める**（出典明記必須）学校もある[2]。<br>・NSW州は**「AI検出ツール」**を開発し、罰則ではなく「責任あるユーザー教育」を目的としている[5]。 |
| **高等教育・大学** | **全国** | 教員が授業方針を学生に知らせる義務があり、**「家に持ち帰り行う宿題」でのAI利用禁止は原則として認められない**（自由な判断）[2]。 |

---

> [!warning] 運用の分散：禁止と容認が学校単位で並立
> 中等教育・高校段階（7-12）では、試験や宿題での利用を**禁止**する学校もあれば、**利用を認める**（出典明記必須）学校も存在し、統一された基準がない[2]。教員の指示がない限り、AI利用は「他人からの支援」とみなされ、学術的不正に触れる可能性がある点も、解釈の一貫性を欠く要因となっている[2]。

---

> [!tip] NSWの対応：罰則より「責任あるユーザー教育」を優先
> ニューサウスウェールズ州（NSW）は独自の学齢期適応チューター**「NSWEduChat」**を開発・提供するとともに、**「AI検出ツール」**を導入している。ただしその目的は罰則ではなく、「責任あるユーザー教育」に置かれている[5]。

---

> [!note] 高等教育段階：AI利用禁止は原則として認められない
> 大学レベルでは、教員が授業方針を学生に知らせる義務がある一方、**「家に持ち帰り行う宿題」でのAI利用禁止は原則として認められない**（自由な判断）とされている[2]。

---

### 3. 高等学校（Senior Secondary）での具体的な扱い

> [!info] 禁止と許可の判断
> 各教員が「授業内課題（試験含む）」での利用方針を決定する自由があり、一律禁止はされていないが、**「利用したら支援を得ているとみなされる」**という原則が適用される[2]。

---

> [!note] 出典明記の義務
> AIを活用して作成した内容は、AIの名称・用途・活用範囲・利用時期を**明記する必要がある**とされる（国の方針に基づく）[1]。

---

> [!warning] リスク管理
> 個人情報の保護、著作権、セキュリティ確保が必須とされ、生徒はAIサービスの**年齢制限（通常18歳以上、または利用規約による制限）も遵守**する必要がある[1]。

---

> [!tip] NSW州の独自措置
> 高校生向けに「AI検出ツール」と「教育特化チューター」を整備し、不正を罰するのではなく**責任ある利用を教育する**方針を明確化している[5]。

---

### 4. 結論と注意点

> [!info] 年齢別規定
> 国レベルで「15歳以下は禁止」といった一律の年齢規定はなく、**利用規約（年齢制限18歳以上など）の遵守**と**教員の指導下での利用**が原則です[1]。

---

> [!info] 学校段階別規定
> 小学生から大学生までを対象とするフレームワークが存在しますが、高校段階での具体的な「許可・禁止」は**学校や教員の裁量**に委ねられています[3]。

---

> [!tip] 実務的な方針
> オーストラリアは「実務的・柔軟」であり、教育現場の裁量を重視する傾向が強く、**一律の禁止ではなく、リテラシー教育と透明性の確保**を重視しています[2][5]。

---

> [!important] 実務上の正解
> 特定の「年齢別・学校段階別」の統一的な法律や規定を探すことは不可能であり、**「国のフレームワーク」を基盤とし、「各州のガイドライン」および「各学校のポリシー」を確認する**ことが実務上の正解となります。特に高校では、教員が授業ごとに利用可否を決定するため、生徒は各授業のルールを個別に確認する必要があります[2]。

---

出典: https://www.taki-hj.ac.jp/ai-guide.html, https://www.nii.ac.jp/event/upload/20260316-takemura-funamori02.pdf, https://www.mext.go.jp/content/2025414-mxt_shuukyo01_000033776_03.pdf, https://datos-insights.com/blog/%E7%B1%B3%E5%85%AC%E7%AB%8B%E5%B0%8F%E4%B8%AD%E9%AB%98%E6%A0%A1%E3%81%AB%E3%81%BF%E3%82%8B%E7%94%9F%E6%88%90ai%E6%B4%BB%E7%94%A8%E3%83%9D%E3%83%AA%E3%82%B7%E3%83%BC%E3%81%AE%E4%BD%9C%E3%82%8A%E6%96%B9/, https://www.kyobun.co.jp/article/2024053106, https://www.iaijoshi-h.ed.jp/3%E6%9C%8819%E6%97%A5%E6%B0%B4%E4%B8%AD%E5%AD%A63%E5%B9%B4%E7%94%9F%E3%81%8B%E3%82%89%E9%AB%98%E6%A0%A12%E5%B9%B4%E7%94%9F%E3%81%BE%E3%81%A7%E3%81%AE25%E5%90%8D%E3%81%AE%E7%94%9F%E5%BE%92%E3%81%8C/, https://jp.linkedin.com/pulse/report-ai-literacy-australian-schools-skiltrak-dlvde?tl=ja, https://www.instagram.com/reel/DL8uZcgTG_n/, https://meglink-saitama.ed.jp/dxcases/warabi

---

**クエリ:** Australia state territory generative AI school policy secondary school implementation 2024

> [!info] 2024年における生成AIの位置づけ
> 2024年、**ChatGPTをはじめとする生成AIツールはオーストラリアの全ての中等学校で正式に許可**されました。教育大臣らが**Australian Framework for Generative AI in Schools**を正式に承認し、**2024年1月**に発効しています [3][8]。

---

> [!warning] 連邦フレームワークと実装の乖離
> 連邦フレームワークは全州・準州の大臣が承認した**統一的な全国的基盤**を提供する一方、**実装の責任は各州・準州および非政府機関に委ねられており**、方針は管轄ごとに異なります [3]。

---

> [!info] 六つのコア原則
> このフレームワークは以下の**六つのコア原則**に基づいて構築されています：人間中心の価値観、透明性、安全性・プライバシー、公平性、協働、持続可能性 [1][3][7]。

### Key Implementation Requirements for Secondary Schools (2024)

| Aspect | Requirement |
| :--- | :--- |
| **Transparency** | All AI use by staff (lesson planning, feedback) and students must be **disclosed** to management, peers, and families [1][5]. |
| **Data Privacy** | Schools must obtain **opt-in parental consent** before using tools requiring personal data beyond school email/password [4]. Uploading personally identifiable information is prohibited [4]. |
| **Age Bands** | **Supervised use only** for students under 13; secondary students (Years 7–12) may use AI for brainstorming and concept explanation **with attribution** [1]. |
| **Assessment** | AI **cannot replace authentic assessments**; schools must prevent AI-generated substitutes for student work [1]. |
| **Curriculum** | AI literacy must be integrated into the **Digital Technologies curriculum from Year 1**, deepening as usage increases [1][7]. |

### State-Specific Nuances (Vic Example)

> [!info] Victoria の固有要件
> **Victoria** issued a specific policy requiring schools to:
> - Direct staff to **not use AI to communicate** with students/parents in ways that undermine authentic learning relationships [4].
> - Ensure tools meet **accessibility and inclusivity obligations** under the *Equal Opportunity Act 2010* (Vic) and federal disability laws [4].
> - **Prohibit** generating media depictions of students/staff or artefacts mimicking cultural traditions disrespectfully [4].

---

> [!note] 他州・連邦レベルの動向
> Other states (e.g., NSW, SA) are developing their own implementation plans, with some referencing **SA SACE Board AI protocols** for senior secondary assessments [7]. The Commonwealth Department of Education provided **$1 million to Education Services Australia** to set "product expectations" for trusted GenAI tools [3].

---

> [!warning] 政策整備と現場実態のギャップ
> Schools are expected to complete policy drafts in **4–6 weeks**, consult for 2 weeks, and approve within one term, with **70% of teachers** already using AI informally prior to policy rollout [1].

---

出典: https://www.teachingjobs.com.au/education-news/how-to-create-whole-school-generative-ai-policy-state-compliance-195, https://www.education.gov.au/schooling/resources/australian-framework-generative-artificial-intelligence-ai-schools, https://www.aph.gov.au/Parliamentary_Business/Committees/House/Former_Committees/Employment_Education_and_Training/AIineducation/Report/Chapter_2_-_Integration_practices_and_policies, https://www2.education.vic.gov.au/pal/generative-artificial-intelligence/policy, https://blog.aare.edu.au/does-the-new-ai-framework-serve-schools-or-edtech/, https://leonfurze.com/2024/03/06/video-understanding-the-australian-framework-for-genai-in-schools/, https://www.australiancurriculum.edu.au/curriculum-information/understand-this-curriculum-connection/artificial-intelligence, https://www.aacrao.org/edge/emergent-news/artificial-intelligence-such-as-chatgpt-to-be-allowed-in-australian-schools-from-2024/, https://link.springer.com/article/10.1007/s13384-025-00801-z, https://isa.edu.au/wp-content/uploads/2026/02/Independent-Insights-Feb-2026_DIGITAL_FINAL.pdf
