# DUVW

# Data Usage Verifiable Watermarking (DUVW) scheme

### Overview
This repository is the official implementation of DUVW, and the corresponding paper is under review.

### Prerequisites

```
python = 3.8.17
pytorch = 2.0.0
matplotlib
numpy
...
```


### Running the experiments

1. To run the DUVW on MNIST
```
python /VMU/Verifiable_MU/On_MNIST/VMU_on_MNIST.py 
```
2. To run the MIB on MNIST
```
python /VMU/Verifiable_MU/On_MNIST/Membership_inf_via_backdoor/MIB_on_MNIST.py 
```

3. To run the DUVW on CIFAR10
```
python /VMU/Verifiable_MU/On_CIFAR10/VMU_on_CIFAR10.py 
```

4. To run the MIB on CIFAR10
```
python /VMU/Verifiable_MU/On_CIFAR10/Membership_inf_via_backdoor/MIB_on_CIFAR10.py
```

5. To run the DUVW on CIFAR100
```
python /VMU/Verifiable_MU/On_CIFAR100/VMU_on_CIFAR100.py 
```

6. To run the DUVW on CelebA
```
python /VMU/Verifiable_MU/On_CelebA/VMU_on_CelebA32.py 
```

7. To run the MIB on CelebA
```
python /VMU/Verifiable_MU/On_CelebA/MIB_method/MIB_on_CelebA.py
```