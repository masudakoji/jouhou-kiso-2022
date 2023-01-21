---
marp: true
theme: gaia
footer: "1年 情報基礎 -CSVファイルのアップロード-"
paginate: true
---
<style>
    @import url('https://fonts.googleapis.com/css2?family=Noto+Serif&display=swap');

    /* レイアウト */
    section {
    background-color: #FFF5EE;
    font-family: "Helvetica Neue", Arial, "Hiragino Kaku Gothic ProN",
        "Hiragino Sans", Meiryo, sans-serif;
    padding: 40px 30px 30px 30px;
    }

    /* フォントサイズ設定 */
    section {
        font-size: 200%;
    }
    section > ul, ol, p{
        font-size: 70%;
    }
    section > h1{
        font-size: 110%;
    }
    section > h2{
        font-size: 80%;
    }
    section > h3{
        font-size: 70%;
    }

    /* リンクのデコレーションを消す */
    a{
        text-decoration: none;
    }

    /* 画像を中央に表示させる */
    img[alt~="center"] {
    display: block;
    margin: 0 auto;
    }

    /* フッター設定 */
    section::after,
    footer {
    color: white;
    background-color: #44aada;
    height: 46px;
    margin-bottom: 0px;
    font-size: 50%;
    padding: 0px 20px 0px 20px;
    }
</style>



<!-- タイトルスライドのフォントサイズ修正 -->
<!-- _class: lead 　 -->
<style scoped>
    section > h1{
        font-size: 150%;
    }
</style>

# 1年 情報基礎
## CSVファイルのアップロード


---
Google Colaboratoryを開いて、左のメニューあるアイコンをクリック
![w:1230 center](img02/ss01.png)



---
「ファイル」メニューが開く
![w:1230 center](img02/ss02.png)

---
もし、次のような表示が出た場合、ランタイムに接続されていないので、コードを何か追加して実行
![w:1230 center](img02/ss03.png)

---
コードを追加して実行するとランタイムに接続できるので、次のように表示される
![w:1230 center](img02/ss04.png)

---
自身のPC上にあるCSVファイルをドラッグ&ドロップすると、CSVファイルを追加できる
![w:1230 center](img02/ss05.png)

---
アップロードしたCSVファイルを読み込むことができた
![w:1230 center](img02/ss06.png)



