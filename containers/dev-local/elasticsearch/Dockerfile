FROM docker.elastic.co/elasticsearch/elasticsearch-oss:7.9.3

# kuromojiをインストール
RUN elasticsearch-plugin  install analysis-kuromoji

# ICU analysis pluginをインストール
RUN elasticsearch-plugin  install analysis-icu
