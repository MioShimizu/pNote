## ビジネス設計にITの手法を活かす〜顧客中心設計〜

### IT化の巧拙 　

IT、またはICTは、Information (and Communications) Technologyの略だがそのままで日本語になっている。ICTという言い回しは官庁や自治体などでよく耳にするが、やや正規な表現を主張しているかに聞こえないこともない。霞ヶ関や海外では"IT"では通じないよ、などと言う人もいる。いずれにしても意味に大差はなく本稿では”IT”という個人的に耳慣れした単語を使うことにする。  

ITの（またはICTの）活用とかIT化とかいうと、その事例本や解説本の多くは「情報システム」の専門用語の説明から入る場合が多いように思う。"システム"とは何か、いかなる”アーキテクチャ”か、どんな”テクノロジ”で構成されているか、など、システムデザイナーやシステムエンジニアのマスターベーションに聞こえる。ITの利用者（ユーザ）にとってはそんなことより、どんな"効能"があるのか、”使い勝手”や”安全性”はどうなのか知りたいのに、ITの専門家（IT屋）は「それを示すのは難しいですね」と片ずけてしまう。これは多くの情報システムが、複雑で専門的で一般人に説明困難で、さらに成果にかかる条件が多岐で、その上ユーザの使用感や効能を把握する仕組み自体を欠いているからである。IT業界では未だに多くのシステム開発が（例えば一連のコロナ対策システムなど）、成果主義ではなく工数精算方式で報酬が決まるからだ。採用された新技術や開発の生産性などシステム開発内部の仕組みにフォーカスし、ユーザのフィーリングや業務改善に直接着目しない体質みたいなものがIT屋に染み付いているように思える。ITの利用者（ユーザ）はそれに乗ってはいけない。アプリケーションソフトの開発設計や複雑怪奇なITプロダクトの購入検討の前に、行うべきことがある。大切なのは"ビジネスモデル"であり、”データ”であり、顧客の”フィーリング”なのだ。  

実は最新のシステム設計に関する工学研究に則れば、設計の最上流でこのようなビジネスの仕組みや顧客接点やマーケティングを検討する手法がちゃんと用意されている。にも関わらず国産のITベンダーでは殆ど馴染みがない。というのはシステム開発の上流はコンサルタントの領域で専門人材も少なく、下流のシステム開発の方がビジネスボリュームがあるからである。そうとは知らずこの工程を無視すると、実はとんでもないことに陥りやすいにも関わらず、ユーザのIT専門部門や似非プロフェッショナル達はこの上流工程を端折ったりITに疎いシステムの最終利用者（ビジネス部門）に放任したりしている。  

本来、新しいビジネスモデルをどう考案し、デジタル化されたデータをどう活用し、ビジネス/サービスの目的（自動化や顧客満足向上など）をどこまで達成するか、がシステム化の勝負の決め手なのに、ユーザがIT屋の甘言に翻弄されてこれらを見失うと、単にコードを入れただけの精度と効率のない”入れポン”システム（どこかの接種券予約システムみたいな）が出来てしまう。多くの場合、その下流作業を担う現場では、結局紙と手作業という非効率に陥ってしまう。現場にまともなバーコードリーダーもないのに、いたずらに今回限りの新コード(!)を採番し、現場受付では利用もせず、実績登録も手打ちに陥って何千万という非効率を作り出してしまう。  

そんなことにならないようにユーザは、まず自らのビジネス/サービスの本質的な問題点や改革点を探し出してシステム化の目標に据えて、その成果を測定できるデータを見つける努力をしなければならない。既存業務プロセスで非効率で無意味な作業は何か、業務の中心にあるデータは何か、顧客に価値あるデータが発見されたり、創造できるチャンスがないか、を精査しなければならない。そしてIT活用を考える前に、ビジネスプロセスがどうあるべきか（あるべき姿）を熟考、自問、再再検討するのだ。最新の(IT)工学ではこの考え方に基づく最上流設計手法を、「顧客中心設計」と呼んでいる。伝統的にマーケティング力のある企業では、新製品/サービスを開発する際にこの設計工程を必ず実施している。この場合、システム化の対象や目的はその過程で出てくる部分的なツールでしかない。テクノロジ崇拝の技術屋ばっかりのITベンダーにはこのノウハウはない。業務と顧客を理解しているユーザやマーケッターが製品/サービス戦略やIT活用を考える時、顧客中心のデータ中心のこのアプローチが有効だと思う。  

