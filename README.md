1. docker-compose.ymlファイルと同じ階層で次を実行(完了までに5分かかる)<br>
docker-compose up -d 

2. docker ps で linux-studyコンテナのSTATUSがUpになっていることを確認<br>
2.1. 何も表示されない場合(exitedの状態)は次を実行<br>
docker restart linux-study

3. 次を実行(コンテナに入ってbashを起動する)<br>
docker exec -it linux-study bash

4. コンテナから出る場合は exit

5. 作業はworkディレクトリで行う(コンテナ上の/work/にマウントされている)
