# multimedia-hw1" 
> Po-Yu, Wu
---

## 1. Color Quantization and Dithering 
- you can change `n`in `hw1_1.ipynb`
```javascript=
n = 3 #change to n=6 to show the different effect on color quantiation
```
- click `run_all` button on the top of the ipynb
- the result is stored in `.\out` directory
  - `{n}` varies according to n's definition. In this homework, n can be either 3 or 6, generating two type of color badges: $2^3$ and $2^6$ respectively
  - `median_cut{n}.png`, which stores the result of median cut. Note that the side product is the color badge
  - `error_diffusion_dithering_{n}.png`, which uses the color badge from the median cut with the help of the error diffusion
## 2. Interpolation
- you can cahgne `n` in `hw1_2.ipynb`
```javascript=
n = 3 #change n to change the interpolation ratio
```
- click `run_all` button on the top of the ipynb
- the result is stored in `.\out` directory
  - `bee_near.png`, which stores the nearest neighbor interpolation result
  - `bee_linear_.png`, which stores the bilinear interpolation result
## 3. Photo enhancement
- you can cahgne `gamma_value` in `hw1_3.ipynb`
```javascript=
gamma_value = 5 #change gamma value to find the best gamma value s.t. it has the best effect
```
- click `run_all` button on the top of the ipynb
- the result is stored in `.\out` directory
  - `gamma_img.png` stores the final transformed image which starts from rgb 2 yiq 2 gammaed yiq 2 rgb
  - `*_hisogram.png` stores the histograms.
    - original rgb histogram
    - yiq hisogram
    - gammaed hisogram
    - after yiq rgb histogram