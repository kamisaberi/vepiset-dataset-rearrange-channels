### in_channels: 45 With normalization

```
[2025-05-09 16:27:37,277] [INFO] Loading pretrained weights from Hugging Face hub (timm/vgg16.tv_in1k)
[2025-05-09 16:27:37,539] [INFO] [timm/vgg16.tv_in1k] Safe alternative available for 'pytorch_model.bin' (as 'model.safetensors'). Loading weights using safetensors.
[2025-05-09 16:27:37,540] [INFO] Converted input conv features.0 pretrained weights from 3 to 45 channel(s)
[2025-05-09 16:27:37,865] [INFO]  contains5089 samples  537 pos
[2025-05-09 16:27:37,865] [INFO]  contains5089 samples
[2025-05-09 16:27:37,866] [INFO]  After filter contains5089 samples  537 pos
[2025-05-09 16:27:37,866] [INFO]  After filter contains5089 samples

val_ds: <torch.utils.data.dataloader.DataLoader object at 0x7fb5fa55ae40>

100%|██████████| 160/160 [00:03<00:00, 46.81it/s]

for threshold: 0.0500, tn: 1688,fp: 2864,fn: 5,tp: 532,precision: 0.1567, recall: 0.9907, f1: 0.2705
for threshold: 0.1000, tn: 2829,fp: 1723,fn: 28,tp: 509,precision: 0.2280, recall: 0.9479, f1: 0.3676
for threshold: 0.1500, tn: 3369,fp: 1183,fn: 59,tp: 478,precision: 0.2878, recall: 0.8901, f1: 0.4349
for threshold: 0.2000, tn: 3651,fp: 901,fn: 73,tp: 464,precision: 0.3399, recall: 0.8641, f1: 0.4879
for threshold: 0.2500, tn: 3872,fp: 680,fn: 86,tp: 451,precision: 0.3988, recall: 0.8399, f1: 0.5408
for threshold: 0.3000, tn: 4031,fp: 521,fn: 109,tp: 428,precision: 0.4510, recall: 0.7970, f1: 0.5760
for threshold: 0.3500, tn: 4165,fp: 387,fn: 130,tp: 407,precision: 0.5126, recall: 0.7579, f1: 0.6116
for threshold: 0.4000, tn: 4269,fp: 283,fn: 152,tp: 385,precision: 0.5763, recall: 0.7169, f1: 0.6390
for threshold: 0.4500, tn: 4337,fp: 215,fn: 178,tp: 359,precision: 0.6254, recall: 0.6685, f1: 0.6463
for threshold: 0.5000, tn: 4386,fp: 166,fn: 210,tp: 327,precision: 0.6633, recall: 0.6089, f1: 0.6350
for threshold: 0.5500, tn: 4428,fp: 124,fn: 231,tp: 306,precision: 0.7116, recall: 0.5698, f1: 0.6329
for threshold: 0.6000, tn: 4457,fp: 95,fn: 250,tp: 287,precision: 0.7513, recall: 0.5345, f1: 0.6246
for threshold: 0.6500, tn: 4483,fp: 69,fn: 276,tp: 261,precision: 0.7909, recall: 0.4860, f1: 0.6021
for threshold: 0.7000, tn: 4502,fp: 50,fn: 296,tp: 241,precision: 0.8282, recall: 0.4488, f1: 0.5821
for threshold: 0.7500, tn: 4517,fp: 35,fn: 315,tp: 222,precision: 0.8638, recall: 0.4134, f1: 0.5592
for threshold: 0.8000, tn: 4532,fp: 20,fn: 331,tp: 206,precision: 0.9115, recall: 0.3836, f1: 0.5400
for threshold: 0.8500, tn: 4539,fp: 13,fn: 358,tp: 179,precision: 0.9323, recall: 0.3333, f1: 0.4911
for threshold: 0.9000, tn: 4542,fp: 10,fn: 384,tp: 153,precision: 0.9387, recall: 0.2849, f1: 0.4371
for threshold: 0.9500, tn: 4545,fp: 7,fn: 418,tp: 119,precision: 0.9444, recall: 0.2216, f1: 0.3590
labels len: 5089
predictions len: 5089
```