### 顧客中心設計とは  

この設計手法はお気付きの通り、IT化やシステム化以外の目的、例えばビジネスプロセスの開発や改善、業務プロセスの設計や改善、顧客とのリレーションやマーケティング戦略の検討に使うことも出来る。事実、製品設計やシステム設計の上流として考案されたこの手法が、今日では多くのマーケティングコンサルに利用されている。筆者もクラウドサービスの上流設計で、多くのIT屋が機能/非機能設計から入るのに対して反論してくれた工学系の大学教授らに紹介を受けた。モノ造り日本が躓きを見せた時、品質と機能設計ばかり追い続けていた工学系の学者連中がたどり着いた生き残りのための変換点だったようだ。過剰品質の日の丸製造業が、モノからコト造り（顧客の経験価値にまずフォーカスする）にシフトした欧米企業に勝てなくなった反省の産物とも言えないこともない。  

顧客中心設計で最もフォーカスするのは、顧客の体験である。英語で Customer (/User) Experienceという(CXとかUXとか略す)。顧客がどの様な行動をしどう感じ何を体験したのか、そしてそこにどの様な価値が創出出来るか考える姿勢を、顧客経験価値志向などと言う。自社の製品・サービスを発想の中心に置きがちなシーズ思考と明確に決別して、徹底して取引前から取引終了までの全ての時間での顧客の行動と感情に集中する。そして、その顧客の行動と感情のいちいちと、サービスの提供者との接触、コミュニケーション、関係性を時系列で詳（つまび）らかにすることで、サービスの全体像と問題点を描ききる。いわば（製品）サービスに関わる顧客の全旅程の見える化である。この作業は通常サービスを設計するチームが専門家（マーケティングコンサルタント）の支援を得て、製品・サービス設計の上流で実施するが、ここではより実践的で簡易なやり方を紹介しよう。  

#### 顧客をプロファイリングする

まず顧客のプロファイリングから始める。あらゆるマーケティングやセールスの教科書やガイドやコンサルがすべからくこれを出発点としている。できれば先入観を捨てて、顧客（マーケット）を大きく捉え、その属性（年齢、性別、住所など）、その特性（所得、心理、他社顧客/自社顧客、行動など）で分類して、これから検討するターゲットの位置づけを見定める（セグメント化という）。  

##### 顧客リサーチとペルソナ策定

これには調査（リサーチ）が必要かもしれない。地理的な平均年収や持家比率の分布、家族構成や所得調査（国勢調査？）、民間や銀行の顧客意識調査など、入手可能な外部情報もあるだろう。そこでは、横浜市在住より鎌倉市在住の方が、年齢層も高く財産持ちという傾向が発見できるかもしれない。地方より周辺都市部の方が顧客の流出入とディベロッパーが纏めている不動産の新規購入客の集団が多いかもしれない。選別と特定ができても、オケラみたいなピーピーの顧客層もいるかもしれない。反対に金払いの良い集合が存在するかもしれない。ここの選択で後の結果が相当変わる。目の付け所がよければ後の打率が良いし、外れればペンペン草だ。  

そして、目を付けたセグメントにコンタクト手段はあるのか、儲かる相手なのか、競合や既存ベンダーが囲い込んでいないかなど、選別・特定できたセグメント（顧客層）のスクリーニング（精査と評価）も重要だ。対象の製品・サービスごとに、選別・特定できる顧客層はおそらく異なるだろう。複数のセグメンテーションができるかもしれない。そうそうサプライズはないが、何か時代の趨勢や最近のトレンドが発見できれば、近い将来の有力マーケットにフォーカスできるかもしれない。  

顧客のセグメントがおおよそ固まった段階で、あらためてそのセグメントに典型的な個人の属性と特性を書き出しておく。どういう人物（属性）なのか、どんな嗜好や特徴や傾向があるのか、どこで接触できるのか整理する。これを”ペルソナ策定”などと顧客中心設計では呼んでいる。  

##### 登場人物の特定

ペルソナ策定が出来たらここで、顧客の周辺関係を洗っておこう。顧客本人を取り巻く社会的関係の概略を押さえていくのだ。不動産業や信託銀行とコネがあるのか、地域のケアマネや福祉施設と関係があるのか、保有会社の税理士や社労士など士業との関係を持っているのか、特定したペルソナに固有の傾向が発見できればその”筋”が活用できるかもしれない。傾向がなくても、その前提を置くことでリーチ可能になるかもしれない。そしてあなた（サービス提供者）との距離やさらに業務で関わりのある関係団体（裁判所、登記所、福祉課など）も整理しマップできれば、顧客の社会関係（人脈）と、サービス提供者への接触ルートや業務での登場人物（団体）が整理できるだろう。これらの登場人物（顧客の関係者と業務の関係者）は、次のカスタマージャーニマップ作成の縦軸になっていく。  

