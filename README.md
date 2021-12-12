# 矩形選択（BOX選択）ができるアプリやエディタについて

この投稿は、JP - XXXXX - xxxxxx-p Advent Calendar 2021 の 10日目の記事です。

矩形選択（くけいせんたく）、Box選択について知ってる人は多分知っていると思うのですが、ちょっとまとめます。

基本的に、コピーペーストを行う際には、SHIFTを押しながら矢印キーで、文章を選択してコピーしたりするかと思うのですが、その際に、ALTを押しながら矢印キーを押したり、マウスでドラッグしたりするとBOX型に選択できたりします。

この矩形選択（BOX選択）についてざっと調べました。


→ お急ぎの方

サクラエディタ、秀丸エディタ、vim、コマンドプロンプト、TeraTermProで使う例を記載。


## サクラエディタ

https://sakura-editor.github.io/help/HLP000014.html

ALT押しながらキーボードの方向キーで選択可能。ALT押しながらマウスドラッグでも可。

矩形選択して、CTRL＋Cでコピー、貼り付けたい位置で、CTRL＋Vで矩形のまま貼り付け。

（選択）

![image](https://user-images.githubusercontent.com/19838489/145711466-d827cf61-f541-4374-b289-ef947c132534.png)

(貼り付け)

![image](https://user-images.githubusercontent.com/19838489/145711474-ae5a404b-8265-41cb-845b-d222df23d770.png)

## 秀丸エディタ（シェアウェア。4200円の時代に購入してから長いこと使ってます。）

ALT押しながらマウスドラッグで矩形選択が可能。

BOX選択というキーが指定も指定できる。私は、F2をBOX選択に割り当てしてます。

F2→矢印キーで選択。CTRL＋Cでコピー、CTRL＋Vで矩形のまま貼り付け。

（選択）

![image](https://user-images.githubusercontent.com/19838489/145711499-a7e0a1fa-d8c9-43e2-b5bd-0b7a37b8d27d.png)

(貼り付け）

![image](https://user-images.githubusercontent.com/19838489/145711504-4746cb8f-5b7e-4da4-a60d-98c71d8497f3.png)


## コマンドプロンプト

個人的には、「簡易編集モード」をチェックして使ってます。

![image](https://user-images.githubusercontent.com/19838489/145711648-67db0a99-fd64-4e43-9943-b53cfe0b3dad.png)

ALT＋マウスドラッグで選択。右クリックでコピー。

（選択＋コピー）

![image](https://user-images.githubusercontent.com/19838489/145711659-80c4c3bc-847e-45af-8040-970421efb1f4.png)

（貼り付け）

右クリックで。（矩形貼り付けできているかは不明）

## vim

ESCでコマンドモード

→ CTRL+vで矩形選択モード開始。矢印（か、HJKL）で選択。

→ y でコピー

![image](https://user-images.githubusercontent.com/19838489/145711676-3da60523-a8c2-47ff-b045-00fe2fa6dd8d.png)

所定の位置まで移動して

→ p で貼り付け

（貼り付け）

![image](https://user-images.githubusercontent.com/19838489/145711684-68b59a79-ca35-4ac8-beaa-d1de883b33de.png)

## TeraTermPro

みんな大好きTeraTermにもありました。ALT＋マウスで選択します。

![image](https://user-images.githubusercontent.com/19838489/145711692-f049aeae-8ca4-4133-b0c5-52c10fd9cc1e.png)



