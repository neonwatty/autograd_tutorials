# Tutorial notebooks illustrating `autograd` functionalities

This repo contains a set of Jupyter notebook describing how to use various [autograd](https://github.com/HIPS/autograd) functionalities including:

[basic functionalities] including 

- **computing derivatives using standard and lambda (anonymous) functions**

- **subtleties involved in automatic differentiation - in particular how evaluating a gradient gets you a function evaluation as well 'for free'**

- **computing individual partial derivatives of multi-input functions**

- **computing higher order partial derivatives of multi-input functions**

- **computing higher order Taylor series approximations**

- the [flatten_func](https://github.com/HIPS/autograd/blob/master/autograd/misc/flatten.py) function 

      
<img src="https://github.com/jermwatt/autograd_flatten_func_description/blob/master/flattening.png" width="425"/> 

This notebook was produced as supplementary material for the second edition of the textbook Machine Learning Refined, published Cambridge University Press, set for release in mid-2019.  You can find a host of examples employing `autograd` and - in particular - `flatten_func` on the main repository for the textbook [located here](https://github.com/jermwatt/mlrefined) (see for example the drafts on [multi-class classification](https://jermwatt.github.io/mlrefined/blog_posts/7_Linear_multiclass_classification/7_2_Perceptron.html) [fully connected networks](https://jermwatt.github.io/mlrefined/blog_posts/13_Multilayer_perceptrons/13_1_Multi_layer_perceptrons.html)).