##### 参考　顧客周辺にいる事業者・団体と業務関係者（想定例）　　

士業(弁護士、社労士、税理士、行政書士)、銀行、不動産業、ケアマネ、保健所、病院・療養施設、老人ホーム、ディベロッパー、ホームビルダー(設計工務店)、裁判所、警察、自治会（福祉課）、老人会、商工会議所、ライオンズクラブ、中小企業庁  

#### カスタマージャーニーマップを描く

次の作業は表（マトリックス/マップ）での整理になる。表の横軸はセールスからサービス提供とフォローアップまでの時間軸（ステップ/フェーズ）、縦軸は登場人物とその行動と感情になる。※以下例を図示するが著作権を無視した無許可転載なので、見たら削除するので連絡してください。  

![CustomerJourneyMap_DL_rev1](CustomerJourneyMap_DL_rev1.jpeg)

マップの横軸は顧客が、①見込み客（認知・注意・興味）から②有力プロスペクト（紹介・説明・説得）を経て、③サービス受益者（契約・サービス提供）になり、④アフターサービス（フォローアップ・保守）に至る工程（ステップ/フェーズ）を示している（サービスライフサイクルと言う）。 　

縦軸はまず①顧客のペルソナ（上記例にはない）、②行動、③感情（ポジティブ、ネガティブ）のセットがあり（タッチポイントは通常次に出て来る）、次に④顧客の有力な関係者群（士業・銀行・不動産など）の顧客との接触方法（タッチポイント：広告宣伝、Web、電話、説明会、往訪、ファックスなど）、⑤対応した行動（査定見積、裁判所に出頭など）、⑥その行動時の感情（喜び、怒り、苛立ちなど）のセットがあり、次に⑦あなた（サービス提供者）の顧客との接触手段（タッチポイント：同席、個別訪問、メール、郵送など）と、⑧とるべき行動（士業に同行/代行、サービス紹介、見積、資料収集など）とそれに関わる業務関係者群（裁判所、登記所など）への連絡手段（電子申請、郵送、出頭など）を、それぞれ書く行を設ける（例には顧客のセットしかないが実用的でない）。  

この縦横の表（カスタマージャーニーマップ）では、各欄を利用し”まず現状”を整理する（あるべき姿ではない）。接触方法が現状ファックスであったらファックスと書く。ファックスのない顧客があれば郵送も追記する。ある程度想像や思い込みでもラフに整理し精度（正確性）は問わないのがコツだ。例えばペルソナ策定が「年少の子供を持って人生で最初に山手のマンションを購入する30代の世帯主」だった場合、マップのスタートをマンション選定段階にしても良いし購入契約時のローン検討段階にしても良い。あなた（サービス提供者）の提供業務をイメージして決めればよい。サービス提供者が顧客と直接の接触が困難な場合、関係者（ディベロッパーか銀行か）のタッチポイントの利用可否が検討できるように、あなたより顧客に距離の近い関係者の接触方法を研究し記入する。そして関係者がその行動（説明会とか）で遭遇する感情（基本的な質疑や書類不備の顧客が多く面倒だ、など）の改善や強化に関われるか後から考えられるように、該当欄（⑥関係者の感情）に彼らの怒るべき感情をメモして行く。  

もちろんフェーズ毎に顧客と関係者の④タッチポイントと⑤行動は変化するだろう。それに対してサービス提供者の⑦接触手段と⑧行動も変化するだろう。顧客の行動（ジャーニー）に注目し、それぞれの時点での満足と不満足、サプライズやデライト、怒りや苛立ちを測定（類推）できれば、顧客への接触方法の改善やシステム化、情報提供や利便性の提供（待ち時間のお知らせや短縮など）のアイディアでアドバンテージが取れるだろう。同様に関係者の感情が把握できれば、サービス提案や業務代行の切り口が整理できるだろう。さらにバックヤードとしての⑧業務関係者への接触手段に非効率があれば、それ自身システム化のターゲットになるかもしれない（自動化とか）。カスタマージャーニーマップの最後の1行前には、これらの改善ポイント（例では「ビジネス課題」になっている）をフェーズ毎に思いつくままプロットしていく（⑨ビジネス課題）。　　

