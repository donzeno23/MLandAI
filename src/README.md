## Install pip-tools
```
python3 -m pip install pip-tools

Collecting pip-tools
  Downloading pip_tools-7.3.0-py3-none-any.whl.metadata (23 kB)
Collecting build (from pip-tools)
  Downloading build-1.0.3-py3-none-any.whl.metadata (4.2 kB)
Collecting click>=8 (from pip-tools)
  Downloading click-8.1.7-py3-none-any.whl.metadata (3.0 kB)
Requirement already satisfied: pip>=22.2 in ./venv/lib/python3.11/site-packages (from pip-tools) (24.0)
Requirement already satisfied: setuptools in ./venv/lib/python3.11/site-packages (from pip-tools) (67.6.1)
Requirement already satisfied: wheel in ./venv/lib/python3.11/site-packages (from pip-tools) (0.42.0)
Requirement already satisfied: packaging>=19.0 in ./venv/lib/python3.11/site-packages (from build->pip-tools) (23.2)
Collecting pyproject_hooks (from build->pip-tools)
  Downloading pyproject_hooks-1.0.0-py3-none-any.whl (9.3 kB)
Downloading pip_tools-7.3.0-py3-none-any.whl (57 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 57.4/57.4 kB 3.6 MB/s eta 0:00:00
Downloading click-8.1.7-py3-none-any.whl (97 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 97.9/97.9 kB 6.3 MB/s eta 0:00:00
Downloading build-1.0.3-py3-none-any.whl (18 kB)
Installing collected packages: pyproject_hooks, click, build, pip-tools
Successfully installed build-1.0.3 click-8.1.7 pip-tools-7.3.0 pyproject_hooks-1.0.0
```

