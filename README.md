# elasticsearch サンプル

## 起動

```
docker-compose up
```

## 各種URL

### elasticsearchエンドポイント

http://localhost:9200


### kibanaエンドポイント

http://localhost:5601


## 各種indexとクエリ

- es/index/join_test.json
  es6で入ったjoin fieldを使った親子関係のデータサンプル

- es/query_sample/contents.txt
    contents.txt join fieldを使ったデータのクエリのサンプル

- es/index/nested_test.json
  nested fieldを使った親子関係のデータサンプル

- es/query_sample/nested-contents.txt
    nested fieldを使ったデータのクエリのサンプル