カスタマージャーニーマップを作成する目的は、一義的には正にそれら（日常コミュニケーションや業務改善と顧客や関係者への訴求ポイントの発見）にあるが、IT化という観点ではこれらの行動やコミュニケーションの現場で採取できる顧客データの収集（データポイントの発見）という意義もある。AmazonやFaceBookでは、Web上での顧客の振る舞い（参照やページ戻り、躊躇や中断など）をデータポイントとして収集し解析して顧客Web行動を購買や目的の行動まで誘導する手段や適時適切な広告効果の測定を達成している。そこまで詳細で陰湿でなくても、例えばシンガポールのチャンギ空港の税関・入国出口で利用客に5段階のニコちゃんマークのボタンを押させているし、流通や医療関係でも窓口での待ち時間と顧客満足度との関係を測定している。カスタマージャーニーマップの一番下段に、IT化やデジタル化の介入ができるポイントと採取可能なデータ内容を書く行を設け、IT化の重要な目的の１つとして書き出しておく（⑩データポイント）。 　

カスタマージャーニーマップは、通常複数のメンバーでツールや模造紙上にポストイットで各自自由にプロットし都度都度ブレインストーミング風に整理していく。参加者のいない場合は、顧客調査や関係者問診などのテストマーケティングを挟んで、複数回に渡ってチューンしていくしかない。大切なのは正確性より気付きだ。チームでも個人でも否定的な発想（そんなの出来ないとか）は厳禁だ。顧客と関係者の行動・感情の起伏と（コンタクト/データ）ポイントの理解を深めて、サービスの設計/改善に活かすアイディアを発想する機会創出に利用する。  

アイディアの発想法を教える研究も相当数あるがかなり難解だ。”改良”、”排除”、”代替”、”流用”などの概念を新発想のきっかけに利用しながら、寝ても醒めても自問自答するしかない。  

#### ツール化やシステム化を考える

ひとたびカスタマージャーニーマップを描いてみると、顧客の行動も様々なパターンがあることが分かる。後見ないし財産管理を委託したいと考えている顧客は、地域のケアマネに相談するかもしれないし、地元の法律相談会に足を運ぶかもしれない。何を前提にするかでマップ上の顧客の旅程はがらりと変わってしまう。しかしペルソナ策定をしたターゲットにあり得るパターンは、表が横長になろうと描いておこう。同様に顧客（または関係者）のITリテラシーで接触手段は制約を受けるだろう。接触ルートが士業やケアマネ経由であれば、電子メール位は使えるかもしれない。年配層であれば電話や郵便に限定されるかもしれない。現実に近い状況を選定する。   

顧客や関係者の感情（フィーリング）もアンケート調査やヒアリングをしない限り想像になってしまう。ある程度の業務経験があれば、現実の顧客や関係者のクレーム実績に注目すると、強い感情例を見つけることができる。感情の裏には”期待”がある。”期待”を達成/過達できればデライト（強い喜び）が、反すればクレームになる。顧客とのトラブルや強いクレームは容易に認知できるので、そこを推論の出発点にすることが出来る。  

顧客や関係者の感情（フィーリング）を改善するには、感情の背後にある”期待”に気付くことである。彼らにとって何が問題の本質なのか想像して、解決策、軽減策を考える。それらの多くは、コミュニケーション頻度、詳細な情報提供、スピードの改善や優先度アップで軽減される場合が多い。自動応答やプッシュ通知、FAQ提供や進捗連絡など、コンタクトポイントの改善（質と量）を検討して見よう。  

顧客との接触方法や課題の解決方法が発見・発想出来たら、それがシステム化出来ないか考えよう。ITがストレートに利用できればベストであろうが、最低でもプロセス化、パターン化、手法化出来ないか検討し、顧客やその関係者の問題解決（省力化/省人化/効率化/品質向上/スピードアップなど）として理路整然と説明できるようにする。解決方法が明瞭に説明できることで、セールスポイントやサービスの”強み”になる。  

解決方法をセールスポイントとして説明する伝統的な方法に”FAB（Feature、Advantage、Benefit): ファブと発音”という手法がある。セールスポイントを”Feature”（特徴）、"Advantage"（優位点）、"Benefit"（便益）の順に説明する方法だ。例えば顧客を紹介してくれた地域のケアマネに、業務の進捗報告と関連情報提供を週次でフィードバックをするサービスを考えてみる。  

