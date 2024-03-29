# GYRO: Gimbal Yaw motion Real-wOrld (GYRO) dataset

Dataset proposed in "Real-time Large-motion Deblurring for Gimbal-based imaging systems", IEEE Journal of Selected Topics in Signal Processing, 2024.

## Summary of GYRO
1. GYRO is captured by a camera mounted on a gimbal where the gimbal undergoes to-and-fro rotational yaw motion. The gimbal is equipped with a gyroscope that measures the angular velocity,
known as steering rate (SR) in angles per second.
1. Using the gimbal setup with different steering rates of 1, 10, 20, 30, 40, 50, and 60 deg/sec, we captured RGB videos using Sony FCB-EX980S/P camera from two geographical areas and IR videos using a customized surveillance sight camera from three different geographical areas with 30 fps.
1. GYRO contains two real RGB sets (DRGB1 and DRGB2), and three real IR sets (DIR1, DIR2, and DIR3). DIR1 contains IR scenes of some buildings and a tower placed against a mountainous backdrop. DIR2 and DRGB1 contain scenes of an urban setting with multiple houses in IR, and RGB domains, respectively. DIR3 and DRGB2 have views of a hilly terrain.

Sample frames from each set and the statistics of GYRO dataset are given below. 

![GYRO (3)](https://github.com/nishavarghese15/GYRO/assets/93310210/0d85df17-88ce-4ef7-9084-487baafd44a1)


![GYRO (4)](https://github.com/nishavarghese15/GYRO/assets/93310210/41860fe4-765f-4c47-933b-95c7ded216bc)



## How to access the Dataset?
1. Read the GYRO release agreement: https://drive.google.com/file/d/1BFJ2ZuvKvVxH-nuu8qyyjkBt-GitW-LE/view?usp=sharing  
1. Obtain a signed copy of the above agreement form.   
1. Enter your details in the request form. [link](https://docs.google.com/forms/d/e/1FAIpQLSdbuVsnn1QXPg-OhKYEs0RRNZFY2zvDF_ds51I37nzMkaIxMg/viewform?usp=sf_link)
1. Upload the agreement as part of the request form.

After you submit the request form, you will receive an e-mail notification (within 5 working days) with the link to download the dataset.

## Acknowledgement
Support from IRDE CARS project (No: RB2021EE206IRDE005001) is gratefully acknowledged.

## Cite Us
If you use GYRO, please cite the following work:
```
@InProceedings{GRNet,
    author    = {Varghese, Nisha and Rajagopalan, A. N. and Ansari, Zahir Ahmed},
    title     = {Real-time Large-motion Deblurring for Gimbal-based imaging systems},
    booktitle = {IEEE Journal of Selected Topics in Signal Processing},
    vol ={ }
    year      = {2024},
    pages     = {}
}
```
