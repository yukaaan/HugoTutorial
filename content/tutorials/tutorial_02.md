---
author: "Yuka"
date: "2021-11-27"
linktitle: "Tutorial 02"
title: "No.02 サイトを作成"
categories: ["hugo", "学習"]
tags: ["hugo", "hugo new site", "サイトを作成", "チュートリアル", "02"]
weight: 10
description: "HUGOを使ってサイトを作成するの手順について掲載しています。｜HUGO初心者向け！サイト制作チュートリアル"
---

## サイトを作成する

とりあえずサイトをつくってみます。
HUGO ではコマンドを入力して新しいサイトを作成します。

### コマンドプロンプトまたは VSCode のターミナルを立ち上げます。

{{< figure src="/media/img/tutorial_02/tutorial_02_01.png" alt="コマンドプロンプト" width="396" height="201" >}}

{{< note >}}
コマンドプロンプトを起動する方法は window ＋ R キーを押しすと写真のような入力画面が出てくるので「cmd」と入力、OK を押します。(windows の場合)
{{< /note >}}

{{< figure src="/media/img/tutorial_02/tutorial_02_02.png" alt="ターミナル" width="780" height="281" >}}

{{< note >}}
VSCode の場合は Ctrl + @ でショートカットでターミナルが開けます。
{{< /note >}}

### [Tutorial No.01](/tutorials/tutorial_01)で作成した「Hugo」フォルダへ移動します。

{{< figure src="/media/img/tutorial_02/tutorial_02_03.png" alt="フォルダ1" width="781" height="422" >}}

{{< figure src="/media/img/tutorial_02/tutorial_02_04.png" alt="フォルダ2" width="816" height="495" >}}

{{< note >}}
移動したいフォルダを開いて画像（1 枚目）の赤い丸をクリックすると「C:￥ Hugo」のように画像（2 枚目）表示してくれるのでそのままコピーしてください。渡しの場合は「C:￥ Hugo」でしたが作った場所によって違います。
{{< /note >}}

{{< figure src="/media/img/tutorial_02/tutorial_02_05.png" alt="コマンド入力1" width="777" height="282" >}}

{{< note >}}
ターミナルに`cd`と入力した後、続けて先程コピーした`C:￥Hugo`を貼り付けます。赤い線の様になっていれば OK です。
そして Enter すると「C:￥ Hugo」に移動できます。
{{< /note >}}

### コマンド`hugo new site example_site`を入力します。

{{< figure src="/media/img/tutorial_02/tutorial_02_06.png" alt="コマンド入力2" width="835" height="321" >}}

{{< note >}}
`example_site`の部分はサイトの名前です。自由に設定してください。
{{< /note >}}

{{< figure src="/media/img/tutorial_02/tutorial_02_07.png" alt="コマンド入力3" width="815" height="484" >}}

{{< note >}}
入力が成功するとこのようにメッセージが表示され、サイトが作成されます。
{{< /note >}}

{{< figure src="/media/img/tutorial_02/tutorial_02_08.png" alt="フォルダ確認" width="791" height="453" >}}

{{< note >}}
「Hugo」フォルダを開いて「example_site」フォルダが作成されていれば成功です。
{{< /note >}}
