# PHP とデータベースを利用したカレンダーアプリ

## 職業訓練校の課題で制作したカレンダーアプリです

課題としての要件は、クリックすることで月の遷移ができるカレンダー表示、それに対してデータベースを利用した予定の追加、削除、変更、そしてその結果のポップアップ表示でした。

複数の php ファイルを遷移しつつスケジュールの登録、削除をしてもよいとのことでしたが、フォームの送信画面にたびたび遷移するのはあんまり好みではなかったので、できるだけユーザは index.php に対するアクセスだけですべての機能を使えるように javascript から php にリクエストを投げて裏で処理を行い、index.php に反映出来る方法を調べてそうなるように記述しました