### in_channels: 48 Without normalization

```
[2025-05-09 16:30:58,753] [INFO] Loading pretrained weights from Hugging Face hub (timm/vgg16.tv_in1k)
[2025-05-09 16:30:59,021] [INFO] [timm/vgg16.tv_in1k] Safe alternative available for 'pytorch_model.bin' (as 'model.safetensors'). Loading weights using safetensors.
[2025-05-09 16:30:59,022] [INFO] Converted input conv features.0 pretrained weights from 3 to 48 channel(s)
[2025-05-09 16:30:59,359] [INFO]  contains5089 samples  537 pos
[2025-05-09 16:30:59,359] [INFO]  contains5089 samples
[2025-05-09 16:30:59,359] [INFO]  After filter contains5089 samples  537 pos
[2025-05-09 16:30:59,359] [INFO]  After filter contains5089 samples

val_ds: <torch.utils.data.dataloader.DataLoader object at 0x7fb5fa55b860>

100%|██████████| 160/160 [00:03<00:00, 45.59it/s]

for threshold: 0.0500, tn: 0,fp: 4552,fn: 0,tp: 537,precision: 0.1055, recall: 1.0000, f1: 0.1909
for threshold: 0.1000, tn: 1,fp: 4551,fn: 0,tp: 537,precision: 0.1055, recall: 1.0000, f1: 0.1909
for threshold: 0.1500, tn: 3514,fp: 1038,fn: 269,tp: 268,precision: 0.2052, recall: 0.4991, f1: 0.2908
for threshold: 0.2000, tn: 4063,fp: 489,fn: 344,tp: 193,precision: 0.2830, recall: 0.3594, f1: 0.3167
for threshold: 0.2500, tn: 4333,fp: 219,fn: 396,tp: 141,precision: 0.3917, recall: 0.2626, f1: 0.3144
for threshold: 0.3000, tn: 4445,fp: 107,fn: 430,tp: 107,precision: 0.5000, recall: 0.1993, f1: 0.2850
for threshold: 0.3500, tn: 4485,fp: 67,fn: 451,tp: 86,precision: 0.5621, recall: 0.1601, f1: 0.2493
for threshold: 0.4000, tn: 4523,fp: 29,fn: 463,tp: 74,precision: 0.7184, recall: 0.1378, f1: 0.2313
for threshold: 0.4500, tn: 4534,fp: 18,fn: 476,tp: 61,precision: 0.7722, recall: 0.1136, f1: 0.1981
for threshold: 0.5000, tn: 4545,fp: 7,fn: 487,tp: 50,precision: 0.8772, recall: 0.0931, f1: 0.1684
for threshold: 0.5500, tn: 4550,fp: 2,fn: 494,tp: 43,precision: 0.9556, recall: 0.0801, f1: 0.1478
for threshold: 0.6000, tn: 4552,fp: 0,fn: 501,tp: 36,precision: 1.0000, recall: 0.0670, f1: 0.1257
for threshold: 0.6500, tn: 4552,fp: 0,fn: 504,tp: 33,precision: 1.0000, recall: 0.0615, f1: 0.1158
for threshold: 0.7000, tn: 4552,fp: 0,fn: 523,tp: 14,precision: 1.0000, recall: 0.0261, f1: 0.0508
for threshold: 0.7500, tn: 4552,fp: 0,fn: 537,tp: 0,precision: 0.0000, recall: 0.0000, f1: 0.0000
for threshold: 0.8000, tn: 4552,fp: 0,fn: 537,tp: 0,precision: 0.0000, recall: 0.0000, f1: 0.0000
for threshold: 0.8500, tn: 4552,fp: 0,fn: 537,tp: 0,precision: 0.0000, recall: 0.0000, f1: 0.0000
for threshold: 0.9000, tn: 4552,fp: 0,fn: 537,tp: 0,precision: 0.0000, recall: 0.0000, f1: 0.0000
for threshold: 0.9500, tn: 4552,fp: 0,fn: 537,tp: 0,precision: 0.0000, recall: 0.0000, f1: 0.0000
labels len: 5089
predictions len: 5089
```

