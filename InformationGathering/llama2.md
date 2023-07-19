# Llama2について

参考サイト
- [MetaとMicrosoftが提携し、「Llama 2」をリリース](https://qiita.com/jingwora/items/49eec682a6e93ea08cc0)
- [Metaの次世代オープンソースLLM「Llama 2」が発表 ～AzureとWindows上で動作サポート](https://forest.watch.impress.co.jp/docs/news/1517341.html)

llamaはメタ製

今回はwindowsと提携。Azureとも

パラメタ数は7B、13B、70Bの3モデル

さすがに70Bはローカルで動かせないか？

性能はこんな感じ
![](https://asset.watch.impress.co.jp/img/wf/docs/1517/341/3_l.jpg)

Hugging Faceとかでも今後使用できる感じ＼(^o^)／

[llama2 70B Chatbot](https://huggingface.co/spaces/ysharma/Explore_llamav2_with_TGI)

結構すごい性能SQLとか理解している。

```
・7B モデル : "GPU [medium] - 1x Nvidia A10G" 推奨
・13B モデル : "GPU [xlarge] - 1x Nvidia A100" 推奨
・70B モデル : "GPU [xxlarge] - 8x Nvidia A100" 推奨
```

chat-GPT3.5ぐらいに匹敵している。

文字数すこしネックかも
