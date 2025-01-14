---
license: apache-2.0
base_model: google/vit-base-patch16-224-in21k
tags:
- image-classification
- generated_from_trainer
metrics:
- accuracy
model-index:
- name: skin_cancer_classification
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# skin_cancer_classification

This model is a fine-tuned version of [google/vit-base-patch16-224-in21k](https://huggingface.co/google/vit-base-patch16-224-in21k) on the Pranavkpba2000/skin_cancer_dataset dataset.
It achieves the following results on the evaluation set:
- Loss: 0.5151
- Accuracy: 0.8260

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 0.0002
- train_batch_size: 32
- eval_batch_size: 16
- seed: 42
- optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08
- lr_scheduler_type: linear
- num_epochs: 10

### Training results

| Training Loss | Epoch | Step | Validation Loss | Accuracy |
|:-------------:|:-----:|:----:|:---------------:|:--------:|
| 0.8727        | 0.11  | 100  | 0.9507          | 0.6690   |
| 0.7811        | 0.22  | 200  | 0.8702          | 0.6843   |
| 0.7222        | 0.34  | 300  | 0.7517          | 0.7319   |
| 0.7191        | 0.45  | 400  | 0.7081          | 0.7474   |
| 0.638         | 0.56  | 500  | 0.6894          | 0.7407   |
| 0.6001        | 0.67  | 600  | 0.7046          | 0.7565   |
| 0.5818        | 0.78  | 700  | 0.7262          | 0.7422   |
| 0.5796        | 0.9   | 800  | 0.6466          | 0.7681   |
| 0.4426        | 1.01  | 900  | 0.6218          | 0.7730   |
| 0.4675        | 1.12  | 1000 | 0.6566          | 0.7569   |
| 0.4604        | 1.23  | 1100 | 0.5782          | 0.7938   |
| 0.4426        | 1.35  | 1200 | 0.5478          | 0.7996   |
| 0.3967        | 1.46  | 1300 | 0.5586          | 0.8001   |
| 0.4287        | 1.57  | 1400 | 0.5743          | 0.7948   |
| 0.4066        | 1.68  | 1500 | 0.5839          | 0.7980   |
| 0.4107        | 1.79  | 1600 | 0.5630          | 0.8032   |
| 0.3894        | 1.91  | 1700 | 0.5591          | 0.8004   |
| 0.2612        | 2.02  | 1800 | 0.5176          | 0.8173   |
| 0.346         | 2.13  | 1900 | 0.5796          | 0.7986   |
| 0.2242        | 2.24  | 2000 | 0.5196          | 0.8239   |
| 0.2262        | 2.35  | 2100 | 0.5568          | 0.8103   |
| 0.2764        | 2.47  | 2200 | 0.5428          | 0.8156   |
| 0.2795        | 2.58  | 2300 | 0.5354          | 0.8234   |
| 0.3017        | 2.69  | 2400 | 0.5231          | 0.8197   |
| 0.3295        | 2.8   | 2500 | 0.5550          | 0.8120   |
| 0.3014        | 2.91  | 2600 | 0.5151          | 0.8260   |
| 0.1332        | 3.03  | 2700 | 0.5651          | 0.8182   |
| 0.1519        | 3.14  | 2800 | 0.5824          | 0.8277   |
| 0.1537        | 3.25  | 2900 | 0.6195          | 0.8281   |
| 0.187         | 3.36  | 3000 | 0.6482          | 0.8204   |
| 0.1428        | 3.48  | 3100 | 0.5512          | 0.8463   |
| 0.1743        | 3.59  | 3200 | 0.6152          | 0.8252   |
| 0.1765        | 3.7   | 3300 | 0.5390          | 0.8418   |
| 0.1612        | 3.81  | 3400 | 0.5550          | 0.8279   |
| 0.0938        | 3.92  | 3500 | 0.6105          | 0.8380   |
| 0.0698        | 4.04  | 3600 | 0.6672          | 0.8273   |
| 0.1087        | 4.15  | 3700 | 0.6583          | 0.8184   |
| 0.0558        | 4.26  | 3800 | 0.6141          | 0.8304   |
| 0.0841        | 4.37  | 3900 | 0.6157          | 0.8377   |
| 0.0662        | 4.48  | 4000 | 0.7013          | 0.8289   |
| 0.0883        | 4.6   | 4100 | 0.7606          | 0.8180   |
| 0.0721        | 4.71  | 4200 | 0.6966          | 0.8322   |
| 0.0332        | 4.82  | 4300 | 0.7743          | 0.8189   |
| 0.0994        | 4.93  | 4400 | 0.6767          | 0.8303   |
| 0.0362        | 5.04  | 4500 | 0.7643          | 0.8321   |
| 0.0507        | 5.16  | 4600 | 0.8140          | 0.8348   |
| 0.0322        | 5.27  | 4700 | 0.7166          | 0.8397   |
| 0.0219        | 5.38  | 4800 | 0.7363          | 0.8339   |
| 0.0346        | 5.49  | 4900 | 0.7343          | 0.8435   |
| 0.0638        | 5.61  | 5000 | 0.7396          | 0.8441   |
| 0.1143        | 5.72  | 5100 | 0.8020          | 0.8338   |
| 0.024         | 5.83  | 5200 | 0.7715          | 0.8446   |
| 0.0203        | 5.94  | 5300 | 0.7485          | 0.8439   |
| 0.0172        | 6.05  | 5400 | 0.7893          | 0.8467   |
| 0.0115        | 6.17  | 5500 | 0.7671          | 0.8505   |
| 0.0628        | 6.28  | 5600 | 0.7690          | 0.8477   |
| 0.0475        | 6.39  | 5700 | 0.7534          | 0.8488   |
| 0.0193        | 6.5   | 5800 | 0.8026          | 0.8497   |
| 0.0163        | 6.61  | 5900 | 0.7703          | 0.8562   |
| 0.0232        | 6.73  | 6000 | 0.8823          | 0.8471   |
| 0.0157        | 6.84  | 6100 | 0.7953          | 0.8435   |
| 0.0211        | 6.95  | 6200 | 0.8299          | 0.8391   |
| 0.0007        | 7.06  | 6300 | 0.7862          | 0.8532   |
| 0.0085        | 7.17  | 6400 | 0.8090          | 0.8548   |
| 0.0153        | 7.29  | 6500 | 0.8183          | 0.8576   |
| 0.0031        | 7.4   | 6600 | 0.8853          | 0.8425   |
| 0.0112        | 7.51  | 6700 | 0.8415          | 0.8574   |
| 0.0012        | 7.62  | 6800 | 0.8442          | 0.8569   |
| 0.0015        | 7.74  | 6900 | 0.8475          | 0.8564   |
| 0.0043        | 7.85  | 7000 | 0.8748          | 0.8452   |
| 0.0099        | 7.96  | 7100 | 0.8873          | 0.8411   |
| 0.0008        | 8.07  | 7200 | 0.8584          | 0.8559   |
| 0.0004        | 8.18  | 7300 | 0.8598          | 0.8522   |
| 0.0004        | 8.3   | 7400 | 0.8667          | 0.8536   |
| 0.0003        | 8.41  | 7500 | 0.8667          | 0.8576   |
| 0.0073        | 8.52  | 7600 | 0.8736          | 0.8602   |
| 0.0003        | 8.63  | 7700 | 0.8760          | 0.8566   |
| 0.0007        | 8.74  | 7800 | 0.9347          | 0.8540   |
| 0.0073        | 8.86  | 7900 | 0.9070          | 0.8532   |
| 0.0002        | 8.97  | 8000 | 0.9208          | 0.8536   |
| 0.0002        | 9.08  | 8100 | 0.9304          | 0.8555   |
| 0.0003        | 9.19  | 8200 | 0.9301          | 0.8546   |
| 0.0002        | 9.3   | 8300 | 0.9298          | 0.8557   |
| 0.0002        | 9.42  | 8400 | 0.9300          | 0.8557   |
| 0.0003        | 9.53  | 8500 | 0.9283          | 0.8560   |
| 0.0002        | 9.64  | 8600 | 0.9205          | 0.8562   |
| 0.0002        | 9.75  | 8700 | 0.9216          | 0.8566   |
| 0.0002        | 9.87  | 8800 | 0.9204          | 0.8556   |
| 0.0002        | 9.98  | 8900 | 0.9207          | 0.8555   |


### Framework versions

- Transformers 4.39.3
- Pytorch 2.1.2
- Datasets 2.18.0
- Tokenizers 0.15.2