### in_channels: 48 With normalization

```
[2025-05-09 17:18:08,911] [INFO] Loading pretrained weights from Hugging Face hub (timm/vgg16.tv_in1k)
[2025-05-09 17:18:09,165] [INFO] [timm/vgg16.tv_in1k] Safe alternative available for 'pytorch_model.bin' (as 'model.safetensors'). Loading weights using safetensors.
[2025-05-09 17:18:09,167] [INFO] Converted input conv features.0 pretrained weights from 3 to 48 channel(s)
[2025-05-09 17:18:09,506] [INFO]  contains5089 samples  537 pos
[2025-05-09 17:18:09,506] [INFO]  contains5089 samples
[2025-05-09 17:18:09,507] [INFO]  After filter contains5089 samples  537 pos
[2025-05-09 17:18:09,507] [INFO]  After filter contains5089 samples

val_ds: <torch.utils.data.dataloader.DataLoader object at 0x788dd8357080>

100%|██████████| 160/160 [00:03<00:00, 47.13it/s]

for threshold: 0.0500, tn: 2617,fp: 1935,fn: 29,tp: 508,precision: 0.2079, recall: 0.9460, f1: 0.3409
for threshold: 0.1000, tn: 3717,fp: 835,fn: 92,tp: 445,precision: 0.3477, recall: 0.8287, f1: 0.4898
for threshold: 0.1500, tn: 4064,fp: 488,fn: 143,tp: 394,precision: 0.4467, recall: 0.7337, f1: 0.5553
for threshold: 0.2000, tn: 4238,fp: 314,fn: 180,tp: 357,precision: 0.5320, recall: 0.6648, f1: 0.5911
for threshold: 0.2500, tn: 4341,fp: 211,fn: 206,tp: 331,precision: 0.6107, recall: 0.6164, f1: 0.6135
for threshold: 0.3000, tn: 4406,fp: 146,fn: 232,tp: 305,precision: 0.6763, recall: 0.5680, f1: 0.6174
for threshold: 0.3500, tn: 4438,fp: 114,fn: 255,tp: 282,precision: 0.7121, recall: 0.5251, f1: 0.6045
for threshold: 0.4000, tn: 4463,fp: 89,fn: 280,tp: 257,precision: 0.7428, recall: 0.4786, f1: 0.5821
for threshold: 0.4500, tn: 4485,fp: 67,fn: 292,tp: 245,precision: 0.7853, recall: 0.4562, f1: 0.5771
for threshold: 0.5000, tn: 4509,fp: 43,fn: 302,tp: 235,precision: 0.8453, recall: 0.4376, f1: 0.5767
for threshold: 0.5500, tn: 4520,fp: 32,fn: 314,tp: 223,precision: 0.8745, recall: 0.4153, f1: 0.5631
for threshold: 0.6000, tn: 4525,fp: 27,fn: 322,tp: 215,precision: 0.8884, recall: 0.4004, f1: 0.5520
for threshold: 0.6500, tn: 4528,fp: 24,fn: 334,tp: 203,precision: 0.8943, recall: 0.3780, f1: 0.5314
for threshold: 0.7000, tn: 4531,fp: 21,fn: 346,tp: 191,precision: 0.9009, recall: 0.3557, f1: 0.5100
for threshold: 0.7500, tn: 4538,fp: 14,fn: 361,tp: 176,precision: 0.9263, recall: 0.3277, f1: 0.4842
for threshold: 0.8000, tn: 4542,fp: 10,fn: 369,tp: 168,precision: 0.9438, recall: 0.3128, f1: 0.4699
for threshold: 0.8500, tn: 4544,fp: 8,fn: 383,tp: 154,precision: 0.9506, recall: 0.2868, f1: 0.4406
for threshold: 0.9000, tn: 4544,fp: 8,fn: 389,tp: 148,precision: 0.9487, recall: 0.2756, f1: 0.4271
for threshold: 0.9500, tn: 4547,fp: 5,fn: 403,tp: 134,precision: 0.9640, recall: 0.2495, f1: 0.3964
labels len: 5089
predictions len: 5089
```