## Install packages
```
(venv) Rachels-MacBook-Pro:src racheldaloia$ pip3 install beyondml
Collecting beyondml
  Downloading beyondml-0.1.7-py3-none-any.whl (74 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 74.9/74.9 kB 3.1 MB/s eta 0:00:00
Collecting tensorflow<=2.13
  Downloading tensorflow-2.13.0-cp311-cp311-macosx_10_15_x86_64.whl (216.3 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 216.3/216.3 MB 3.1 MB/s eta 0:00:00
Collecting torch
  Downloading torch-2.2.0-cp311-none-macosx_10_9_x86_64.whl (150.6 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 150.6/150.6 MB 8.4 MB/s eta 0:00:00
Collecting absl-py>=1.0.0
  Downloading absl_py-2.1.0-py3-none-any.whl (133 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 133.7/133.7 kB 14.6 MB/s eta 0:00:00
Collecting astunparse>=1.6.0
  Downloading astunparse-1.6.3-py2.py3-none-any.whl (12 kB)
Collecting flatbuffers>=23.1.21
  Downloading flatbuffers-23.5.26-py2.py3-none-any.whl (26 kB)
Collecting gast<=0.4.0,>=0.2.1
  Downloading gast-0.4.0-py3-none-any.whl (9.8 kB)
Collecting google-pasta>=0.1.1
  Downloading google_pasta-0.2.0-py3-none-any.whl (57 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 57.5/57.5 kB 5.5 MB/s eta 0:00:00
Collecting h5py>=2.9.0
  Downloading h5py-3.10.0-cp311-cp311-macosx_10_9_x86_64.whl (3.2 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 3.2/3.2 MB 11.6 MB/s eta 0:00:00
Collecting libclang>=13.0.0
  Downloading libclang-16.0.6-py2.py3-none-macosx_10_9_x86_64.whl (24.5 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 24.5/24.5 MB 9.4 MB/s eta 0:00:00
Collecting numpy<=1.24.3,>=1.22
  Downloading numpy-1.24.3-cp311-cp311-macosx_10_9_x86_64.whl (19.8 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 19.8/19.8 MB 12.3 MB/s eta 0:00:00
Collecting opt-einsum>=2.3.2
  Downloading opt_einsum-3.3.0-py3-none-any.whl (65 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 65.5/65.5 kB 5.1 MB/s eta 0:00:00
Collecting packaging
  Using cached packaging-23.2-py3-none-any.whl (53 kB)
Collecting protobuf!=4.21.0,!=4.21.1,!=4.21.2,!=4.21.3,!=4.21.4,!=4.21.5,<5.0.0dev,>=3.20.3
  Downloading protobuf-4.25.2-cp37-abi3-macosx_10_9_universal2.whl (394 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 394.2/394.2 kB 15.2 MB/s eta 0:00:00
Requirement already satisfied: setuptools in ./venv/lib/python3.11/site-packages (from tensorflow<=2.13->beyondml) (67.6.1)
Collecting six>=1.12.0
  Using cached six-1.16.0-py2.py3-none-any.whl (11 kB)
Collecting termcolor>=1.1.0
  Downloading termcolor-2.4.0-py3-none-any.whl (7.7 kB)
Collecting typing-extensions<4.6.0,>=3.6.6
  Using cached typing_extensions-4.5.0-py3-none-any.whl (27 kB)
Collecting wrapt>=1.11.0
  Downloading wrapt-1.16.0-cp311-cp311-macosx_10_9_x86_64.whl (37 kB)
Collecting grpcio<2.0,>=1.24.3
  Downloading grpcio-1.60.1-cp311-cp311-macosx_10_10_universal2.whl (9.6 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 9.6/9.6 MB 10.3 MB/s eta 0:00:00
Collecting tensorboard<2.14,>=2.13
  Downloading tensorboard-2.13.0-py3-none-any.whl (5.6 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 5.6/5.6 MB 9.2 MB/s eta 0:00:00
Collecting tensorflow-estimator<2.14,>=2.13.0
  Downloading tensorflow_estimator-2.13.0-py2.py3-none-any.whl (440 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 440.8/440.8 kB 9.2 MB/s eta 0:00:00
Collecting keras<2.14,>=2.13.1
  Downloading keras-2.13.1-py3-none-any.whl (1.7 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.7/1.7 MB 11.9 MB/s eta 0:00:00
Collecting tensorflow-io-gcs-filesystem>=0.23.1
  Downloading tensorflow_io_gcs_filesystem-0.36.0-cp311-cp311-macosx_10_14_x86_64.whl (2.5 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 2.5/2.5 MB 14.1 MB/s eta 0:00:00
Collecting filelock
  Using cached filelock-3.13.1-py3-none-any.whl (11 kB)
Collecting torch
  Downloading torch-2.1.2-cp311-none-macosx_10_9_x86_64.whl (146.7 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 146.7/146.7 MB 4.6 MB/s eta 0:00:00
Collecting sympy
  Downloading sympy-1.12-py3-none-any.whl (5.7 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 5.7/5.7 MB 10.5 MB/s eta 0:00:00
Collecting networkx
  Downloading networkx-3.2.1-py3-none-any.whl (1.6 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.6/1.6 MB 10.5 MB/s eta 0:00:00
Collecting jinja2
  Using cached Jinja2-3.1.3-py3-none-any.whl (133 kB)
Collecting fsspec
  Downloading fsspec-2024.2.0-py3-none-any.whl (170 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 170.9/170.9 kB 6.2 MB/s eta 0:00:00
Collecting wheel<1.0,>=0.23.0
  Using cached wheel-0.42.0-py3-none-any.whl (65 kB)
Collecting google-auth<3,>=1.6.3
  Downloading google_auth-2.27.0-py2.py3-none-any.whl (186 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 186.8/186.8 kB 6.9 MB/s eta 0:00:00
Collecting google-auth-oauthlib<1.1,>=0.5
  Downloading google_auth_oauthlib-1.0.0-py2.py3-none-any.whl (18 kB)
Collecting markdown>=2.6.8
  Downloading Markdown-3.5.2-py3-none-any.whl (103 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 103.9/103.9 kB 4.6 MB/s eta 0:00:00
Collecting requests<3,>=2.21.0
  Using cached requests-2.31.0-py3-none-any.whl (62 kB)
Collecting tensorboard-data-server<0.8.0,>=0.7.0
  Downloading tensorboard_data_server-0.7.2-py3-none-macosx_10_9_x86_64.whl (4.8 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 4.8/4.8 MB 8.2 MB/s eta 0:00:00
Collecting werkzeug>=1.0.1
  Downloading werkzeug-3.0.1-py3-none-any.whl (226 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 226.7/226.7 kB 8.8 MB/s eta 0:00:00
Collecting MarkupSafe>=2.0
  Using cached MarkupSafe-2.1.5-cp311-cp311-macosx_10_9_x86_64.whl (14 kB)
Collecting mpmath>=0.19
  Downloading mpmath-1.3.0-py3-none-any.whl (536 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 536.2/536.2 kB 12.4 MB/s eta 0:00:00
Collecting cachetools<6.0,>=2.0.0
  Using cached cachetools-5.3.2-py3-none-any.whl (9.3 kB)
Collecting pyasn1-modules>=0.2.1
  Using cached pyasn1_modules-0.3.0-py2.py3-none-any.whl (181 kB)
Collecting rsa<5,>=3.1.4
  Downloading rsa-4.9-py3-none-any.whl (34 kB)
Collecting requests-oauthlib>=0.7.0
  Using cached requests_oauthlib-1.3.1-py2.py3-none-any.whl (23 kB)
Collecting charset-normalizer<4,>=2
  Using cached charset_normalizer-3.3.2-cp311-cp311-macosx_10_9_x86_64.whl (121 kB)
Collecting idna<4,>=2.5
  Using cached idna-3.6-py3-none-any.whl (61 kB)
Collecting urllib3<3,>=1.21.1
  Using cached urllib3-2.2.0-py3-none-any.whl (120 kB)
Collecting certifi>=2017.4.17
  Using cached certifi-2024.2.2-py3-none-any.whl (163 kB)
Collecting pyasn1<0.6.0,>=0.4.6
  Using cached pyasn1-0.5.1-py2.py3-none-any.whl (84 kB)
Collecting oauthlib>=3.0.0
  Using cached oauthlib-3.2.2-py3-none-any.whl (151 kB)
Installing collected packages: mpmath, libclang, flatbuffers, wrapt, wheel, urllib3, typing-extensions, termcolor, tensorflow-io-gcs-filesystem, tensorflow-estimator, tensorboard-data-server, sympy, six, pyasn1, protobuf, packaging, oauthlib, numpy, networkx, MarkupSafe, markdown, keras, idna, grpcio, gast, fsspec, filelock, charset-normalizer, certifi, cachetools, absl-py, werkzeug, rsa, requests, pyasn1-modules, opt-einsum, jinja2, h5py, google-pasta, astunparse, torch, requests-oauthlib, google-auth, google-auth-oauthlib, tensorboard, tensorflow, beyondml
Successfully installed MarkupSafe-2.1.5 absl-py-2.1.0 astunparse-1.6.3 beyondml-0.1.7 cachetools-5.3.2 certifi-2024.2.2 charset-normalizer-3.3.2 filelock-3.13.1 flatbuffers-23.5.26 fsspec-2024.2.0 gast-0.4.0 google-auth-2.27.0 google-auth-oauthlib-1.0.0 google-pasta-0.2.0 grpcio-1.60.1 h5py-3.10.0 idna-3.6 jinja2-3.1.3 keras-2.13.1 libclang-16.0.6 markdown-3.5.2 mpmath-1.3.0 networkx-3.2.1 numpy-1.24.3 oauthlib-3.2.2 opt-einsum-3.3.0 packaging-23.2 protobuf-4.25.2 pyasn1-0.5.1 pyasn1-modules-0.3.0 requests-2.31.0 requests-oauthlib-1.3.1 rsa-4.9 six-1.16.0 sympy-1.12 tensorboard-2.13.0 tensorboard-data-server-0.7.2 tensorflow-2.13.0 tensorflow-estimator-2.13.0 tensorflow-io-gcs-filesystem-0.36.0 termcolor-2.4.0 torch-2.1.2 typing-extensions-4.5.0 urllib3-2.2.0 werkzeug-3.0.1 wheel-0.42.0 wrapt-1.16.0
```

