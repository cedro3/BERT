　.ipynbファイルをクリックするとJupyter notebook形式のファイルが表示されます。先頭にある「Open in Colab」ボタンを押すと、Google Colab上で実行できます。使用環境は、Google Colab が動作すれば、どんなものでも構いません。
 
# BERT_IMDb_run.ipynb
BERTによる英語データのネガポジ判定と判定根拠の可視化を行うコードです。\
・使用するデータセットはIMDbです。これは、映画のレビュー(英文)から文章を取り出し、それがポジテイブな表現なのか、ネガティブな表現なのかをまとめたものです。\
・学習後、テスト文章で推論を行い、その文章のどの単語が判断根拠になっているか(Attention)を可視化します。詳細は、[Qiita](https://qiita.com/jun40vn/items/b7f32621ec7399baa3f8)を参照下さい。\
\
（参考）
・[つくりながら学ぶ! PyTorchによる発展ディープラーニング](https://github.com/YutaroOgawa/pytorch_advanced)
# BERT_pretrained_model.ipynb
日本語BERT_pretrained_modelを使って、穴埋め問題や文生成をやらせるコードです。詳細は、[Qiita](https://qiita.com/jun40vn/items/6458eb3a5301602d7092)を参照下さい。\
\
（参考)\
・[BERT日本語モデルを使って、クリスマスプレゼントに欲しいものを推測してみた](https://www.cresco.co.jp/blog/entry/11517/)\
・[ColabでJUMAN++を使う](https://www.mojirca.com/2019/08/colab-jumanpp.html)

