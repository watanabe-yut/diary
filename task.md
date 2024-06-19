### 短期的タスク
- 山下さんのマルチモーダル議論叩き台を見る
- 宮前さんのFDNSの資料見る
- pj会の前のディスカッションのための資料を用意する（~〆切：6/21（金）のPJ会の直前~　**6/19(水)までにはgitにアップした方がよいか**）
  - 入出力もマルチモーダルなクレーム抽出に着目して調査＆論文調査する
  - 調査対象を広げる（陽にclaim extractionといっていなくても、貢献できそうなやつとか）
- Interopの参加報告（**〆切：6/21（金）のPJ会**）
  - 展示員の方とどういう会話をしたか、どういう展示があったか
  - パワポ2~3枚ぐらいでまとめて、PJ会で報告する
  - そのために、誰と会ってどんな会話をしたか、誰と名刺交換したか、どんな展示を見たかなどをメモっておく
  - 黒坂さんの講演内容をサマライズして報告
- 育成計画書の作成（**レビュー会6/24(月)**、**1st draftの〆切：6月最終週**）
  - 角田さんも交えてみてもらう（**〆切：6月の最終週と7月の第一週**）
  - 雑談会で見てもらうのもありかも
- [eL]仕事と介護の両立のために
- kakeaiで今井さんとの1on1予約


### 長期的タスク
- issue#548（**新人研修関連のタスク**）
  - 6月度育成計画書提出（7/5(金)）
    - 定期的に評価項目を見る
  - e-learning受講（目安は2024上期までに受講完了）
- issue#544（**機械学習の基礎の習得**）
  - 機械学習とPythonの習得
  - 進捗の報告&質問は適宜issueに投げる
  - 大木さんに教えていただいたNetCampussやUdemyも
  - 勉強の指針としては、ML→LLMとニューラルネットワーク（とくにGNN）