## TensorFlow 
```
>>> import beyondml as mann
2024-02-12 20:59:42.375280: I tensorflow/core/platform/cpu_feature_guard.cc:182] This TensorFlow binary is optimized to use available CPU instructions in performance-critical operations.
To enable the following instructions: AVX2 FMA, in other operations, rebuild TensorFlow with the appropriate compiler flags.
```

## AISquared
```
>>> import aisquared as ais
WARNING:root:Failure to load the inference.so custom c++ tensorflow ops. This error is likely caused the version of TensorFlow and TensorFlow Decision Forests are not compatible. Full error:dlopen(/Users/racheldaloia/sandbox/MLandAI/src/venv/lib/python3.11/site-packages/tensorflow_decision_forests/tensorflow/ops/inference/inference.so, 6): Symbol not found: __ZNKSt3__115basic_stringbufIcNS_11char_traitsIcEENS_9allocatorIcEEE3strEv
  Referenced from: /Users/racheldaloia/sandbox/MLandAI/src/venv/lib/python3.11/site-packages/tensorflow_decision_forests/tensorflow/ops/inference/inference.so (which was built for Mac OS X 12.3)
  Expected in: /usr/lib/libc++.1.dylib

Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
  File "/Users/racheldaloia/sandbox/MLandAI/src/venv/lib/python3.11/site-packages/aisquared/__init__.py", line 8, in <module>
    import aisquared.config
  File "/Users/racheldaloia/sandbox/MLandAI/src/venv/lib/python3.11/site-packages/aisquared/config/__init__.py", line 8, in <module>
    from .ModelConfiguration import ModelConfiguration
  File "/Users/racheldaloia/sandbox/MLandAI/src/venv/lib/python3.11/site-packages/aisquared/config/ModelConfiguration.py", line 3, in <module>
    import tensorflowjs as tfjs
  File "/Users/racheldaloia/sandbox/MLandAI/src/venv/lib/python3.11/site-packages/tensorflowjs/__init__.py", line 21, in <module>
    from tensorflowjs import converters
  File "/Users/racheldaloia/sandbox/MLandAI/src/venv/lib/python3.11/site-packages/tensorflowjs/converters/__init__.py", line 21, in <module>
    from tensorflowjs.converters.converter import convert
  File "/Users/racheldaloia/sandbox/MLandAI/src/venv/lib/python3.11/site-packages/tensorflowjs/converters/converter.py", line 37, in <module>
    from tensorflowjs.converters import tf_saved_model_conversion_v2
  File "/Users/racheldaloia/sandbox/MLandAI/src/venv/lib/python3.11/site-packages/tensorflowjs/converters/tf_saved_model_conversion_v2.py", line 28, in <module>
    import tensorflow_decision_forests
  File "/Users/racheldaloia/sandbox/MLandAI/src/venv/lib/python3.11/site-packages/tensorflow_decision_forests/__init__.py", line 64, in <module>
    from tensorflow_decision_forests import keras
  File "/Users/racheldaloia/sandbox/MLandAI/src/venv/lib/python3.11/site-packages/tensorflow_decision_forests/keras/__init__.py", line 53, in <module>
    from tensorflow_decision_forests.keras import core
  File "/Users/racheldaloia/sandbox/MLandAI/src/venv/lib/python3.11/site-packages/tensorflow_decision_forests/keras/core.py", line 61, in <module>
    from tensorflow_decision_forests.keras import core_inference
  File "/Users/racheldaloia/sandbox/MLandAI/src/venv/lib/python3.11/site-packages/tensorflow_decision_forests/keras/core_inference.py", line 36, in <module>
    from tensorflow_decision_forests.tensorflow.ops.inference import api as tf_op
  File "/Users/racheldaloia/sandbox/MLandAI/src/venv/lib/python3.11/site-packages/tensorflow_decision_forests/tensorflow/ops/inference/api.py", line 179, in <module>
    from tensorflow_decision_forests.tensorflow.ops.inference import op
  File "/Users/racheldaloia/sandbox/MLandAI/src/venv/lib/python3.11/site-packages/tensorflow_decision_forests/tensorflow/ops/inference/op.py", line 15, in <module>
    from tensorflow_decision_forests.tensorflow.ops.inference.op_dynamic import *
  File "/Users/racheldaloia/sandbox/MLandAI/src/venv/lib/python3.11/site-packages/tensorflow_decision_forests/tensorflow/ops/inference/op_dynamic.py", line 24, in <module>
    raise e
  File "/Users/racheldaloia/sandbox/MLandAI/src/venv/lib/python3.11/site-packages/tensorflow_decision_forests/tensorflow/ops/inference/op_dynamic.py", line 21, in <module>
    ops = tf.load_op_library(resource_loader.get_path_to_datafile("inference.so"))
          ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/Users/racheldaloia/sandbox/MLandAI/src/venv/lib/python3.11/site-packages/tensorflow/python/framework/load_library.py", line 54, in load_op_library
    lib_handle = py_tf.TF_LoadLibrary(library_filename)
                 ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
tensorflow.python.framework.errors_impl.NotFoundError: dlopen(/Users/racheldaloia/sandbox/MLandAI/src/venv/lib/python3.11/site-packages/tensorflow_decision_forests/tensorflow/ops/inference/inference.so, 6): Symbol not found: __ZNKSt3__115basic_stringbufIcNS_11char_traitsIcEENS_9allocatorIcEEE3strEv
  Referenced from: /Users/racheldaloia/sandbox/MLandAI/src/venv/lib/python3.11/site-packages/tensorflow_decision_forests/tensorflow/ops/inference/inference.so (which was built for Mac OS X 12.3)
  Expected in: /usr/lib/libc++.1.dylib

>>> 

```