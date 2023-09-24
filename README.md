# Multitask Meta-Learning modification of "The Close Relationship Between Contrastive Learning and Meta-Learning"

Fork of the repo https://github.com/RenkunNi/MetaContrastive

## MTM SSL training Examples on CIFAR10

 ```bash
 python train.py --config configs/imagenet_train_epochs100_bs512.yaml --dist_address '127.0.0.1:1672' --n_supp 1 --n_query 1 --multiplier 2 --arch ResNet50 --seed 1234 --run_id 000001 --head contrastive --accu_iter 1 --batch_size 256 --lr 2.4 --iters 1000800 --eval_freq 100080 --save_freq 12510 --temperature 10.
 ```