- issue#527（**マルチモーダルなクレーム抽出の検討**）
  - [サーベイ論文](https://arxiv.org/abs/2305.13507)でreferされているマルチモーダルクレーム抽出の4つの手法の調査
  - factoolのソースを読んでテキストからのクレーム抽出部を理解（ソースコードの該当箇所も探す）
    - ソースコードが読めたらドキュメント作成してみるとか
    - 時間があればクレーム抽出以外の箇所も読む。mtgで話されていることに追いつけるかも
  - 山本さんのアドバイス（TI分析定例5/16）にしたがって、過去の偽情報の事例から、手作業でやってみるクレーム抽出とLLMのクレーム抽出を比較してみる
- 技術勉強会
  - 現在のテーマはプロンプトエンジニアリング
    - 教科書：[大規模言語モデルを使いこなすためのプロンプトエンジニアリングの教科書](https://www.amazon.co.jp/gp/product/B0CV46J8V4/ref=ppx_yo_dt_b_d_asin_title_351_o00?ie=UTF8&psc=1)
  - 次回のテーマはRAG or GNN
    - RAGの教科書の候補：[LLMのファインチューニングとRAG](https://www.ohmsha.co.jp/book/9784274231957/)
    - GNNの教科書の候補：[グラフニューラルネットワーク (機械学習プロフェッショナルシリーズ) ](https://www.amazon.co.jp/%E3%82%B0%E3%83%A9%E3%83%95%E3%83%8B%E3%83%A5%E3%83%BC%E3%83%A9%E3%83%AB%E3%83%8D%E3%83%83%E3%83%88%E3%83%AF%E3%83%BC%E3%82%AF-%E6%A9%9F%E6%A2%B0%E5%AD%A6%E7%BF%92%E3%83%97%E3%83%AD%E3%83%95%E3%82%A7%E3%83%83%E3%82%B7%E3%83%A7%E3%83%8A%E3%83%AB%E3%82%B7%E3%83%AA%E3%83%BC%E3%82%BA-%E4%BD%90%E8%97%A4-%E7%AB%9C%E9%A6%AC/dp/4065347823)、[スペクトルグラフ理論: 線形代数からの理解を目指して](https://www.amazon.co.jp/%E3%82%B9%E3%83%9A%E3%82%AF%E3%83%88%E3%83%AB%E3%82%B0%E3%83%A9%E3%83%95%E7%90%86%E8%AB%96-%E7%B7%9A%E5%BD%A2%E4%BB%A3%E6%95%B0%E3%81%8B%E3%82%89%E3%81%AE%E7%90%86%E8%A7%A3%E3%82%92%E7%9B%AE%E6%8C%87%E3%81%97%E3%81%A6-SGC%E3%83%A9%E3%82%A4%E3%83%96%E3%83%A9%E3%83%AA-%E5%90%89%E7%94%B0-%E6%82%A0%E4%B8%80/dp/4781916015/ref=pd_vtp_h_pd_vtp_h_d_sccl_2/356-1726938-3151046?pd_rd_w=tzVMw&content-id=amzn1.sym.a075abab-259f-40c3-bc0f-76d5f3149ef5&pf_rd_p=a075abab-259f-40c3-bc0f-76d5f3149ef5&pf_rd_r=F0QAZKCZK2Z7J23B0VH1&pd_rd_wg=4xCa5&pd_rd_r=1ca2874d-24dc-4e1d-85ab-4ac412b4171a&pd_rd_i=4781916015&psc=1)、[線形代数で考える スペクトラル・グラフ理論入門](https://www.amazon.co.jp/%E7%B7%9A%E5%BD%A2%E4%BB%A3%E6%95%B0%E3%81%A7%E8%80%83%E3%81%88%E3%82%8B-%E3%82%B9%E3%83%9A%E3%82%AF%E3%83%88%E3%83%A9%E3%83%AB%E3%83%BB%E3%82%B0%E3%83%A9%E3%83%95%E7%90%86%E8%AB%96%E5%85%A5%E9%96%80-%E3%83%9C%E3%82%B0%E3%83%80%E3%83%B3%E3%83%BB%E3%83%8B%E3%82%AB/dp/4535790043)
  - 現在のローテは佐久間 -> 中村（元）-> 設楽 -> 藤本（馨）-> 宮前 -> 坂本（匠）-> 渡邉 -> 奥村

### その他
  - 量子暗号解析セミナーの勉強
  - 格子暗号勉強会の勉強
  - ヘッドセット、ディスプレイなど買いたい（角田さん）
  - 手のひら静脈の登録


### 時間があるときに見ておくべきドキュメント類
- MMCE周辺
  - 宮前さんのサーベイ
  - FDNSの勉強会資料
  - 山下さんのたたき台
- コンサル研修のスライドライティング
- [技術棚卸し](https://fujitsu.sharepoint.com/sites/jp-SecurityLaboratory/SC/Forms/AllItems.aspx?OR=Teams%2DHL&CT=1715568018742&clickparams=eyJBcHBOYW1lIjoiVGVhbXMtRGVza3RvcCIsIkFwcFZlcnNpb24iOiI0OS8yNDAzMzEwMTgxNyIsIkhhc0ZlZGVyYXRlZFVzZXIiOmZhbHNlfQ%3D%3D&id=%2Fsites%2Fjp%2DSecurityLaboratory%2FSC%2F%E7%A0%94%E7%A9%B6%E5%93%A1%2FCommon%2F2024%E5%B9%B4%E5%BA%A6%2F%E6%8A%80%E8%A1%93%E6%A3%9A%E5%8D%B8%E3%81%97&viewid=45e20bc0%2D041a%2D43dd%2Da3ca%2D037439d3db4b)
- [鈴木さんのTI全体アーキ資料](https://fujitsu.sharepoint.com/sites/jp-SecurityLaboratory/SC/Forms/AllItems.aspx?OR=Teams%2DHL&CT=1715568018742&clickparams=eyJBcHBOYW1lIjoiVGVhbXMtRGVza3RvcCIsIkFwcFZlcnNpb24iOiI0OS8yNDAzMzEwMTgxNyIsIkhhc0ZlZGVyYXRlZFVzZXIiOmZhbHNlfQ%3D%3D&id=%2Fsites%2Fjp%2DSecurityLaboratory%2FSC%2F%E7%A0%94%E7%A9%B6%E5%93%A1%2FSocialTrustCPJ%2FGr%5FTrustableInternet%2F%E3%82%A2%E3%83%BC%E3%82%ADG%2F%E5%85%A8%E4%BD%93%E3%82%A2%E3%83%BC%E3%82%AD&viewid=45e20bc0%2D041a%2D43dd%2Da3ca%2D037439d3db4b)
- [20240418山下さんのGitHubレクチャー会](https://fujitsu.sharepoint.com/:p:/r/sites/jp-SecurityLaboratory/_layouts/15/Doc.aspx?sourcedoc=%7B2D9620C1-2D15-4505-BF6B-AF65DE40A231%7D&file=20240418_GitHub%25u30ec%25u30af%25u30c1%25u30e3%25u30fc%25u4f1a.pptx&action=edit&mobileredirect=true)

### Tips