### in_channels: 29 With normalization

```
[2025-05-09 17:29:27,839] [INFO] Loading pretrained weights from Hugging Face hub (timm/vgg16.tv_in1k)
[2025-05-09 17:29:28,094] [INFO] [timm/vgg16.tv_in1k] Safe alternative available for 'pytorch_model.bin' (as 'model.safetensors'). Loading weights using safetensors.
[2025-05-09 17:29:28,096] [INFO] Converted input conv features.0 pretrained weights from 3 to 29 channel(s)
[2025-05-09 17:29:28,428] [INFO]  contains5089 samples  537 pos
[2025-05-09 17:29:28,429] [INFO]  contains5089 samples
[2025-05-09 17:29:28,429] [INFO]  After filter contains5089 samples  537 pos
[2025-05-09 17:29:28,429] [INFO]  After filter contains5089 samples

val_ds: <torch.utils.data.dataloader.DataLoader object at 0x788dd8377140>

100%|██████████| 160/160 [00:03<00:00, 51.87it/s]
for threshold: 0.0500, tn: 1360,fp: 3192,fn: 4,tp: 533,precision: 0.1431, recall: 0.9926, f1: 0.2501
for threshold: 0.1000, tn: 2124,fp: 2428,fn: 17,tp: 520,precision: 0.1764, recall: 0.9683, f1: 0.2984
for threshold: 0.1500, tn: 2655,fp: 1897,fn: 33,tp: 504,precision: 0.2099, recall: 0.9385, f1: 0.3431
for threshold: 0.2000, tn: 3072,fp: 1480,fn: 54,tp: 483,precision: 0.2461, recall: 0.8994, f1: 0.3864
for threshold: 0.2500, tn: 3389,fp: 1163,fn: 76,tp: 461,precision: 0.2839, recall: 0.8585, f1: 0.4267
for threshold: 0.3000, tn: 3684,fp: 868,fn: 99,tp: 438,precision: 0.3354, recall: 0.8156, f1: 0.4753
for threshold: 0.3500, tn: 3929,fp: 623,fn: 128,tp: 409,precision: 0.3963, recall: 0.7616, f1: 0.5214
for threshold: 0.4000, tn: 4103,fp: 449,fn: 155,tp: 382,precision: 0.4597, recall: 0.7114, f1: 0.5585
for threshold: 0.4500, tn: 4214,fp: 338,fn: 177,tp: 360,precision: 0.5158, recall: 0.6704, f1: 0.5830
for threshold: 0.5000, tn: 4284,fp: 268,fn: 207,tp: 330,precision: 0.5518, recall: 0.6145, f1: 0.5815
for threshold: 0.5500, tn: 4348,fp: 204,fn: 222,tp: 315,precision: 0.6069, recall: 0.5866, f1: 0.5966
for threshold: 0.6000, tn: 4394,fp: 158,fn: 241,tp: 296,precision: 0.6520, recall: 0.5512, f1: 0.5974
for threshold: 0.6500, tn: 4421,fp: 131,fn: 259,tp: 278,precision: 0.6797, recall: 0.5177, f1: 0.5877
for threshold: 0.7000, tn: 4456,fp: 96,fn: 277,tp: 260,precision: 0.7303, recall: 0.4842, f1: 0.5823
for threshold: 0.7500, tn: 4482,fp: 70,fn: 295,tp: 242,precision: 0.7756, recall: 0.4507, f1: 0.5701
for threshold: 0.8000, tn: 4506,fp: 46,fn: 316,tp: 221,precision: 0.8277, recall: 0.4115, f1: 0.5498
for threshold: 0.8500, tn: 4518,fp: 34,fn: 328,tp: 209,precision: 0.8601, recall: 0.3892, f1: 0.5359
for threshold: 0.9000, tn: 4532,fp: 20,fn: 354,tp: 183,precision: 0.9015, recall: 0.3408, f1: 0.4946
for threshold: 0.9500, tn: 4542,fp: 10,fn: 381,tp: 156,precision: 0.9398, recall: 0.2905, f1: 0.4438
labels len: 5089
predictions len: 5089
```

