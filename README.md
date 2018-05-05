# KyutechOnCampus
Googleロケーション履歴から九工大キャンパス出勤時間を抽出します．

## 使い方：

index.htmlをダウンロードして，ブラウザでファイルとして開いて下さい．そこに書かれた説明のとおりにExcelを作成すれば，出勤簿の出来上がりです．

### 九工大キャンパス出勤時間抽出ツールの使い方

Googleロケーション履歴から九工大キャンパス出勤時間を抽出します．
ロケーション履歴のデータはどこにも送られませんので，安心してご利用下さい．

1. ブラウザでGoogleアカウントにログインした状態で，以下のURLにアクセスする．
https://takeout.google.com/settings/takeout
2. [選択解除]をして[ロケーション履歴(Location history)]だけチェックを入れ，[次へ]
[アーカイブを作成]→準備画面に遷移し，しばらく待ちます．
3. 準備が終わったら，[ダウンロード]（再度パスワードを聞かます．）
4. ダウンロードしたtakeout-*/を解凍すると，以下のファイルが有るはずです．
 ロケーション履歴/ロケーション履歴.json
6. このファイルを以下のファイル選択から選択します．
7. するとその下に指定した年・月の職場滞在時間が抽出されます．
8. 必要に応じて年・月を切り替えて下さい．
9. それをコピーして，記録簿のExcelに[形式を選択して貼り付け]→[テキスト]で貼り付けます．
10. 以上！
（※深夜は3時までを前日と数えます．ただし月末の深夜は考慮していません！）

