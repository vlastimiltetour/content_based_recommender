### Product Recommendation System Using Efir Brand Data

This project focuses on building a product recommendation system by utilizing product data from the Efir brand's webpage. The workflow includes:

1. **Data Collection**: Extracting product data from the Efir brand's feed.
2. **Data Preparation**: Using pandas to adjust and clean the data in a DataFrame format.
3. **Feature Extraction**: Leveraging product descriptions as the source data, applying TF-IDF vectorization to extract relevant features.
4. **Similarity Calculation**: Implementing cosine similarity using scikit-learn to determine product similarities.
5. **Recommendation System**: Predicting and recommending products based on the calculated similarities.
6. **Clustering**: Applying the knee method to estimate the optimal number of clusters for product categorization.

This system is designed to provide accurate and efficient product recommendations, enhancing the user experience on Efir's platform.

absl-py==1.4.0
accelerate==0.32.1
aiohappyeyeballs==2.4.0
aiohttp==3.10.5
aiosignal==1.3.1
alabaster==0.7.16
albucore==0.0.13
albumentations==1.4.14
altair==4.2.2
annotated-types==0.7.0
anyio==3.7.1
argon2-cffi==23.1.0
argon2-cffi-bindings==21.2.0
array_record==0.5.1
arviz==0.18.0
asn1crypto==1.5.1
astropy==6.1.2
astropy-iers-data==0.2024.8.19.0.32.16
astunparse==1.6.3
async-timeout==4.0.3
atpublic==4.1.0
attrs==24.2.0
audioread==3.0.1
autograd==1.6.2
babel==2.16.0
backcall==0.2.0
beautifulsoup4==4.12.3
bidict==0.23.1
bigframes==1.15.0
bleach==6.1.0
blinker==1.4
blis==0.7.11
blosc2==2.0.0
bokeh==3.4.3
bqplot==0.12.43
branca==0.7.2
build==1.2.1
CacheControl==0.14.0
cachetools==5.5.0
catalogue==2.0.10
certifi==2024.7.4
cffi==1.17.0
chardet==5.2.0
charset-normalizer==3.3.2
chex==0.1.86
clarabel==0.9.0
click==8.1.7
click-plugins==1.1.1
cligj==0.7.2
cloudpathlib==0.18.1
cloudpickle==2.2.1
cmake==3.30.2
cmdstanpy==1.2.4
colorcet==3.1.0
colorlover==0.3.0
colour==0.1.5
community==1.0.0b1
confection==0.1.5
cons==0.4.6
contextlib2==21.6.0
contourpy==1.2.1
cryptography==43.0.0
cuda-python==12.2.1
cudf-cu12 @ https://pypi.nvidia.com/cudf-cu12/cudf_cu12-24.4.1-cp310-cp310-manylinux_2_28_x86_64.whl#sha256=57366e7ef09dc63e0b389aff20df6c37d91e2790065861ee31a4720149f5b694
cufflinks==0.17.3
cupy-cuda12x==12.2.0
cvxopt==1.3.2
cvxpy==1.5.3
cycler==0.12.1
cymem==2.0.8
Cython==3.0.11
dask==2024.7.1
datascience==0.17.6
db-dtypes==1.3.0
dbus-python==1.2.18
debugpy==1.6.6
decorator==4.4.2
defusedxml==0.7.1
distributed==2024.7.1
distro==1.7.0
dlib==19.24.2
dm-tree==0.1.8
docstring_parser==0.16
docutils==0.18.1
dopamine_rl==4.0.9
duckdb==0.10.3
earthengine-api==0.1.417
easydict==1.13
ecos==2.0.14
editdistance==0.8.1
eerepr==0.0.4
einops==0.8.0
en-core-web-sm @ https://github.com/explosion/spacy-models/releases/download/en_core_web_sm-3.7.1/en_core_web_sm-3.7.1-py3-none-any.whl#sha256=86cc141f63942d4b2c5fcee06630fd6f904788d2f0ab005cce45aadb8fb73889
entrypoints==0.4
et-xmlfile==1.1.0
etils==1.7.0
etuples==0.3.9
eval_type_backport==0.2.0
exceptiongroup==1.2.2
fastai==2.7.16
fastcore==1.5.55
fastdownload==0.0.7
fastjsonschema==2.20.0
fastprogress==1.0.3
fastrlock==0.8.2
filelock==3.15.4
fiona==1.9.6
firebase-admin==6.5.0
Flask==2.2.5
flatbuffers==24.3.25
flax==0.8.4
folium==0.17.0
fonttools==4.53.1
frozendict==2.4.4
frozenlist==1.4.1
fsspec==2024.6.1
future==1.0.0
gast==0.6.0
gcsfs==2024.6.1
GDAL==3.6.4
gdown==5.1.0
geemap==0.34.0
gensim==4.3.3
geocoder==1.38.1
geographiclib==2.0
geopandas==0.14.4
geopy==2.4.1
gin-config==0.5.0
glob2==0.7
google==2.0.3
google-ai-generativelanguage==0.6.6
google-api-core==2.19.1
google-api-python-client==2.137.0
google-auth==2.27.0
google-auth-httplib2==0.2.0
google-auth-oauthlib==1.2.1
google-cloud-aiplatform==1.63.0
google-cloud-bigquery==3.25.0
google-cloud-bigquery-connection==1.15.5
google-cloud-bigquery-storage==2.25.0
google-cloud-bigtable==2.26.0
google-cloud-core==2.4.1
google-cloud-datastore==2.19.0
google-cloud-firestore==2.16.1
google-cloud-functions==1.16.5
google-cloud-iam==2.15.2
google-cloud-language==2.13.4
google-cloud-pubsub==2.23.0
google-cloud-resource-manager==1.12.5
google-cloud-storage==2.8.0
google-cloud-translate==3.15.5
google-colab @ file:///colabtools/dist/google_colab-1.0.0.tar.gz#sha256=d5a4d62982cba30e008a88cc159a73b1a171eb4cbeaa52e6dc8d36e132a6ce2b
google-crc32c==1.5.0
google-generativeai==0.7.2
google-pasta==0.2.0
google-resumable-media==2.7.2
googleapis-common-protos==1.63.2
googledrivedownloader==0.4
graphviz==0.20.3
greenlet==3.0.3
grpc-google-iam-v1==0.13.1
grpcio==1.64.1
grpcio-status==1.48.2
gspread==6.0.2
gspread-dataframe==3.3.1
gym==0.25.2
gym-notices==0.0.8
h5netcdf==1.3.0
h5py==3.11.0
holidays==0.55
holoviews==1.18.3
html5lib==1.1
httpimport==1.3.1
httplib2==0.22.0
huggingface-hub==0.23.5
humanize==4.10.0
hyperopt==0.2.7
ibis-framework==8.0.0
idna==3.7
imageio==2.34.2
imageio-ffmpeg==0.5.1
imagesize==1.4.1
imbalanced-learn==0.12.3
imgaug==0.4.0
immutabledict==4.2.0
importlib_metadata==8.4.0
importlib_resources==6.4.3
imutils==0.5.4
inflect==7.3.1
iniconfig==2.0.0
intel-cmplr-lib-ur==2024.2.1
intel-openmp==2024.2.1
ipyevents==2.0.2
ipyfilechooser==0.6.0
ipykernel==5.5.6
ipyleaflet==0.18.2
ipyparallel==8.8.0
ipython==7.34.0
ipython-genutils==0.2.0
ipython-sql==0.5.0
ipytree==0.2.2
ipywidgets==7.7.1
itsdangerous==2.2.0
jax==0.4.26
jaxlib @ https://storage.googleapis.com/jax-releases/cuda12/jaxlib-0.4.26+cuda12.cudnn89-cp310-cp310-manylinux2014_x86_64.whl#sha256=813cf1fe3e7ca4dbf5327d6e7b4fc8521e92d8bba073ee645ae0d5d036a25750
jeepney==0.7.1
jellyfish==1.1.0
jieba==0.42.1
Jinja2==3.1.4
joblib==1.4.2
jsonpickle==3.2.2
jsonschema==4.23.0
jsonschema-specifications==2023.12.1
jupyter-client==6.1.12
jupyter-console==6.1.0
jupyter-server==1.24.0
jupyter_core==5.7.2
jupyterlab_pygments==0.3.0
jupyterlab_widgets==3.0.11
kaggle==1.6.17
kagglehub==0.2.9
keras==3.4.1
keyring==23.5.0
kiwisolver==1.4.5
langcodes==3.4.0
language_data==1.2.0
launchpadlib==1.10.16
lazr.restfulclient==0.14.4
lazr.uri==1.0.6
lazy_loader==0.4
libclang==18.1.1
librosa==0.10.2.post1
lightgbm==4.4.0
linkify-it-py==2.0.3
llvmlite==0.43.0
locket==1.0.0
logical-unification==0.4.6
lxml==4.9.4
malloy==2024.1089
marisa-trie==1.2.0
Markdown==3.7
markdown-it-py==3.0.0
MarkupSafe==2.1.5
matplotlib==3.7.1
matplotlib-inline==0.1.7
matplotlib-venn==0.11.10
mdit-py-plugins==0.4.1
mdurl==0.1.2
miniKanren==1.0.3
missingno==0.5.2
mistune==0.8.4
mizani==0.9.3
mkl==2024.2.1
ml-dtypes==0.4.0
mlxtend==0.23.1
more-itertools==10.3.0
moviepy==1.0.3
mpmath==1.3.0
msgpack==1.0.8
multidict==6.0.5
multipledispatch==1.0.0
multitasking==0.0.11
murmurhash==1.0.10
music21==9.1.0
namex==0.0.8
natsort==8.4.0
nbclassic==1.1.0
nbclient==0.10.0
nbconvert==6.5.4
nbformat==5.10.4
nest-asyncio==1.6.0
networkx==3.3
nibabel==5.0.1
nltk==3.8.1
notebook==6.5.5
notebook_shim==0.2.4
numba==0.60.0
numexpr==2.10.1
numpy==1.26.4
nvtx==0.2.10
oauth2client==4.1.3
oauthlib==3.2.2
opencv-contrib-python==4.10.0.84
opencv-python==4.10.0.84
opencv-python-headless==4.10.0.84
openpyxl==3.1.5
opt-einsum==3.3.0
optax==0.2.2
optree==0.12.1
orbax-checkpoint==0.6.0
osqp==0.6.7.post0
packaging==24.1
pandas==2.1.4
pandas-datareader==0.10.0
pandas-gbq==0.23.1
pandas-stubs==2.1.4.231227
pandocfilters==1.5.1
panel==1.4.5
param==2.1.1
parso==0.8.4
parsy==2.1
partd==1.4.2
pathlib==1.0.1
patsy==0.5.6
peewee==3.17.6
pexpect==4.9.0
pickleshare==0.7.5
Pillow==9.4.0
pip-tools==7.4.1
platformdirs==4.2.2
plotly==5.15.0
plotnine==0.12.4
pluggy==1.5.0
polars==0.20.2
pooch==1.8.2
portpicker==1.5.2
prefetch_generator==1.0.3
preshed==3.0.9
prettytable==3.11.0
proglog==0.1.10
progressbar2==4.2.0
prometheus_client==0.20.0
promise==2.3
prompt_toolkit==3.0.47
prophet==1.1.5
proto-plus==1.24.0
protobuf==3.20.3
psutil==5.9.5
psycopg2==2.9.9
ptyprocess==0.7.0
py-cpuinfo==9.0.0
py4j==0.10.9.7
pyarrow==14.0.2
pyarrow-hotfix==0.6
pyasn1==0.6.0
pyasn1_modules==0.4.0
pycocotools==2.0.8
pycparser==2.22
pydantic==2.8.2
pydantic_core==2.20.1
pydata-google-auth==1.8.2
pydot==1.4.2
pydot-ng==2.0.0
pydotplus==2.0.2
PyDrive==1.3.1
PyDrive2==1.6.3
pyerfa==2.0.1.4
pygame==2.6.0
Pygments==2.16.1
PyGObject==3.42.1
PyJWT==2.9.0
pymc==5.10.4
pymystem3==0.2.0
pynvjitlink-cu12==0.3.0
PyOpenGL==3.1.7
pyOpenSSL==24.2.1
pyparsing==3.1.2
pyperclip==1.9.0
pyproj==3.6.1
pyproject_hooks==1.1.0
pyshp==2.3.1
PySocks==1.7.1
pytensor==2.18.6
pytest==7.4.4
python-apt==2.4.0
python-box==7.2.0
python-dateutil==2.8.2
python-louvain==0.16
python-slugify==8.0.4
python-utils==3.8.2
pytz==2024.1
pyviz_comms==3.0.3
PyYAML==6.0.2
pyzmq==24.0.1
qdldl==0.1.7.post4
ratelim==0.1.6
referencing==0.35.1
regex==2024.5.15
requests==2.32.3
requests-oauthlib==1.3.1
requirements-parser==0.9.0
rich==13.7.1
rmm-cu12==24.4.0
rpds-py==0.20.0
rpy2==3.4.2
rsa==4.9
safetensors==0.4.4
scikit-image==0.23.2
scikit-learn==1.3.2
scipy==1.13.1
scooby==0.10.0
scs==3.2.6
seaborn==0.13.1
SecretStorage==3.3.1
Send2Trash==1.8.3
sentencepiece==0.1.99
shapely==2.0.6
shellingham==1.5.4
simple_parsing==0.1.5
six==1.16.0
sklearn-pandas==2.2.0
smart-open==7.0.4
sniffio==1.3.1
snowballstemmer==2.2.0
snowflake-connector-python==3.12.1
sortedcontainers==2.4.0
soundfile==0.12.1
soupsieve==2.6
soxr==0.4.0
spacy==3.7.6
spacy-legacy==3.0.12
spacy-loggers==1.0.5
Sphinx==5.0.2
sphinxcontrib-applehelp==2.0.0
sphinxcontrib-devhelp==2.0.0
sphinxcontrib-htmlhelp==2.1.0
sphinxcontrib-jsmath==1.0.1
sphinxcontrib-qthelp==2.0.0
sphinxcontrib-serializinghtml==2.0.0
SQLAlchemy==2.0.32
sqlglot==20.11.0
sqlparse==0.5.1
srsly==2.4.8
stanio==0.5.1
statsmodels==0.14.2
StrEnum==0.4.15
sympy==1.13.2
tables==3.8.0
tabulate==0.9.0
tbb==2021.13.1
tblib==3.0.0
tenacity==9.0.0
tensorboard==2.17.0
tensorboard-data-server==0.7.2
tensorflow==2.17.0
tensorflow-datasets==4.9.6
tensorflow-hub==0.16.1
tensorflow-io-gcs-filesystem==0.37.1
tensorflow-metadata==1.15.0
tensorflow-probability==0.24.0
tensorstore==0.1.64
termcolor==2.4.0
terminado==0.18.1
text-unidecode==1.3
textblob==0.17.1
tf-slim==1.1.0
tf_keras==2.17.0
thinc==8.2.5
threadpoolctl==3.5.0
tifffile==2024.8.10
tinycss2==1.3.0
tokenizers==0.19.1
toml==0.10.2
tomli==2.0.1
tomlkit==0.13.2
toolz==0.12.1
torch @ https://download.pytorch.org/whl/cu121/torch-2.3.1%2Bcu121-cp310-cp310-linux_x86_64.whl#sha256=f0deb5d2f932a68ed54625ba140eddbf2af22be978ee19b9b63c986add6425b2
torchaudio @ https://download.pytorch.org/whl/cu121/torchaudio-2.3.1%2Bcu121-cp310-cp310-linux_x86_64.whl#sha256=0b423f4ae3356f11f6723e8c77208ac3f9361a4f941e4cc08d86c32c137594bc
torchsummary==1.5.1
torchtext==0.18.0
torchvision @ https://download.pytorch.org/whl/cu121/torchvision-0.18.1%2Bcu121-cp310-cp310-linux_x86_64.whl#sha256=e95ba5a2c616939281e01babf11664d6d1725e81bba57ef81f81c3e57e4d4151
tornado==6.3.3
tqdm==4.66.5
traitlets==5.7.1
traittypes==0.2.1
transformers==4.42.4
triton==2.3.1
tweepy==4.14.0
typeguard==4.3.0
typer==0.12.4
types-pytz==2024.1.0.20240417
types-setuptools==73.0.0.20240822
typing_extensions==4.12.2
tzdata==2024.1
tzlocal==5.2
uc-micro-py==1.0.3
uritemplate==4.1.1
urllib3==2.0.7
vega-datasets==0.9.0
wadllib==1.3.6
wasabi==1.1.3
wcwidth==0.2.13
weasel==0.4.1
webcolors==24.8.0
webencodings==0.5.1
websocket-client==1.8.0
Werkzeug==3.0.3
widgetsnbextension==3.6.8
wordcloud==1.9.3
wrapt==1.16.0
xarray==2024.6.0
xarray-einstats==0.7.0
xgboost==2.1.1
xlrd==2.0.1
xyzservices==2024.6.0
yarl==1.9.4
yellowbrick==1.5
yfinance==0.2.41
zict==3.0.0
zipp==3.20.0

