Optuna Examples
================

This page contains a list of example codes written with Optuna.

### Simple Black-box Optimization

* [Quadratic function](./quadratic_simple.py)

### Examples with ML Libraries

* [AllenNLP](./allennlp/allennlp_simple.py)
* [AllenNLP (Jsonnet)](./allennlp/allennlp_jsonnet.py)
* [Catalyst](./pytorch/catalyst_simple.py)
* [CatBoost](./catboost/catboost_simple.py)
* [Chainer](./chainer/chainer_simple.py)
* [ChainerMN](./chainer/chainermn_simple.py)
* [Dask-ML](./dask_ml/dask_ml_simple.py)
* [FastAI V1](./fastai/fastaiv1_simple.py)
* [FastAI V2](./fastai/fastaiv2_simple.py)
* [Haiku](./haiku/haiku_simple.py)
* [Gluon](./mxnet/gluon_simple.py)
* [Keras](./keras/keras_simple.py)
* [LightGBM](./lightgbm/lightgbm_simple.py)
* [LightGBM Tuner](./lightgbm/lightgbm_tuner_simple.py)
* [MXNet](./mxnet/mxnet_simple.py)
* [PyTorch](./pytorch/pytorch_simple.py)
* [PyTorch Ignite](./pytorch/pytorch_ignite_simple.py)
* [PyTorch Lightning](./pytorch/pytorch_lightning_simple.py)
* [PyTorch Lightning (DDP)](./pytorch/pytorch_lightning_ddp.py)
* [RAPIDS](./rapids_simple.py)
* [Scikit-learn](./sklearn/sklearn_simple.py)
* [Scikit-learn OptunaSearchCV](./sklearn/sklearn_optuna_search_cv_simple.py)
* [Scikit-image](./skimage/skimage_lbp_simple.py)
* [SKORCH](./pytorch/skorch_simple.py)
* [Tensorflow](./tensorflow/tensorflow_estimator_simple.py)
* [Tensorflow (eager)](./tensorflow/tensorflow_eager_simple.py)
* [XGBoost](./xgboost/xgboost_simple.py)


### An example of Optuna Dashboard

