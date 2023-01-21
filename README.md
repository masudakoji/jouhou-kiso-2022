# jouhou-kiso-2022
Course materials for Fundamentals of Information Technology



## 授業資料

- [【01】Python ・Jupyter Notebook入門](01_Introduction_Python.ipynb)
  - Pythonの簡単な紹介・四則演算の計算方法
  - インデントなどの取り扱いについても言及しています
- [【02】Pythonを使ったデータ解析の概要](02_DataAnalysis_Overview.ipynb)
  - DataFrameや、irisデータセットを用いたデータ解析の例
- [【03】コメント・print文・様々な演算](03_Calculation_Exercise.ipynb)
  - コメント文の書き方
  - print文の書き方
  - 初等関数（log, expなど）の紹介
    - これらは1年後期に習います
  - 四則演算や、剰余などを使った問題演習
    - 8問あります
    - 最後に答え合わせする関数もつけています
- [【04】リスト](04_List_Array.ipynb)
  - リストを使ったプログラミング
  - リストを使った問題演習
    - 8問あります
- [【05】繰り返し処理](05_Control_Flow_ForLoops.ipynb)
  - リストを使った繰り返し計算
  - forを用いた繰り返し計算
  - 繰り返し処理を使った問題演習
    - 7問あります
- [【06】条件分岐](06_Conditional_Statements.ipynb)
  - ifを用いた条件分岐
  - 条件文の書き方、条件文の実体
  - and, or 演算子
  - 様々な条件分岐
    - if - else 文
    - if - elif 文
    - if - elif - else 文
- [【07】条件分岐 問題演習](07_Conditional_Statements_Excercise.ipynb)
  - 条件分岐を使った問題演習
    - 30問あります
- [【08】繰り返し処理 補足](08_Supplemental_ForLoops.ipynb)
  - 繰り返し計算をする際に有用な関数などの紹介
    - range関数
    - enumerateを使ったループ
    - zipを使ったループ
- [【09】whileを使ったループ](09_Control_Flow_WhileLoops.ipynb)
  - whileを使った繰り返し計算
  - continue文, break文
  - whileを使ったループの問題演習
    - 4問あります
- [【10】組み込み関数](10_Built-inFunction.ipynb)
  - Pythonに含まれる組み込み関数の紹介
- [【11】アルゴリズム 線形探索](11_Algorithm_LinearSearch.ipynb)
  - 有名なアルゴリズムの学習
  - 線形探索と呼ばれる探索アルゴリズムの紹介
- [【12】アルゴリズム 二分探索](12_Algorithm_BinarySearch.ipynb)
  - 有名なアルゴリズムの学習
  - 二分探索と呼ばれる探索アルゴリズムの紹介
    - 線形探索よりも効率的なアルゴリズム
- [【13】アルゴリズム 素数判定](13_Algorithm_PrimeNumber-ANSWER.ipynb)
  - 素数を判定するためにはどのようなアルゴリズムがあるのか学習
  - 資料を見ながらプログラムを作成する演習形式です
- [【14】ライブラリ](14_Import_Library.ipynb)
  - 外部ライブラリの読み込み方や、よく使うライブラリの紹介
- [【15】matplotlib](15_Matplotlib.ipynb)
  - matplotlibを使った可視化
    - 二次元プロット
    - 線種やマーカーの変更
- [【16】numpy](16_Numpy.ipynb)
  - ndarrayを使った演算
  - numpyに含まれる関数
  - matplotlibでの活用
- [【17】pandas](17_Pandas.ipynb)
  - pandasを使ったデータ解析
  - DataFrame形式のオブジェクト
- [【18】pandas 補足](18_Supplemental_Pandas.ipynb)
  - グラフで日本語フォントを使用
  - matplotlibのスタイル変更
  - 外部ファイルを読み込み


## スライド
- [Google Colaboratoryの導入](slide/01_introduce_colab.pdf)
- [CSVファイルのアップロード](slide/02_upload_csv.pdf)

## 関連ファイル
- [実行環境のバージョン確認](debug_env.ipynb)

## サンプルデータ
- [都道府県別 人口の推移](data/census.csv)
  - 「国勢調査 男女別人口－全国，都道府県 (総務省 作成)」をもとに作成
  - 時系列のデータ解析などに使用
  - 調査年月：2015年
  - 提供分類：CSV形式による主要時系列データ


## 使い方
ファイル一式をDLする場合、「Code」ボタンをクリックして展開されるメニューから「Download ZIP」を選択してください。

![ss](images/howto_download_01.png)

ファイル単体をDLする場合、ファイル単体を開いて「RAW」ボタンを押すとファイル単体のアドレスが取得できます。
![ss](images/howto_download_02.png)
![ss](images/howto_download_03.png)

ファイル単体のアドレスがわかれば、wgetなどでDLできます。
![ss](images/howto_download_04.png)
