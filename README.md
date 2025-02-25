# MT3 LALALA.AI
- [MT3](https://github.com/magenta/mt3)をフォークしたもの。
- 入力ファイル(音源)をYoutubeのURLで指定し、[LALALA.AI](https://www.lalal.ai/)で抽出したインストをMT3に読み込ませる機能を追加。
- MT3の抽出結果(.mid)からサムネイル付きの動画(.mp4)を生成する機能を追加。
- [LALALA.AI](https://www.lalal.ai/)はアクティベーションキーが必要。

# MT3: Multi-Task Multitrack Music Transcription

MT3 is a multi-instrument automatic music transcription model that uses the [T5X framework](https://github.com/google-research/t5x).

This is not an officially supported Google product.

## Transcribe your own audio

Use our [colab notebook](https://colab.research.google.com/github/shuntacurosu/mt3_lalala/blob/main/mt3/colab/music_transcription_with_transformers.ipynb) to
transcribe audio files of your choosing.  You can use a pretrained checkpoint from
either a) the piano transcription model described in [our ISMIR 2021 paper](https://archives.ismir.net/ismir2021/paper/000030.pdf)
or b) the multi-instrument transcription model described in
[our ICLR 2022 paper](https://openreview.net/pdf?id=iMSjopcOn0p).


## Train a model

For now, we do not (easily) support training.  If you like, you can try to
follow the [T5X training instructions](https://github.com/google-research/t5x#training)
and use one of the tasks defined in [tasks.py](mt3/tasks.py).
