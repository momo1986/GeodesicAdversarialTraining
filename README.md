# GeodesicAdversarialTraining
* To run the Geodesic Adversarial Training
```bash
python GeodesicAT.py --net 'WRN'
python GeodesicAT.py --net 'resnet18'
```
* To run the evaluation program
```bash
python evaluate_attacks.py --model-path ${MODEL-PATH} --attack-method FGSM --dataset cifar10 (or cifar100)
```

