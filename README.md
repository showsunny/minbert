用于情感分类的minBERT(en)

```bash
git clone https://github.com/showsunny/minbert.git
```
安装环境和依赖项
```bash
 source setup.sh
```
预训练
```bash
python3 classifier.py --option pretrain --lr 1e-3
```
微调
```bash
python3 classifier.py --option finetune --lr 1e-5
```
