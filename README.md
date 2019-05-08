# 制限について
  * 12時間ごとに90分利用可能
  
# プログラム編

## ドライブをマウント
  * `from google.colab import drive`でパッケージインポート
  * 実際のコード
    ```   
      from google.colab import drive
      drive.mount('/content/drive')
    ```
  * 実行すると初回はアカウントに承認してもらうようにと促される（結果に表示されたURLにアクセスして承認する ）
