%
% A-SPN: Attention-Based Second-Order Pooling Network for Hyperspectral Image Classification DEMO.
%        Version: 1.0
%        Date   : May 2021
%
%    This demo shows the A-SPN model for hyperspectral image classification.
%
%    main.py ....... A main script executing experiments upon IP, PU, and HU data sets.
%    data.py ....... A script implementing various data manipulation functions.
%    function.py ....... A script implementing the training function, the test function, and etc.
%    model.py ....... A script implementing the SPN and A-SPN models.
%    secondpooling.py ....... A script implementing the Second Order Pooling Operator, namely, SOP.
%    spatialattention.py ....... A script implementing the Attention-based SOP, namely, A-SOP.
% 
%    /Dataset ............... The folder including the IP, PU, and HU data sets, where "DS" represents spatially disjoint.
%    /temp_vars ............... The folder storing temporary results of PCA preprocessing.
%    /logs ............... The folder containing a script guiding to TensorBoard usage.
%
%   --------------------------------------
%   Note: Required core python libraries
%   --------------------------------------
%   1. python 3.6.5
%   2. tensorflow-gpu 1.14.0
%   3. tensorboard 1.14.0
%   4. Keras 2.2.5
%   5. opencv-python 4.4.0.46
%   6. h5py 2.10.0
%   7. matplotlib 3.3.0
%   8. numpy 1.19.4
%   9. scipy 1.5.4
%   --------------------------------------
%   Cite:
%   --------------------------------------
%
%   [1] Z. Xue, M. Zhang, Y. Liu and P. Du, "Attention-Based Second-Order Pooling Network for Hyperspectral Image Classification," in IEEE Transactions on Geoscience and Remote Sensing, doi: 10.1109/TGRS.2020.3048128.
%
%   --------------------------------------
%   Copyright & Disclaimer
%   --------------------------------------
%
%   The programs contained in this package are granted free of charge for
%   research and education purposes only. 
%
%   Copyright (c) 2021 by Zhaohui Xue & Mengxue Zhang
%   zhaohui.xue@hhu.edu.cn & mengxue_zhang@hhu.edu.cn
%   --------------------------------------
%   For full package:
%   --------------------------------------
%   https://sites.google.com/site/zhaohuixuers/
