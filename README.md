# Image and Text fusion for UPMC Food-101 using BERT and CNNs
The  modern  digital  world  is  becoming  more  andmore  multimodal.  Looking  on  the  internet,  images  are  oftenassociated  with  the  text,  so  classification  problems  with  thesetwo  modalities  are  very  common.  In  this  paper,  we  examinemultimodal  classification  using  textual  information  and  visualrepresentations  of  the  same  concept.  We  investigate  two  mainbasic methods to perform multimodal fusion and adapt them withstacking techniques to better handle this type of problem. Here,we use UPMC Food-101, which is a difficult and noisy multimodaldataset that well represents this category of multimodal problems.Our   results   show   that   the   proposed   early   fusion   techniquecombined  with  a  stacking-based  approach  exceeds  the  state  ofthe  art  on the  dataset used.

## Usage
Use Jupyter notebook.

## Dataset
The used dataset is [UPMC Food-101](http://visiir.lip6.fr/explore) a very difficult dataset.

## Results
| Method | Accuracy(%) |
| ---      |  ------  |
| Image (InceptionV3)   | 71.67 | 
| Text (Bert) | 84.41 | 
| Late fusion   | 84.59 | 
| Early fusion   | 92.50 | 

## Citation
```
@INPROCEEDINGS{Gallo:2020:IVCNZ, 
  author={Gallo, Ignazio and Ria, Gianmarco, Landro, Nicola and La Grassa, Riccardo},
  booktitle={2020 International Conference on Image and Vision Computing New Zealand (IVCNZ 2020)}, 
  title={Image and Text fusion for UPMC Food-101 using BERT and CNNs},
  year={2020}, 
  month={Dec},
}
```

## References
[1] [Proposed Model](http://artelab.dista.uninsubria.it/res/research/papers/2020/2020-IVCNZ-Gallo-Food101.pdf)