- 特徴(F) ー「弊事務所では週次で進捗状況と次期関連情報を提供している」**ので**、  
- 優位点(A) ー「クライアントの近況や次の課題に関する知識を先取り出来る」**から**、  
- 便益(B) ー「地域の高齢者対応である本来業務に安心して集中することが出来ます」  

といった感じである。当方の優れた機能やプロセスを”特徴(長)”＝差異化ポイントとして説明し(F)、それによる相手（顧客や関係者）における解決・改善点＝可能になることにフォーカスし(A)、最終的な相手のメリット＝利益を明確に示すメッセージング手法だ。世間での優れたプロモーションは、大体この様な構造が意識的に使われている。口頭で自社の優位性を説明する場合や、パンフや資料で説得をかける際の基本として活用願いたい。ちなみに筆者が数十年前に受講した「デールカーネギーセールスコース」では、このFABに手を加えて特徴(F)と優位点(A)を「事実(fact)」に、便益(B)を「利益(benefit)」に整理し、これにもう一つ加え（記憶では、ハンバーガーのバンズ下(事実)とパテ(利益)に、「証拠(evidence)」というバンズ上を加えて）、事実と利益を示した後でそれが真実である証拠を示すという理論（「セールスバーガー」と呼称）になっていた。つまり「**だから**弊事務所は200を超える顧客を持っている」とか「アワードを受賞した」とか具体的他社事例とかの類である。  

この様な訴求ポイントを「⑨ビジネス課題」毎に策定して、共通ツール化（パンフやプレゼン資料など）したりプロセス化（毎週のプッシュ通知をメール化など）したりシステム化（自動での週報生成や通知配信など）を検討したりすることが、カスタマージャーニーマップの最終行近くで議論・考察される重要作業になる。かつて筆者が営業部門のリーダだった頃、FABを駆使した何種類ものセールスツールを開発し（それは一枚もののパンフから、初期訪問時の紹介資料、説得用の事例集やデモソフト、カンニング用のマニュアルから成る）、”お出かけセット”と称して部下に携行させた。セールス実戦の中で、この様な要領を得た資料は顧客の興味や納得を得るための有効な武器だ。視覚と聴覚の両方に訴えることができるからだ。カスタマージャーニーマップのフェーズ毎に、顧客の感情に対応したキラーコンテンツを用意すべきだ。  

さてカスタマージャーニマップの最終行（⑩）は、顧客のデータポイントの発見である。一連の顧客行動やサービス提供者の活動で、競合先では取り得ない、生の顧客データを採取可能なポイントを見付けることだ。業務上知り得る顧客の秘密事項があるかもしれない。あるいは設定したペルソナに追加できるターゲットの選別を容易化する隠れた特徴かもしれない（山手の財産家で後見人を必要とするのは殆ど未亡人であるとか）。これも発見であり見付けられなければ見過ごしてしまうかもしれない。顧客の行動に対する関係者の行動やサービス提供者の行動から漏れ出す様々な情報（データ）を観察して選別し発見しなければならない。デジタル化が進んでいないとなかなか遭遇しないかもしれない。そんな時は積極的に顧客から採取できないか、考えて見よう。そう考えれば、ほとんどのサービス業が敢行しているCSアンケートが、実はデータポイントの典型なのだ。優れたCSアンケートは、サービス提供者の全サービスプロセスに対する顧客の真摯なフィードバックであり、顧客や関係者が紹介者やインフルエンサーになり得る可能性について（つまりそれが究極の顧客の評価であるが）欧米では必ず10段階評価させている例が多い（世界のマーケティング常識と北米で指摘されたことがある）。重要顧客にはインタビューを実施する企業もある。サービス提供者は最低でも、サービスライフサイクルの後半（フォローアップ段階）で、サイクルの全フェーズを網羅するCSアンケートを敢行すべきである。  

### 最後に

ITエンジニアリングで言われる「顧客中心設計」とその簡単な実践を紹介してきたが、あなた（サービス提供者）の実際においてどんな感じであろう。使えそうであろうか。ビジネスを組み立てるには、マーケティングやセールスやシステム化など多岐に渡る知見が必要だ。業界を圧巻する様なメソッドやシステムはそうそう発明されない。しかし多くの場合、基本に忠実にやるべき手を地道に駆使した者が地味に生き残っていることも事実だ。偶然の出会いもあるかもしれない。美味い筋があるかもしれない。それらは基本を実践した地味さの中で出会えるものである。  

### 了
