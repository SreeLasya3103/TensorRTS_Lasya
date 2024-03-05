# TensorRTS_Lasya

Steps to Run the TensorRTS

```
conda create -n ENN python=3.8
conda activate ENN
pip install entity-gym ( e.g :- https://github.com/entity-neural-network/entity-gym )
pip install enn-trainer ( e.g :- https://github.com/entity-neural-network/enn-trainer )
pip install torch==1.12.0+cu113 -f https://download.pytorch.org/whl/cu113/torch_stable.html
pip install torch-scatter -f https://data.pyg.org/whl/torch-1.12.0+cu113.html
```

```
python TensorRTS.py
python TensorRTS_Selfplay.py
```

Training

```
python train.py --config=config.ron --checkpoint-dir=checkpoints
python train_selfplay.py --config=config.ron --checkpoint-dir=selfplay_checkpoints
```
