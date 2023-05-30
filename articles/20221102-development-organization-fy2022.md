---
title: "Offers 開発組織の体制変更と近況 - 強靱なチームと筋肉質な組織 | Offers Tech Blog"
emoji: "💪"
type: "idea" # tech: 技術記事 / idea: アイデア
topics: ["開発", "組織" , "マネジメント" , "ポエム"]
publication_name: "overflow_offers"
published: true
published_at: 2022-11-02 09:00
---

[Offers](https://offers.jp/) を運営している株式会社 [overflow](https://overflow.co.jp/) の [あほむ](https://twitter.com/ahomu) でございます。今回も [Web の仕様を眺めるシリーズ](https://zenn.dev/topics/web%E4%BB%95%E6%A7%98%E7%9C%BA%E3%82%81%F0%9F%91%80) をお休みしてお送りしております。

# 開発組織の体制変更によって実現したいこと

今回は弊社内において Offers 事業を中心とした全体的な体制変更があったので、関連して開発組織の近況をポエム綴ります。ポエム続きで申し訳ない...。

## 実感できる変化を起こすこと

大上段の目的を伝えるのはもちろんとして組織的に「あ、潮目が変わったな」と中の人たちが実感を得られることが重要です。組織自体が変化する/したことを認識することは、「自分に求められている変化はなんだろう？」と個々人に健全な緊張感をもたらし全体に変化を行き渡らせることに繋がります。[^1]

[Dynamic Capability](https://www.docusign.jp/blog/what-is-dynamic-capability) という経営論にも通じる部分があり、変化を察知して、自分たちのリソースを再整理し、実際に自らを変革する動きはスタートアップだからこそ重要な組織アクションです。

[^1]: 個人的な評価観点においてもスタートアップだからということはなく、自ずから変化を生み出したり、他の人の行動に変化を与えられる能力や振る舞いを常々重要視しているフシがあります

## 注力すべきに注力すること

そもそもの発端として新規事業の経営的な開発優先度の変更がありました。今年の前期、新規事業のプロダクトが紆余曲折ありつつちょうど立ち上がったところでしたが、改めて 10 月から始まる下期に向けて事業戦略を練る中で重要度がアップデートされました。

よって単純明快、注力事業には当社の最大戦力を少数精鋭で突っ込むのがベストという判断をしています。最も象徴的なのは**長年 Offers に携わってきた CTO の異動** です。[^2]

[^2]: Offers 事業〜プロダクトの一線から引きつつも技術監修や基盤構築的なところでは HR のデジタル化を念頭に関わり続けています。誤解なきよう！

## チャレンジや成長の機会をつくること

注力とはいえその体制は本当に成り立つのか。CTO 当人とも慎重に議論を重ねましたが Offers から CTO がスッパリ抜けることで長年 CTO が担っていた開発責任が他のメンバーに委譲されてチャレンジの機会が生まれました。

CTO の抜けた Offers の穴を埋めるべく新規事業のリーダーを逆に引き戻すなどもありましたが結果、大小さまざま CTO に依存していた Offers チームの再組織化が促されることになり、個々の成長にもプラスになるであろう手応えをすでに感じています。

# 新旧開発体制

基本的な構造はあまり変わりが無いので参考までにですが Before/After の図を掲載します。

# Before

今年の 4-5 月ごろの様子を思い出して図に起こすとこのような体制でした。実際の呼称ではありませんが、チームトポロジー風味に述べると Offers と新規事業で Stream-aligned チームが 2 つと、Platform と Enabling のあわさったチームが 1 つでした。

![2022年4-5月ごろ当時の組織図](/images/20221102-development-organization-fy2022/figure-before-org.png)

白丸は業務委託、弊社風にいうと Flexible の皆さんですが人数は当時をあまり正確に表現しきれていないです。（ごめんなさい！）

# After

このたび下記のような体制に変更されました。フルタイムメンバーの入社も今後控えており、来年の前半にかけて一定の規模拡大が予定されています。

- Offers を率いていた CTO が新規事業の開発リード兼テックリードへ
- 新規事業を託されていたエンジニアが CTO と入れ替わりで Offers 全体のテックリードへ
- 候補者向けの機能開発をしていた中心メンバーが候補者向けの開発リードへ
- 前職で CTO も務めておられた強者（ニューカマー）がクライアント向けの開発リードへ

![2022年10月当時の組織図](/images/20221102-development-organization-fy2022/figure-after-org.png)

新規事業に CPO（Product Owner）、CTO、デザイナーのボスという当時の Offers 立ち上げに携わった面々が再集結しています。

コミュニケーションデザイン領域（厳密には開発と異なるため開発組織からは将来的に出る予定）や DesignOps を担うデザイナーの横軸組織も新設されています。ちなみにデザイナーポジションも絶賛採用中なのでよろしくお願いします!!

# 拡大するタイミングだからこそ開発組織の強靭化

今回チームビルディングをやり直すくらいのつもりで気を引き締めるべき体制変更をしたことから **「開発組織の強靭化」** をキーワードになんとも脳筋な方針を打ち出しました。

## 栄養、刺激、休息

強靱なチームを育て、筋肉質な組織を実現するためには次の図に示す栄養・刺激・休息が必要であるとしました。具体的な How はトライ＆エラーを前提として開発リード中心に委ねています。（丸投げと言われかねない!!）

![栄養「チーム規模から組織規模へ」増員はプロテインを摂っただけ、筋肉質に仕上げる必要がある。刺激「個人､チーム､組織の成長に執着する」イチから少数精鋭の筋肉質なチームを作るつもりで手を尽くす。休息「我々も”しあわせな時間”を増やす」時間に限りがあるのは全員同じ、メリハリつけてしっかり休む。](/images/20221102-development-organization-fy2022/kinniku.png)

## 既存社員の成長、挑戦の応援

今後、スタートアップ企業として成長すればするほど採用競争力も上がります。そうすると新しいメンバーの経験や実力のゆるやかなインフレが予想されます。このインフレは旧来メンバーの影響力を希薄化させる要因になりますし、組織上のハレーションが起きる可能性もあります。

そのような中で以前からコミットしているメンバーが長く活躍し続けるためには、シンプルに人材の成長機会の創出と支援が不可欠です。事業成長と人材の成長が相関する組織であればこそ、新旧メンバーが共に伸び伸びと活躍できる土壌であると言えるでしょう。

今回の体制変更でそれぞれ新しい役割を担うことになったメンバーの成長にとても期待しています。また弊社において [テックリードや開発リードといった立場は、職位ではなく付け替え可能な役割](https://zenn.dev/offers/articles/20220415-leader-and-manager-roles-in-overflow) としているので、リード経験者が新しいリード挑戦者（キャリアチャレンジ）を明るく支えていけるような世界観にしていきたく考えています。

## 開発メンバーの直接目標にプロダクト KPI

プロダクト KPI … Weekly Active User がどうとかですね。開発メンバーの実態が社内受託的な形態になってしまっていると達成しても未達でも効力感がありませんし、特に未達のときは企画サイドへの他責になってしまいがちです。実体験としても功罪あるので迷いつつも今期は目標設定（期末時点での評価）に一定の割合で組み込みました。

我々開発組織はプロダクト開発を通して事業/サービスが志す提供価値の伝達量を最大化するアウトプットによって働きが示され、アウトカムには結果も求められます。
経営的にも全社的なプロダクトカルチャーとプロダクト開発力を自社の強みにすると定義していることも踏まえ、プロダクトと一蓮托生となって自分ごととして企画に参加し、自ら効力感を勝ち得ることを求めることにしました。[^3]

[^3]: ちなみに横軸組織は現状だと目標設定対象の社員がいないのですが、プロダクト KPI とは別の目標を立てる予定です

# まとめ

前述した Dynamic Capability も、いわゆる自律分散組織も、オーナーシップをもって自らの危機意識によって組織に変化をもたらす構成員が重要です[^4]。それを包括するカタチとして「全員が組織開発に参加している状態 = [インクルーシブな組織開発](https://offers.jp/media/hr/a_1964)」を理想としています。

今期はプロダクト開発とチームの地力の強化に専念しますが、来期以降はただの雰囲気作りに留まらず誰もが組織開発に参加できる仕組みづくりにも着手したい所存です。おしまい。

[^4]: 方法論として十分条件に過ぎないアグレッシブな取り組みを必要条件としてしまい、組織設計や要求を窮屈にしてしまっている事例もしばしば見かけるので慎重に見ている所もありつつです

## 副業であらゆる経験、キャリア、環境にリーチできるサービス

Offers をよろしくお願いします！（突然の宣伝オチ）

https://offers.jp/lp

# 関連記事

ahomu の本業は Web フロントエンド屋さんです。

https://zenn.dev/offers/articles/20221017-definition-of-frontend
https://zenn.dev/offers/articles/20220711-develop-issues-part2
