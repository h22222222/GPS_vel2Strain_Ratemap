# Surface_vel2Strain_Ratemap
**Obtain surface strain rate by sparse GPS velocity observations, including the estimated strain-rate tensors and rotation-rate tensors.**
## Supported strain method

Bsaed on the multi-scale wavelet-based matlab program from Tape et al. (2009).  (see https://github.com/carltape/surfacevel2strain for more details.)

Needs a matlab installation and some manual run steps.

note: I have made some adjustment in the program to reduce some manual run steps, if you have the requirement for other input parameters, you can remove the 
## usages

user_path.m: change it to your user path first.

surfacevel2strain.m：main program

surfacevel2strain_figs: visualize the results.
## Example

I have provided the example input in the package as: GPS_velo_menggu_forstrain.txt, you can try it.

Some results are as follows:

![strain and rotation results for Mongolia](https://user-images.githubusercontent.com/33387040/167244244-a158020d-36e2-4dbb-a16f-25b4e3e5aaef.png)

## Contributing
If you're using this library or have suggestions, let me know! I'm happy to work together on the code and its applications.

## Citing
If you use this library in your research, you can cite this repository as follows:

He, Y., T. Wang, L. Fang, and L. Zhao (2021). The 2020 Mw 6.0 Jiashi Earthquake: Coinvolvement of Thin-Skinned Thrusting and Basement Shortening in Shaping the Keping-Tage Fold-and-Thrust Belt in Southwestern TianShan, Seismol. Res. Lett. 93, 680–692, doi: 10.1785/0220210063.
