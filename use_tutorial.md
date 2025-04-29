## 配置环境
```
conda create -n com python==3.12.0
pip install -r requirements.txt
conda activate com
```
## 训练EDM模型
```
bash train.sh
```
## 采样生成数据
```
python sample.py --model_path "./outputs/competition" \
    --n_samples
```