The following example demonstrates how to use [Optuna Dashboard](https://github.com/optuna/optuna-dashboard).

* [Starting Optuna Dashboard with in-memory storage](./dashboard/run_server_simple.py)

### An example where an objective function uses additional arguments

The following example demonstrates how to implement an objective function that uses additional arguments other than `trial`.
* [Scikit-learn (callable class version)](./sklearn/sklearn_additional_args.py)

### Examples of Pruning

The following example demonstrates how to implement pruning logic with Optuna.

* [Simple pruning (scikit-learn)](./simple_pruning.py)

In addition, integration modules are available for the following libraries, providing simpler interfaces to utilize pruning.

* [Pruning with Catalyst integration module](./pytorch/catalyst_simple.py)
* [Pruning with CatBoost integration module](./catboost/catboost_pruning.py)
* [Pruning with Chainer integration module](./chainer/chainer_integration.py)
* [Pruning with ChainerMN integration module](./chainer/chainermn_integration.py)
* [Pruning with FastAI V1 integration module](./fastai/fastaiv1_simple.py)
* [Pruning with FastAI V2 integration module](./fastai/fastaiv2_simple.py)
* [Pruning with Keras integration module](./keras/keras_integration.py)
* [Pruning with LightGBM integration module](./lightgbm/lightgbm_integration.py)
* [Pruning with MXNet integration module](./mxnet/mxnet_integration.py)
* [Pruning with PyTorch integration module](./pytorch/pytorch_simple.py)
* [Pruning with PyTorch Ignite integration module](./pytorch/pytorch_ignite_simple.py)
* [Pruning with PyTorch Lightning integration module](./pytorch/pytorch_lightning_simple.py)
* [Pruning with PyTorch Lightning integration module (DDP)](./pytorch/pytorch_lightning_ddp.py)
* [Pruning with Tensorflow integration module](./tensorflow/tensorflow_estimator_integration.py)
* [Pruning with XGBoost integration module](./xgboost/xgboost_integration.py)
* [Pruning with XGBoost integration module (cross validation, XGBoost.cv)](./xgboost/xgboost_cv_integration.py)

### Examples of Samplers

* [Warm Starting CMA-ES](./samplers/warm_starting_cma.py)

### Examples of User-Defined Sampler

* [SimulatedAnnealingSampler](./samplers/simulated_annealing_sampler.py)

### Examples of Terminator

* [Optuna Terminator](./terminator/terminator_simple.py)

### Examples of Multi-Objective Optimization

* [Optimization with BoTorch](./multi_objective/botorch_simple.py)
* [Optimization of MLP with PyTorch](./multi_objective/pytorch_simple.py)

### Examples of Visualization

* [Visualizing study](https://colab.research.google.com/github/optuna/optuna-examples/blob/main/visualization/plot_study.ipynb)
* [Visualizing study with HiPlot](https://colab.research.google.com/github/optuna/optuna-examples/blob/main/hiplot/plot_study.ipynb)

### An example to enqueue trials with given parameter values

* [Enqueuing trials with given parameters](./enqueue_trial.py)

### Examples of aim

* [Tracking optimization process with aim](./aim/aim_integration.py)

### Examples of MLflow

* [Tracking optimization process with MLflow](./mlflow/keras_mlflow.py)

### Examples of Weights & Biases

* [Tracking optimization process with Weights & Biases](./wandb/wandb_integration.py)

### Examples of Hydra

* [Optimization with Hydra](./hydra/simple.py)

### Examples of Distributed Optimization

* [Optimizing on a Dask cluster](./dask/dask_simple.py)
* [Optimizing on Kubernetes](./kubernetes/README.md)
* [Optimizing with Ray's joblib backend](./ray/ray_joblib.py)

### Examples of Reinforcement Learning

* [Optimization of Hyperparameters for Stable-Baslines Agent](./rl/sb3_simple.py)

### External projects using Optuna

* [Allegro Trains](https://github.com/allegroai/trains)
* [BBO-Rietveld: Automated crystal structure refinement](https://github.com/quantumbeam/BBO-Rietveld)
* [Catalyst](https://github.com/catalyst-team/catalyst)
* [CuPy](https://github.com/cupy/cupy)
* [Hydra's Optuna Sweeper plugin](https://hydra.cc/docs/next/plugins/optuna_sweeper/)
* [Mozilla Voice STT](https://github.com/mozilla/DeepSpeech)
* [neptune.ai](https://neptune.ai)
* [OptGBM: A scikit-learn compatible LightGBM estimator with Optuna](https://github.com/Y-oHr-N/OptGBM)
* [Optuna-distributed](https://github.com/xadrianzetx/optuna-distributed)
* [PyKEEN](https://github.com/pykeen/pykeen)
* [RL Baselines Zoo](https://github.com/DLR-RM/rl-baselines3-zoo)
* [Hyperparameter Optimization for Machine Learning, code repository for online course](https://github.com/solegalli/hyperparameter-optimization)

PRs to add additional projects welcome!

### Running with Optuna's Docker images?
You can use our docker images with the tag ending with `-dev` to run most of the examples.
For example, you can run [PyTorch Simple](./pytorch/pytorch_simple.py) via `docker run --rm -v $(pwd):/prj -w /prj optuna/optuna:py3.7-dev python pytorch/pytorch_simple.py`.
Also, you can try our visualization example in Jupyter Notebook by opening `localhost:8888` in your browser after executing this:

```bash
docker run -p 8888:8888 --rm optuna/optuna:py3.7-dev jupyter notebook --allow-root --no-browser --port 8888 --ip 0.0.0.0 --NotebookApp.token='' --NotebookApp.password=''
```
