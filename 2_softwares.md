---
layout: page
title: Code
permalink: /softwares/
---
All my software packages can be found on my [GitHub page](https://github.com/zhoupc). Here are some selected packages. 
#### 1. F-image
A package management system used to install and manage software packages in MATLAB. [GitHub](https://github.com/zhoupc/F-image). 

F-image has a community-curated list of packages used in functional image analysis. Once the package is added to the list, you can install and use a package like this: 
```matlab 
fi.install('cnmfe');   % install CNMF-E 
fi.usepkg('cnmfe');    % use CNMF-E functions in your code. 
```
Check the [GitHub repo](https://github.com/zhoupc/F-image) for details.  

#### 2. CNMF-E 
Constrained Nonnegative Matrix Factorization for microEndoscopic data. 'E' also suggests 'extension'. It is build on top of [CNMF](https://github.com/epnev/ca_source_extraction) with supports to 1 photon data. [GitHub](https://github.com/zhoupc/CNMF_E); [Slack](https://beat-ica.slack.com)

**install with F-image**

```matlab
>> fi.install('cnmfe')
```

#### 3. OASIS 
Fast online deconvolution of calcium imaging. The package was initially developed to run OASIS algorithms for fast spike inference. Later I integrated other deconvolution algorithms as well and run deconvolution using a unified function *deconvolveCa*. The users can easily try different algorithms by properly setting the options. [GitHub](https://github.com/zhoupc/OASIS_matlab) 

**install with F-image**

```matlab
>> fi.install('oasis')
```

#### 4. EASE: EM-Assisted Sources Extraction.
EASE is a toolbox for fusing calcium imaging data and densely reconstructed Electron Microscopy (EM) segments. [Github](https://github.com/zhoupc/ease)

**install with F-image**
```matlab
>> fi.install('ease')
```
(check the github page to install extra softwares for finishing the configurations)
