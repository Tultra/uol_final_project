# University fo London - BSc Computer Science
## Final Project - Deep Learning on a Public Dataset template
### CNN Image Classification on the CIFAR-10 dataset

This code repository contain all Jupyter Notebooks created for Final Project of the BSc Computer Science degree coordinated by the University of London.

Best model is "Model J", with 86,34% accuracy. 

### Model comparison

| Models	 |Total layers	n.| epochs	n. | Dropouts	n.| Batch Regularization |	Accuracy (test set)|	Comments |
| -------- | -------------- | ---------- | ---------- | ------------------- | ------------------ | --------- |
| Baseline |	5           	|  4	       |  -         | 	-                 | 	60.46%	         |           |
|Model A|	7	|8|	-|	-|	65.52%	|Conv2d/MaxPool2D layers added|
|Model B|	10|	8	|3|	-|	64.37%	|Dropout layers added|
|Model C|	12|	16|	3	|-|	76.59%	|Conv2d layers added|
|Model D|	16|	16|	3	|4|	78.42%	|Batch Normalization added|
|Model E|	16|	32|	3	|4|	78.89%	|Reduce Dense Layer hidden units number|
|Model F|	22|	32|	4	|6|	81.26%	|Conv2D/BatchNormalization/MaxPooling/Dropout layers added|
|Model G|	23|	32|	4	|7|	83.06%	|Dropout values tweak (raised) / BatchNormalization added|
|Model H|	23|	64|	4|	7|	84.74%|	|
|Model I|	23|	100|	4|	7|	85.92%	|Dropout values tweak (raised)|
|Model J|	30|	100|	5|	9|	**86.34%**	|Conv2D/BatchNormalization/MaxPooling/Dropout/Dense layers added|
|Model K|	31|	100|	6|9|	86.26%|	Dropout values tweak (raised) / Dropout layer added|
|Model L|	37|	100|	7|	11|	85.53%	|Conv2D/BatchNormalization/MaxPooling/Dropout/Dense layers added. Dropout values tweak (raised)|
|Model M|	435|	50|	2|	multiple|	76.71%	||
