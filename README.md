multimedia-hw1" 
===
> by 108062138 Po-Yu, Wu
> Readme.md contains only the *execution* part in `report.pdf`
---
## *0. HACKMD REPORT LINK*
[HACKMD LINK](https://hackmd.io/@sBeNJ4fqRNqa67PhyWWV4A/HJtm95gb2)
## *1. Color Quantization and Dithering*
### execution
- go to `1.ipynb`
- Please adjust `n` to customize the color badges. In this assignment, `n` can be either 3 or 6, generating the color badges with `2^3` and `2^6` respectively.
- click `Run all` to see the output(`{n}` varies according to `n`'s definition)
- output locates at `./out/` folder
  - `error_diffusion_dithering_{n}.png`
  - `median_cut{n}.png`
- To verify the implementation's correctness, I construct `test_color` to verify that each pixel is limited inside the color badge.
  
## *2. Interpolation*
### execution
- go to `2.ipynb`
- Please adjust `n` to customize the interpolation ratio. In this assignment, `n` is 4.
- click `Run all` to see the output
- output locates at `./out/` folder
  - `bee_near.jpg`
  - `bee_linear.jpg`
## *3. Photo enhancement*
### execution
- go to `3.ipynb`
- Please adjust `gamma_value` to customize the interpolation ratio. In this assignment, `gamma_value` is 5
- click `Run all` to see the output
- output locates at `./out/` folder
  - `Y_hist.jpg`
  - `Y_hist_gamma.jpg`
  - `gamma_img.jpg`