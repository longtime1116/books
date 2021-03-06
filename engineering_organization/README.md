『エンジニアリング組織論への招待』を読んだ

* かなりの良書だった。
* エンジニア組織の改善に必要なことは、組織全体のコミュニケーションの改善である。
* 情報の非対称性は不確実性や限定合理性を生む。エンジニアリングとは不確実性の削減そのものであり、情報を生み出すことでもある。
* 不確実性には以下のような性質のものがある。
  * 環境不確実性
    * 目的不確実性(なぜやるのか)
    * 方法不確実性(どうやるのか)
  * 通信不確実性
* 不確実性の削減のために、以下のように視座毎に意識すべき点が存在する
  * 個人として注意すべき点
    * 仕事と学力テストは異なる。自ら情報を生み出していく姿勢が重要
    * 論理的に考えようとしても認知は歪むものである。自分がどのようなときに認知を正しくできなくなるのか(非論理的になるのか)知っておく必要がある。
    * 理性主義と経験主義
      * フランシス・ベーコン以前の理性主義は、新しい知識は人間の「理性」のなかに存在するという考えで、演繹的に解を導く。
      * 経験主義は、実験や行動でしか「知識」は得られないという姿勢である。
      * ウォーターフォールをはじめとする設計主義的プロセスは理性主義的であり、スクラムのようなソフトウェア開発手法は経験主義的である。
      * 最初の時点ですべてわかっていることなど稀である。問題を解決するのに十分な情報が揃っていることなど稀だからである。
      * なので、大きな意思決定を行う前に仮説を立て、それを検証しつつ少しずつ前に勧めていく方がリスクも少なく着実に不確実性を減らしていくことができる。
    * 全体論とシステム思考
      * 西洋の自然科学の発展は、「要素還元主義」的な思考をもとに進められてきた。
      * これは全体を細かい要素に分割して、それぞれの性質を把握すれば、その総和として全体を把握できるという考え方。(ex. ロジックツリー)
      * しかし、実際はそんなこともない。要素と要素が影響を与え合うので、部分だけしか見ないと局所最適があちこちで発生してしまう。
      * 視座を高く持ち、全体を俯瞰し、全体最適を意識する必要がある。
  * メンバーと接するリーダーとして注意すべき点
    * メンタリングのテクニックにより、メンバーの意識を本人の意志で変えていくことが重要である。
  * チームを回すリーダーとして注意すべき点
    * アジャイルなチームを作ることができれば、チームで不確実性に立ち向かうことができる
    * スクラム開発はアジャイルなチームでアジャイルに開発を進めるためのひとつの方法である。
    * 自己組織化されたチームは自分たち自身の手によって広い視野で問題解決を進めることができるようになるので、強い。
  * エンジニアリング組織全体をみるマネージャとして注意すべき点
    * コミュニケーションコストは、人数が増えると増える。
    * コミュニケーションとは通信不確実性を減らす試みなので、当然まずい。
    * コンウェイの法則の通り、システムを設計する組織は、その構造をそっくり真似た構造の設計を生み出してしまう。
    * なので、ビジネスモデルと組織構造とアーキテクチャは同じ方向を向いている方向がある。
    * 組織構造/アーキテクチャのどちらかだけを変えても、無理が生じてしまう。
      * マイクロサービスアーキテクチャの導入タイミングは適切な時期に行うべきである。
      * 仮に導入が遅れてしまったら少しずつ API として切り出していくという方法がある。
    * 権限委譲にはレベルがあるので、認識を合わせた上で委譲すべきである。
    * 技術的負債とは経営者とエンジニアチームの認識の差を表している、と捉えるアプローチが適切。
    * 経営者は知っているがエンジニアは知らないこと、すなわち将来要件の不確実性と、エンジニアは知っているが経営者は知らないこと、すなわちアーキテクチャの複雑性の２つの情報非対称性を解消する必要がある。
