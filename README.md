Total Parameters:  15112876
----------------------------------------------------------------
        Layer (type)               Output Shape         Param #
================================================================
            Conv2d-1         [-1, 32, 288, 288]             864
       BatchNorm2d-2         [-1, 32, 288, 288]              64
             ReLU6-3         [-1, 32, 288, 288]               0
            Conv2d-4         [-1, 32, 288, 288]             288
       BatchNorm2d-5         [-1, 32, 288, 288]              64
             ReLU6-6         [-1, 32, 288, 288]               0
            Conv2d-7         [-1, 64, 288, 288]           2,048
       BatchNorm2d-8         [-1, 64, 288, 288]             128
             ReLU6-9         [-1, 64, 288, 288]               0
           Conv2d-10         [-1, 64, 144, 144]             576
      BatchNorm2d-11         [-1, 64, 144, 144]             128
            ReLU6-12         [-1, 64, 144, 144]               0
           Conv2d-13        [-1, 128, 144, 144]           8,192
      BatchNorm2d-14        [-1, 128, 144, 144]             256
            ReLU6-15        [-1, 128, 144, 144]               0
           Conv2d-16        [-1, 128, 144, 144]           1,152
      BatchNorm2d-17        [-1, 128, 144, 144]             256
            ReLU6-18        [-1, 128, 144, 144]               0
           Conv2d-19        [-1, 128, 144, 144]          16,384
      BatchNorm2d-20        [-1, 128, 144, 144]             256
            ReLU6-21        [-1, 128, 144, 144]               0
           Conv2d-22          [-1, 128, 72, 72]           1,152
      BatchNorm2d-23          [-1, 128, 72, 72]             256
            ReLU6-24          [-1, 128, 72, 72]               0
           Conv2d-25          [-1, 256, 72, 72]          32,768
      BatchNorm2d-26          [-1, 256, 72, 72]             512
            ReLU6-27          [-1, 256, 72, 72]               0
           Conv2d-28          [-1, 256, 72, 72]           2,304
      BatchNorm2d-29          [-1, 256, 72, 72]             512
            ReLU6-30          [-1, 256, 72, 72]               0
           Conv2d-31          [-1, 256, 72, 72]          65,536
      BatchNorm2d-32          [-1, 256, 72, 72]             512
            ReLU6-33          [-1, 256, 72, 72]               0
           Conv2d-34          [-1, 256, 36, 36]           2,304
      BatchNorm2d-35          [-1, 256, 36, 36]             512
            ReLU6-36          [-1, 256, 36, 36]               0
           Conv2d-37          [-1, 512, 36, 36]         131,072
      BatchNorm2d-38          [-1, 512, 36, 36]           1,024
            ReLU6-39          [-1, 512, 36, 36]               0
           Conv2d-40          [-1, 512, 36, 36]           4,608
      BatchNorm2d-41          [-1, 512, 36, 36]           1,024
            ReLU6-42          [-1, 512, 36, 36]               0
           Conv2d-43          [-1, 512, 36, 36]         262,144
      BatchNorm2d-44          [-1, 512, 36, 36]           1,024
            ReLU6-45          [-1, 512, 36, 36]               0
           Conv2d-46          [-1, 512, 36, 36]           4,608
      BatchNorm2d-47          [-1, 512, 36, 36]           1,024
            ReLU6-48          [-1, 512, 36, 36]               0
           Conv2d-49          [-1, 512, 36, 36]         262,144
      BatchNorm2d-50          [-1, 512, 36, 36]           1,024
            ReLU6-51          [-1, 512, 36, 36]               0
           Conv2d-52          [-1, 512, 36, 36]           4,608
      BatchNorm2d-53          [-1, 512, 36, 36]           1,024
            ReLU6-54          [-1, 512, 36, 36]               0
           Conv2d-55          [-1, 512, 36, 36]         262,144
      BatchNorm2d-56          [-1, 512, 36, 36]           1,024
            ReLU6-57          [-1, 512, 36, 36]               0
           Conv2d-58          [-1, 512, 36, 36]           4,608
      BatchNorm2d-59          [-1, 512, 36, 36]           1,024
            ReLU6-60          [-1, 512, 36, 36]               0
           Conv2d-61          [-1, 512, 36, 36]         262,144
      BatchNorm2d-62          [-1, 512, 36, 36]           1,024
            ReLU6-63          [-1, 512, 36, 36]               0
           Conv2d-64          [-1, 512, 36, 36]           4,608
      BatchNorm2d-65          [-1, 512, 36, 36]           1,024
            ReLU6-66          [-1, 512, 36, 36]               0
           Conv2d-67          [-1, 512, 36, 36]         262,144
      BatchNorm2d-68          [-1, 512, 36, 36]           1,024
            ReLU6-69          [-1, 512, 36, 36]               0
           Conv2d-70          [-1, 512, 18, 18]           4,608
      BatchNorm2d-71          [-1, 512, 18, 18]           1,024
            ReLU6-72          [-1, 512, 18, 18]               0
           Conv2d-73         [-1, 1024, 18, 18]         524,288
      BatchNorm2d-74         [-1, 1024, 18, 18]           2,048
            ReLU6-75         [-1, 1024, 18, 18]               0
           Conv2d-76         [-1, 1024, 18, 18]           9,216
      BatchNorm2d-77         [-1, 1024, 18, 18]           2,048
            ReLU6-78         [-1, 1024, 18, 18]               0
           Conv2d-79         [-1, 1024, 18, 18]       1,048,576
      BatchNorm2d-80         [-1, 1024, 18, 18]           2,048
            ReLU6-81         [-1, 1024, 18, 18]               0
        mobilenet-82  [[-1, 256, 72, 72], [-1, 512, 36, 36], [-1, 1024, 18, 18]]               0
         Upsample-83         [-1, 1024, 36, 36]               0
           Conv2d-84          [-1, 512, 36, 36]       4,719,104
      BatchNorm2d-85          [-1, 512, 36, 36]           1,024
             ReLU-86          [-1, 512, 36, 36]               0
           Conv2d-87          [-1, 512, 36, 36]       2,359,808
      BatchNorm2d-88          [-1, 512, 36, 36]           1,024
             ReLU-89          [-1, 512, 36, 36]               0
       DoubleConv-90          [-1, 512, 36, 36]               0
         Upsample-91         [-1, 1024, 72, 72]               0
           Conv2d-92          [-1, 256, 72, 72]       2,359,552
      BatchNorm2d-93          [-1, 256, 72, 72]             512
             ReLU-94          [-1, 256, 72, 72]               0
           Conv2d-95          [-1, 256, 72, 72]         590,080
      BatchNorm2d-96          [-1, 256, 72, 72]             512
             ReLU-97          [-1, 256, 72, 72]               0
       DoubleConv-98          [-1, 256, 72, 72]               0
         Upsample-99        [-1, 512, 144, 144]               0
          Conv2d-100        [-1, 128, 144, 144]         589,952
     BatchNorm2d-101        [-1, 128, 144, 144]             256
            ReLU-102        [-1, 128, 144, 144]               0
          Conv2d-103        [-1, 128, 144, 144]         147,584
     BatchNorm2d-104        [-1, 128, 144, 144]             256
            ReLU-105        [-1, 128, 144, 144]               0
      DoubleConv-106        [-1, 128, 144, 144]               0
        Upsample-107        [-1, 128, 288, 288]               0
          Conv2d-108         [-1, 64, 288, 288]          73,792
     BatchNorm2d-109         [-1, 64, 288, 288]             128
            ReLU-110         [-1, 64, 288, 288]               0
          Conv2d-111         [-1, 64, 288, 288]          36,928
     BatchNorm2d-112         [-1, 64, 288, 288]             128
            ReLU-113         [-1, 64, 288, 288]               0
      DoubleConv-114         [-1, 64, 288, 288]               0
          Conv2d-115          [-1, 4, 288, 288]             260
================================================================
Total params: 14,087,876
Trainable params: 14,087,876
Non-trainable params: 0
----------------------------------------------------------------
Input size (MB): 0.95
Forward/backward pass size (MB): 1509.89
Params size (MB): 53.74
Estimated Total Size (MB): 1564.58
----------------------------------------------------------------
