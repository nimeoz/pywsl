# pywsl: **py**thon codes for **w**eakly-**s**upervised **l**earning

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Build Status](https://travis-ci.org/t-sakai-kure/pywsl.svg?branch=master)](https://travis-ci.org/t-sakai-kure/pywsl)

This package contains the following implementation:
- ***Unbiased PU learning***  
  &nbsp;&nbsp;&nbsp; in "Convex formulation for learning from positive and unlabeled data", ICML, 2015 [[uPU]](#uPU)
- ***PU Set Kernel Classifier***  
  &nbsp;&nbsp;&nbsp; in "Convex formulation of multiple instance learning from positive and unlabeled bags", arXiv, 2017 [[PU-SKC]](#pu-skc)
- ***Class-prior estimation based on energy distance***  
  &nbsp;&nbsp;&nbsp; in "Computationally efficient class-prior estimation under class balance change using energy distance", IEICE-ED, 2016 [[CPE-ENE]](#cpe_ene).
- ***PNU classification***  
  &nbsp;&nbsp;&nbsp; in "Semi-supervised classification based on classification from positive and unlabeled data", ICML 2017 [[PNU]](#pnu_mr).
- ***PNU-AUC optimization***  
  &nbsp;&nbsp;&nbsp; in "Semi-supervised AUC optimization based on positive-unlabeled learning", MLJ 2018 [[PNU-AUC]](#pnu_auc).

## Contributors
- [Tomoya Sakai](https://t-sakai-kure.github.io)
- [Han Bao](http://levelfour.github.io)

## References
1. <a name="uPU"> du Plessis, M. C., Niu, G., & Sugiyama, M.   
  Convex formulation for learning from positive and unlabeled data.   
  In F. Bach and D. Blei (Eds.), Proceedings of 32nd International Conference on Machine Learning (ICML2015), 
  JMLR Workshop and Conference Proceedings, vol.37, pp.1386-1394, Lille, France, Jul. 6-11, 2015. 
1. <a name="pu-skc"> Bao, H., Sakai, T., Sato, I., Sugiyama, M.  
  Convex formulation of multiple instance learning from positive and unlabeled bags.  
  arXiv:1704.06767, 2017.
1. <a name="cpe_ene"> Kawakubo, H., du Plessis, M. C., & Sugiyama, M.  
  Computationally efficient class-prior estimation under class balance change using energy distance.   
  IEICE Transactions on Information and Systems, vol.E99-D, no.1, pp.176-186, 2016.
1. <a name="pnu_mr"> Sakai, T., du Plessis, M. C., Niu, G., & Sugiyama, M.   
  Semi-supervised classification based on classification from positive and unlabeled data.   
  In D. Precup and Y. W. Teh (Eds.), Proceedings of 34th International Conference on Machine Learning (ICML2017), Proceedings of Machine Learning Research, vol.70, pp.2998-3006, Sydney, Australia, Aug. 6-12, 2017.  
1. <a name="pnu_auc"> Sakai, T., Niu, G., & Sugiyama, M.   
  Semi-supervised AUC optimization based on positive-unlabeled learning.   
  Machine Learning, vol.107, no.4, pp.767-794, 2018.   
