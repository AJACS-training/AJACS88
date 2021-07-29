# 講習会中に受講者からいただいた質問および講師による回答

### Q.
Biosample、BioprojectでつけられたIDを元にそれに関連したデータの検索をGEOやバリアントについてをそれぞれのデータベースでできるのでしょうか？
### A. 
NCBI BioProject でアクセッション番号で検索した結果画面の Project Data: または右側の Related Information に 関連した GEO DataSets や dbSNP, dbVar へのデータへのリンクがつけられます。

NCBI BioSample においても同様に、検索した結果画面の下部（Slide 17枚目、BioSample の説明で関連データの箇所）、または右側の Related Information に関連した GEO DataSets や dbSNP, dbVar へのデータへのリンクがつけられます。

----

### Q.
NGSデータ中で、アセンブル済みデータにアクセスしたい場合、どこを見ればデータにたどり着けるか、鍵になる単語があれば教えて頂きたいです。
（通常の塩基配列データなら、どこを押せばデータにたどり着くか大体わかるのですが、NGSデータではその直感が発揮できるほど理解できていません・・・）
### A.
特定のBioProject番号が分かっている、または絞り込めている場合は、NCBI BioProject の結果のサイトのProject Data:からNucleotide または Assembly でアセンブル配列へのリンクが表示されます。

また、NCBI BioProject で("bioproject sra"[Filter]) AND "bioproject assembly"[Filter] で検索すると SRA とアセンブル配列が同時に登録されている BioProject を絞り込むことができます。
