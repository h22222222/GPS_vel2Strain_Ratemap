# Surface_vel2Strain_Ratemap
**Obtain surface strain rate by sparse GPS velocity observations, including the estimated strain-rate tensors and rotation-rate tensors.**
## Supported strain method

Bsaed on the multi-scale wavelet-based matlab program from Tape et al. (2009).  (see https://github.com/carltape/surfacevel2strain for more details.)

Needs a matlab installation and some manual run steps.

note: I have made some adjustment in the program to reduce some manual run steps, if you have the requirement for other input parameters, you can remove the 
## Illustrations

user_path.m: change it to your user path first.

surfacevel2strain.m：main program

surfacevel2strain_figs: visualize the results.
## Example

I have provided the example input in the package as: GPS_velo_menggu_forstrain.txt, which is the observations in Mongolia during 1997-2003 from Calais et al.（2003）, you can try it.

Some results are as follows:

![strain and rotation results for Mongolia](https://user-images.githubusercontent.com/33387040/167244244-a158020d-36e2-4dbb-a16f-25b4e3e5aaef.png)

## Contact
If you're using this library or have questions, let me know! I'm happy to work together on the code and its applications.

## References
> Tape, C., Musé, P., Simons, M., Dong, D., & Webb, F. (2009). Multiscale estimation of GPS velocity fields. Geophysical Journal International, 179(2), 945-971. 
> 
> 苏小宁,孟国杰,王振. 基于多尺度球面小波解算GPS应变场的方法及应用[J]. 地球物理学报,2016,59(5):1585-1595. DOI:10.6038/cjg20160504．
> 
> 高涵,张明,秦姗兰,等. 基于多尺度球面小波分析云南地区应变特征[J]. 大地测量与地球动力学,2018,38(12):1232-1237. DOI:10.14075/j.jgg.2018.12.004.
