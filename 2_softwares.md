---
layout: page
title: Code
permalink: /softwares/
---
## [F-image](https://github.com/zhoupc/F-image)
[GitHub](https://github.com/zhoupc/F-image)
**F-image** is a package management system used to install and manage software packages written for functional image analysis. With F-image, you can install and use a package like this. 
```matlab 
fi.install('cnmfe');   # install CNMF-E 
fi.usepkg('cnmfe');    # use CNMF-E functions in your code. 
```

F-image has a community-curated list of packages used in functional image analysis. Once the package is added to the list, you can use the above function to manage your package. Check the [GitHub repo](https://github.com/zhoupc/F-image) for details. 

## CNMF_E 
[GitHub](https://github.com/zhoupc/CNMF_E); [Slack](https://beat-ica.slack.com)

Constrained Nonnegative Matrix Factorization for microEndoscopic data. 'E' also suggests 'extension'. It is build on top of [CNMF](https://github.com/epnev/ca_source_extraction) with supports to 1 photon data. 

**install with F-image**
```matlab
>> fi.install('cnmfe')
```

## OASIS 
[**GitHub**](https://github.com/zhoupc/OASIS_matlab)

Fast online deconvolution of calcium imaging. The package was initially developed to run OASIS algorithms for fast spike inference. Later I integrated other deconvolution algorithms as well and run deconvolution using a unified function *deconvolveCa*. The users can easily try different algorithms by properly setting the options.

**install with F-image**
```matlab
>> fi.install('oasis')
```

