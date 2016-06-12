103000021 吳柏瑤 軟體實驗 assignment8 Readme

1.explanation of your work
2.problem you encountered and how to solve

    將助教給的SampleSocket與計算小遊戲結合，將app連接server,
    然後將計算出來的答案傳送回server。

    將socket當作主程式做更改，將layout安置於mainactivity裡。
    唯一要改變的，就是當按下+-*/的按鈕時，要先將結果的字串記錄下來，
    並且開啟thread。thread並會執行sockt，連線，
    並用outputstream把直傳去server。此時server會接受到傳回去的答案字串，
    將setlabel改成接收到的值，就完成這次作業了。

    有點還是不了解server&client的傳接順序，
    但藉由實作印出server與client間的互動，已經逐漸明瞭。
    用手機寫出app並且模擬，真的很有趣。
    感謝助教老師總是給我們這麼好的code提供學習，謝謝，辛苦你們了。