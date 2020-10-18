# SystemRecognition
## ディレクトリ構成
以下のようなディレクトリ構成で`code`内のスクリプトを実行
```
.
├── code
│   ├── kadai1
│   ├── kadai2
│   └── kadai3
├── figure
│   └── foodimg128
│       ├── bibimba
│       ├── chahan
│       ├── chikenrice
│       ├── curry
│       ├── ebichill
│       ├── gratin
│       ├── gyudon
│       ├── hiyachu
│       ├── kaisendon
│       ├── katsudon
│       ├── meatspa
│       ├── omelet
│       ├── omurice
│       ├── oyakodon
│       ├── pilaf
│       ├── pilaf2curry
│       │   ├── testA
│       │   ├── testB
│       │   ├── trainA
│       │   └── trainB
│       ├── pix2pix_pizza
│       │   ├── test
│       │   ├── train
│       │   └── val
│       ├── pizza
│       ├── ramen
│       ├── rice
│       ├── soba
│       ├── steak
│       ├── tendon
│       ├── unadon
│       └── yakisoba
└── result
    ├── basic_model
    ├── foodimg
    │   └── cgan
    ├── function_fitting
    ├── gratin
    │   ├── dcgan
    │   ├── lsgan
    │   └── wgan
    ├── pilaf2curry
    ├── pix2pix_pizza
    └── pretrained_model
```

## ディレクトリの説明
`code`: 各課題のソースコード(ipybファイル)および実行結果をまとめたディレクトリ<br><br>
`figure`: 画像認識や画像生成に用いた画像(jpg or pngファイル)をまとめたディレクトリ 
          <br>(uecfood10，uecfood20, foodimg128は画像枚数が多い + 公開してよいか不明であったため省略)<br><br>
`result`: 課題の実行結果の画像をまとめたディレクトリ
   - functing_fitting: `fullconnection_keras.ipynb` の実行結果
   - basic_model: `conv_keras.ipynb`と`mnist_keras.ipynb` の実行結果
   - pretrained_model: `pretrained_keras.ipynb` の実行結果
   - gratin: `lsgan.ipynb`，`dcgan.ipynb`，`wgan.ipynb` の実行結果
   - foodimg: `conditional_gan.ipynb`の実行結果
   - pilaf2curry: `cyclegan.ipynb`の実行結果
   - pix2pix: `pix2pix.ipynb`の実行結果
  
