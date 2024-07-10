# The implementation of DNCNN and Color Constancy Model
This is my implementation of DNCNN and Color Constancy Model to improve their performance
1. DNCNN
My implementation of DNCNN reaches 32.25dB when testing with test sets, a huge improvement from 26.24dB. Below is an example image.

| `<Noisy>`  | `<Denoised>`|
|------------|----------------|
|<img src="https://github.com/kimhyeonejun/DNCNN-and-Color-Constancy-Model/assets/103301952/eea74a1f-0653-4e7b-9dca-79c377394964" alt="다운로드" width="300" height="300">|<img src="https://github.com/kimhyeonejun/DNCNN-and-Color-Constancy-Model/assets/103301952/71d55989-44f5-43a9-af4b-508fc63eb2a2" alt="0802x2" width="300" height="300">|
| Noisy image | PSNR: 32.69dB |

2. FC4
My implementation of FC4 reaches a 13.48 AE on average when tested with test sets, a huge improvement from a 16.72 AE. Below is an example image.

| `<Color distorted>`  | `<Restored>`   |
|------------|----------------|
|![image](https://github.com/kimhyeonejun/DNCNN-and-Color-Constancy-Model/assets/103301952/52a35fef-4401-4213-86f4-d093bcec6235)|![image](https://github.com/kimhyeonejun/DNCNN-and-Color-Constancy-Model/assets/103301952/34d33c44-d837-4e74-8385-0902afb1caa4)|
| Distorted with green | AE : 1.365 |
