# SufficientLineage

Authors: Shaobo Wang (sw1001@georgetown.edu), Chia-Hsuan Hsieh (ch1165@georgetown.edu), Chenyuan Wu(16221213@bjtu.edu.cn)

Advisor: Dr. Wenchao Zhou (wzhou@cs.georgetown.edu)
        
This algorithm is presented by [Re and Suciu](https://homes.cs.washington.edu/~suciu/paper220.pdf)

How to use:

1. Check out if you have opencl environment first. Run 'make' in the shell, and then run './query' to launch the program. 
2. Use './query --list' to see what opencl device you have on your platform, and Use'./query --device INDEX' to choose one device
(default device is of index 0).
3. the .cl files might need some changes in the definition if you change the datasets.


