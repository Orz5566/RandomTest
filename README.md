# RandomTest

https://osdn.net/projects/dtxmaniaxg-verk/scm/svn/commits/571
に基づき、昔書いたドコドコ仕様、ミラー、ランダムオプション辺りのコードを一通り整理＆書き直したやつの置き場です。
アルゴリズムの僅かな改良によってコードを短縮し、ドラムのランダムも全押し譜面に対応出来ました。
ついでにグループ分けランダムのオプション項目の追加とShowLagTimeの位置調整もしました。

DTXManiaXG(ver.K) rev571から変更したファイルは下記の通り：

**・ドコドコ仕様、ミラー、ランダムオプション関連**
```bash
DTXManiaプロジェクト/コード/スコア、曲/CDTX.cs
DTXManiaプロジェクト/コード/ステージ/06.曲読み込み/CStage曲読み込み.cs
```
**・グループ分けランダムのトグル関連**
```bash
DTXManiaプロジェクト/コード/全体/CConfigIni.cs
DTXManiaプロジェクト/コード/スコア、曲/CDTX.cs
DTXManiaプロジェクト/コード/ステージ/04.コンフィグ/CActConfigList.cs
```
**・ShowLagTimeの仕様、位置調整**
```bash
DTXManiaプロジェクト/コード/ステージ/07.演奏/ギター画面/CAct演奏Guitar判定文字列.cs
DTXManiaプロジェクト/コード/ステージ/07.演奏/ドラム画面/CAct演奏Drums判定文字列.cs
実行時フォルダ/System/Graphics/7_lag numbers.png
```
