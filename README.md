# Telco-customer-churn

kaggleのtelco-customer-churn-ibmデータセットを利用してデータの前処理、可視化、解析を行いました。  
参照データセット：https://www.kaggle.com/datasets/waseemalastal/telco-customer-churn-ibm-dataset  

解析の目的は、どういった特徴を持つ顧客がサービスを解約する傾向にあるかを把握することです。  
このことを把握することで、解約させずサービスを継続させるためにどういった施策を打ち出せるかも合わせて検討しました。  

作業環境はGoogle colaboratoryを使用しました。  
他の環境で実行する際は、データダウンロード周りを工夫して実行してください。  

今回用いた解析は以下の2つです。  
 - 生存時間解析
 - 機会学習（ランダムフォレスト）

データの可視化で工夫した点はPlotlyをできるだけ使用することで、Webブラウザでインタラクティブに表示できるようにしたことです。  
ユーザーがグラフにカーソルを合わせることでデータの詳細を理解しやすいようにしました。



以下、データの確認内容の一部です。
![データフレーム特徴量](https://github.com/user-attachments/assets/01dced33-278c-419c-bab2-92de8cbfe911)
![相関関係マトリックス](https://github.com/user-attachments/assets/c550bbb4-a6fe-4638-8a25-595b0b243e4d)
![データ可視化1](https://github.com/user-attachments/assets/5eaaab0a-7acd-4dc0-a705-9f0dd13d7402)
![データ可視化2](https://github.com/user-attachments/assets/a7dc3a75-c48b-4838-8931-c428e1339e1b)
![データ可視化_生存時間解析](https://github.com/user-attachments/assets/a18e2dde-cc30-45e4-8b15-8d0085dc10b7)
![ランダムフォレスト](https://github.com/user-attachments/assets/f4d185d2-fc26-47dd-a50b-253bbbbd6b89)
![まとめ](https://github.com/user-attachments/assets/145c09de-dc08-4f68-8abd-dd7293f516c4)
