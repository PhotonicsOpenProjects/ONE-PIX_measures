# ONE-PIX measure 

This repository contains measurement samples taken with the ONE-PIX kit. Several unconventional imaging techniques were used to construct this database.
Each data can be loaded with the functions from the ONE-PIX repository. 

## Content 

Each ONE-PIX measurements contained in this repository are listed in the table below:

### Classical HSPI folder 

<p align="center">
<img src="img/classical_hspi.png" alt="ONE-PIX principle" width="500"/>
</p>


|Measure name|Scene description|Use case |Spatial resolution (pix²)|Pattern basis|
|---|---|---|---|---|
|Ammonite_fossil|Hypercube of an ammonite fossil|Paleontology|101x101|Fourier split|
|Bonzai_NIR|Hypercube of a bonsai acquired over a widened spectral range allowing the red edge to be seen|life science|61x61|Fourier split|
|Color_addition|Hypercube of a sheet of A4 paper with a print of the additive synthesis rosette.|Colorimetry,hyperspectral segmentation|31x31|Fourier split|
|Colored_squares|Hypercube of colored squares printed on paper glued to a gray carpet|colorimetry,Hyperspectral segmentation|101x101|Fourier split|
|Squash_leaf|Squash leaf maintained with green and blue bugs having areas of necrosis and chlorosis.|Life science agronomy|101x101|Fourier split|

### HAS measure 

|Measure name|Scene description|Use case |segmentation method|
|---|---|---|---|
|Chlorophytum_comosum| HAS measure of a spider plant (Chlorophytum_comosum)|Life science agronomy|kmeans segmentation|
|Nicotiana_tabacum| HAS measure of a tobacco plant (Nicotiana_tabacum) with a upper view and a sgementation of each leaves|Life science agronomy|manual segmentation|
|the_black_island| HAS measure of book cover of the famous black island adventure of tintin by Hergé. |color analysis art analysis|manual segmentation|


### Spyrit :

|Measure name|Scene description|Use case |Spatial resolution (pix²)|Pattern basis|
|---|---|---|---|---|
|Colored_squares (linear_reconstruction)|Hypercube of colored squares printed on paper glued to a gray carpet with linear reconstruction|colorimetry,Hyperspectral segmentation|32x32|Walsh Hadamard split|
|Colored_squares (spyrit_reconstruction)|same measure than linear reconstruction but with CNN reconstruction|deeplearning|64x64|Walsh Hadamard split acquisition and CNN reconstruction|