### in_channels: 19 With normalization

```
[2025-05-09 17:35:17,500] [INFO] Loading pretrained weights from Hugging Face hub (timm/vgg16.tv_in1k)
[2025-05-09 17:35:17,758] [INFO] [timm/vgg16.tv_in1k] Safe alternative available for 'pytorch_model.bin' (as 'model.safetensors'). Loading weights using safetensors.
[2025-05-09 17:35:17,760] [INFO] Converted input conv features.0 pretrained weights from 3 to 19 channel(s)
[2025-05-09 17:35:18,093] [INFO]  contains5089 samples  537 pos
[2025-05-09 17:35:18,094] [INFO]  contains5089 samples
[2025-05-09 17:35:18,094] [INFO]  After filter contains5089 samples  537 pos
[2025-05-09 17:35:18,094] [INFO]  After filter contains5089 samples

val_ds: <torch.utils.data.dataloader.DataLoader object at 0x765c536159d0>

100%|██████████| 160/160 [00:02<00:00, 57.19it/s]
for threshold: 0.0500, tn: 3893,fp: 659,fn: 107,tp: 430,precision: 0.3949, recall: 0.8007, f1: 0.5289
for threshold: 0.1000, tn: 4199,fp: 353,fn: 172,tp: 365,precision: 0.5084, recall: 0.6797, f1: 0.5817
for threshold: 0.1500, tn: 4341,fp: 211,fn: 222,tp: 315,precision: 0.5989, recall: 0.5866, f1: 0.5927
for threshold: 0.2000, tn: 4414,fp: 138,fn: 248,tp: 289,precision: 0.6768, recall: 0.5382, f1: 0.5996
for threshold: 0.2500, tn: 4446,fp: 106,fn: 271,tp: 266,precision: 0.7151, recall: 0.4953, f1: 0.5853
for threshold: 0.3000, tn: 4474,fp: 78,fn: 294,tp: 243,precision: 0.7570, recall: 0.4525, f1: 0.5664
for threshold: 0.3500, tn: 4493,fp: 59,fn: 309,tp: 228,precision: 0.7944, recall: 0.4246, f1: 0.5534
for threshold: 0.4000, tn: 4504,fp: 48,fn: 323,tp: 214,precision: 0.8168, recall: 0.3985, f1: 0.5357
for threshold: 0.4500, tn: 4517,fp: 35,fn: 332,tp: 205,precision: 0.8542, recall: 0.3818, f1: 0.5277
for threshold: 0.5000, tn: 4526,fp: 26,fn: 341,tp: 196,precision: 0.8829, recall: 0.3650, f1: 0.5165
for threshold: 0.5500, tn: 4531,fp: 21,fn: 354,tp: 183,precision: 0.8971, recall: 0.3408, f1: 0.4939
for threshold: 0.6000, tn: 4534,fp: 18,fn: 364,tp: 173,precision: 0.9058, recall: 0.3222, f1: 0.4753
for threshold: 0.6500, tn: 4537,fp: 15,fn: 377,tp: 160,precision: 0.9143, recall: 0.2980, f1: 0.4494
for threshold: 0.7000, tn: 4543,fp: 9,fn: 385,tp: 152,precision: 0.9441, recall: 0.2831, f1: 0.4355
for threshold: 0.7500, tn: 4544,fp: 8,fn: 394,tp: 143,precision: 0.9470, recall: 0.2663, f1: 0.4157
for threshold: 0.8000, tn: 4544,fp: 8,fn: 404,tp: 133,precision: 0.9433, recall: 0.2477, f1: 0.3923
for threshold: 0.8500, tn: 4547,fp: 5,fn: 413,tp: 124,precision: 0.9612, recall: 0.2309, f1: 0.3724
for threshold: 0.9000, tn: 4548,fp: 4,fn: 428,tp: 109,precision: 0.9646, recall: 0.2030, f1: 0.3354
for threshold: 0.9500, tn: 4548,fp: 4,fn: 440,tp: 97,precision: 0.9604, recall: 0.1806, f1: 0.3041
labels len: 5089
predictions len: 5089
```








