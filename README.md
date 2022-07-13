# PyTorch and ML Tutorial Notebook

To utilize these notebooks, please make sure that you have `miniconda` installed. If not, see [here](https://docs.conda.io/en/latest/miniconda.html).

Once `conda` is installed, run the following.

```
$ conda create --name pytorch-intro python=3.8
$ conda activate pytorch-intro
$ pip install -r requirements.txt
```

If you are interested in GPU acceleration with PyTorch, see [here](https://pytorch.org/get-started/locally/). The following commands are below for your convenience.

For Linux:
```
$ pip install pytorch torchvision torchaudio cudatoolkit=11.3 -c pytorch
```

For Windows:
```
$ pip install pytorch torchvision torchaudio cudatoolkit=11.3 -c pytorch
```

For M1 Macbooks:
```
$ pip install pytorch torchvision torchaudio -c pytorch-nightly
```
