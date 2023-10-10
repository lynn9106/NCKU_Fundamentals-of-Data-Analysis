# 環境建置

## anaconda
下載cuda

conda create --name fact_check python=3.8 
conda install pytorch torchvision torchaudio pytorch-cuda=11.8 -c pytorch -c nvidia
# 將requirements.txt放在conda路徑下
pip install -r requirements.txt
conda install ipykernel
pip list
Package                 Version
----------------------- ------------
absl-py                 1.4.0
asttokens               2.2.1
backcall                0.2.0
beautifulsoup4          4.12.2
brotlipy                0.7.0
cachetools              5.3.0
certifi                 2022.12.7
cffi                    1.15.1
charset-normalizer      2.0.4
colorama                0.4.6
cryptography            39.0.1
decorator               5.1.1
dill                    0.3.6
executing               1.2.0
filelock                3.9.0
fsspec                  2023.4.0
google-auth             2.17.3
google-auth-oauthlib    0.4.6
grpcio                  1.54.0
hanlp                   2.1.0b49
hanlp-common            0.0.19
hanlp-downloader        0.0.25
hanlp-trie              0.0.5
huggingface-hub         0.14.1
idna                    3.4
importlib-metadata      6.6.0
ipython                 8.12.2
ipywidgets              8.0.5
jedi                    0.18.2
Jinja2                  3.1.2
joblib                  1.2.0
jupyterlab-widgets      3.0.7
Markdown                3.4.3
MarkupSafe              2.1.1
matplotlib-inline       0.1.6
mkl-fft                 1.3.6
mkl-random              1.2.2
mkl-service             2.4.0
mpmath                  1.2.1
networkx                2.8.4
numpy                   1.24.3
oauthlib                3.2.2
OpenCC                  1.1.1
packaging               23.1
pandarallel             1.6.4
pandas                  1.5.3
parso                   0.8.3
phrasetree              0.0.8
pickleshare             0.7.5
Pillow                  9.4.0
pip                     23.0.1
prompt-toolkit          3.0.38
protobuf                3.20.3
psutil                  5.9.5
pure-eval               0.2.2
pyasn1                  0.5.0
pyasn1-modules          0.3.0
pycparser               2.21
Pygments                2.15.1
pynvml                  11.5.0
pyOpenSSL               23.0.0
PySocks                 1.7.1
python-dateutil         2.8.2
pytz                    2023.3
PyYAML                  6.0
regex                   2023.5.5
requests                2.29.0
requests-oauthlib       1.3.1
rsa                     4.9
scikit-learn            1.2.2
scipy                   1.10.1
sentencepiece           0.1.99
setuptools              66.0.0
six                     1.16.0
soupsieve               2.4.1
stack-data              0.6.2
sympy                   1.11.1
tensorboard             2.11.0
tensorboard-data-server 0.6.1
tensorboard-plugin-wit  1.8.1
termcolor               2.3.0
threadpoolctl           3.1.0
tokenizers              0.11.6
toposort                1.5
torch                   1.13.1+cu116
torchaudio              2.0.0
torchvision             0.15.0
tqdm                    4.65.0
traitlets               5.9.0
transformers            4.27.1
typing_extensions       4.5.0
urllib3                 1.26.15
wcwidth                 0.2.6
Werkzeug                2.3.3
wheel                   0.38.4
widgetsnbextension      4.0.7
wikipedia               1.4.0
win-inet-pton           1.1.0
zipp                    3.15.0


# 檔案路徑
創建data資料夾跟程式碼同一個路徑上
把wikipage放到data資料夾裡面
public_train.jsonl 放到data資料夾裡面
test.jsonl放到data資料夾裡面
剩下的資料夾程式碼回自行建立
程式即可運行