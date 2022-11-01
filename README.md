# iimonTest2-B
ローカルでの実行方法

①自身が利用しているデータベースの情報を、application.propertiesに入力する。

②以下のsql文を実行する。 

CREATE TABLE user ( id SERIAL PRIMARY KEY, user_name TEXT, password TEXT );

CREATE TABLE post ( id SERIAL PRIMARY KEY, user_name TEXT, text TEXT );

③ターミナルで`iimonTest2-B/build/libs/IimonTest2-Bcomplete1-0.0.1-SNAPSHOT.jar`を実行する。

④`http://localhost:8080/post`にアクセスする。
