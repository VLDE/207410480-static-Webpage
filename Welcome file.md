＃歡迎來到StackEdit！

嗨！我對你們的第一次降價文件** StackEdit **。如果你想了解StackEdit，你可以讀我。如果你想玩Markdown，可以編輯我。完成後，您可以通過打開導航欄左側的*                            *文件瀏覽器**來創建新文件。


＃文件

StackEdit存儲您的文件在您的瀏覽器，這意味著您的所有文件會自動保存到本地，都可以訪問**下線！**

## 創建文件和文件夾

可以使用導航欄左下角的按鈕訪問文件資源管理器。您可以通過單擊文件資源管理器中的**新文件**按鈕來創建新文件。您還可以通過單擊**新文件夾**按鈕來創建文件夾。

## 切換到另一個文件

您的所有文件都列在文件資源管理器中，您可以通過單擊列表中的文件從一個切換到另一個。

## 重命名文件

您可以通過單擊導航欄中的文件名或單擊文件資源管理器中的**重命名**按鈕來重命名當前文件。

## 刪除文件

您可以通過單擊文件資源管理器中的**刪除**按鈕來刪除當前文件。該文件將被移動到** Trash **文件夾中，並在7天不活動後自動刪除。

## 導出文件

您可以通過單擊菜單中的**導出到磁盤**來導出當前文件。您可以選擇將文件導出為純降價，使用把手模板或PDF作為HTML導出。


＃同步

同步是StackEdit的最大特色之一。它使您可以將工作區中的任何文件與存儲在** Google Drive **，** Dropbox **和** GitHub **帳戶中的其他文件同步。這使您可以繼續在其他設備上書寫，與共享文件的人協作，輕鬆集成到您的工作流程中......同步機制在後台每分鐘進行一次，下載，合併和上傳文件修改。

有兩種類型的同步，它們可以相互補充：

- 工作區同步將自動同步所有文件，文件夾和設置。這將允許您在任何其他設備上獲取工作區。	> 要開始同步工作區，只需在菜單中使用Google登錄即可。- 文件同步將使工作區的一個文件與** Google Drive **，** Dropbox **或** GitHub **中的一個或多個文件同步。	> 在開始同步文件之前，您必須在** Synchronize **子菜單中鏈接一個帳戶。





## 打開一個文件

您可以從打開文件**谷歌驅動器**，** Dropbox的**或** GitHub的**通過打開**同步**子菜單，然後點擊**從打開**。在工作區中打開後，文件中的任何修改都將自動同步。

## 保存文件

您可以保存工作區中的任何文件**谷歌驅動器**，** Dropbox的**或** GitHub的**通過打開**同步**子菜單，然後點擊**節省**。即使工作區中的文件已同步，您也可以將其保存到其他位置。StackEdit可以將一個文件與多個位置和帳戶同步。

## 同步文件

一旦您的文件鏈接到同步位置，StackEdit將通過下載/上傳任何修改定期同步它。如有必要，將執行合併，並解決衝突。

如果您剛剛修改了文件並想要強制同步，請單擊導航欄中的**立即同步**按鈕。

> **注：**的**立即同步**按鈕是無效的，如果你沒有文件同步。 

## 管理文件同步

由於一個文件可以與多個位置進行同步，你可以列出並通過單擊管理同步位置**文件同步**的**同步**子菜單。這允許您列出和刪除鏈接到您的文件的同步位置。


＃出版

在StackEdit中發布使您可以輕鬆地在線發布文件。一旦您對文件感到滿意，您就可以將其發佈到不同的託管平台，例如** Blogger **，** Dropbox **，** Gist **，** GitHub **，** Google Drive **，* * WordPress **和** Zendesk **。使用[ Handlebars templates ]（http://handlebarsjs.com/），您可以完全控制導出的內容。

> 在開始發布之前，您必須在**發布**子菜單中鏈接一個帳戶。

## 發布文件

您可以通過打開**發布**子菜單並單擊**發佈到**來發布文件。對於某些位置，您可以選擇以下格式：

- Markdown：在可以解釋它的網站上發布Markdown文本（例如** GitHub **）， -  HTML：通過Handlebars模板（例如在博客上）發布轉換為HTML的文件。


## 更新出版物

發布後，StackEdit會將您的文件鏈接到該出版物，以便您輕鬆重新發布。修改文件並想要更新出版物後，單擊導航欄中的**立即發布**按鈕。

> **注意：**如果您的文件尚未發布，則**現在**發布**按鈕被禁用。 

## 管理文件發布

由於一個文件可以被發布到多個位置，你可以列出和管理通過點擊發布位置**文件發布**的**發布**子菜單。這允許您列出和刪除鏈接到您的文件的發布位置。


＃降價擴展

StackEdit通過添加額外的** Markdown擴展**擴展了標準Markdown語法，為您提供了一些不錯的功能。

> ** ProTip：**您可以在**文件屬性**對話框中禁用任何** Markdown擴展**。 


## SmartyPants

SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:

|                |ASCII                          |HTML                         |
|----------------|-------------------------------|-----------------------------|
|Single backticks|`'Isn't this fun?'`            |'Isn't this fun?'            |
|Quotes          |`"Isn't this fun?"`            |"Isn't this fun?"            |
|Dashes          |`-- is en-dash, --- is em-dash`|-- is en-dash, --- is em-dash|


## KaTeX

You can render LaTeX mathematical expressions using [KaTeX](https://khan.github.io/KaTeX/):

The *Gamma function* satisfying $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

> You can find more information about **LaTeX** mathematical expressions [here](http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference).


## UML diagrams

You can render UML diagrams using [Mermaid](https://mermaidjs.github.io/). For example, this will produce a sequence diagram:

```美人魚
序列
圖表愛麗絲 -  >>鮑勃：你好鮑勃，你好嗎？
鮑勃 -  >>約翰：約翰，你呢？
鮑勃 -  x愛麗絲：我很感謝！
Bob-x John：我很感謝！
注意約翰的權利：鮑勃認為很長很長一段時間，因為文本不適合連續。鮑勃 - >愛麗絲：和約翰一起檢查......愛麗絲 - > 約翰：是的......約翰，你好嗎？```





這將產生一個流程圖：

```美人魚
圖LR 
A [方形矩形]  - 鏈接文字 - > B（（圓圈））
A  - > C（圓形矩形）
B  - > D {菱形} 
C  - > D```

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEyMjU3MTAwOThdfQ==
-->