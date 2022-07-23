# 実行手順
apacheのDocumentrootと設定し、提出したプログラムを同じ階層に入れる。index.phpファイルにアクセスする。
phpやXAMPP、MySqlなどの設定は授業でおこなった設定と同じ。

## 操作
/Applications/XAMPP/xamppfiles/bin/mysql -u root のようにrootユーザでデータベースにアクセスする。アクセスしたら、データベース初期化スクリプトuserscript.sqlを実行しユーザ作成、権限付与、データベース作成、テーブル作成を行う。データベースの設定が完了したら、サーバへアクセスをする。

## データベース
ユーザ名：kkohei

パスワード：kkohei

###データベース設定

データベース名：board_db

テーブル名：site

### テーブル設定

カラム：id,message,modified

          id:主キー、AUTO_INCREMENT、Int
          
    message :VARCHAR(200)
    
    modified :DATETIME



