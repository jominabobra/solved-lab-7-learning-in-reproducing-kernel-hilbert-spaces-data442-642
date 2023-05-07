Download Link: https://assignmentchef.com/product/solved-lab-7-learning-in-reproducing-kernel-hilbert-spaces-data442-642
<br>
<strong>Exercise 1</strong>

For this exercise, the performance of the SVM is tested in the context of a two-class twodimensional classification task. The data set comprises <em>N </em>= 150 points uniformly distributed in the region [−5<em>,</em>5] × [−5<em>,</em>5]. For each point <em>x<sub>n </sub></em>= [<em>x<sub>n,</sub></em><sub>1</sub><em>,x<sub>n,</sub></em><sub>2</sub>]<sup>&gt;</sup>, we compute

where <em>η </em>stands for zero mean Gaussian noise of variance = 4. The point is assigned to either of the two classes, depending on the value of the noise as well as its position with respect to the graph of the function

<em>f</em>(<em>x</em>) = 0<em>.</em>05<em>x</em><sup>3 </sup>+ 0<em>.</em>05<em>x</em><sup>2 </sup>+ 0<em>.</em>05<em>x </em>+ 0<em>.</em>05

in the two-dimensional space. That is, if <em>x<sub>n,</sub></em><sub>2 </sub>≥ <em>y<sub>n</sub></em>, the point is assigned to class <em>ω</em><sub>1</sub>; otherwise, it is assigned to class <em>ω</em><sub>2</sub>.

<ul>

 <li>Plot the points [<em>x<sub>n,</sub></em><sub>1</sub><em>,x<sub>n,</sub></em><sub>2</sub>] using different colors for each class.</li>

 <li>Use SVM with the Gaussian kernel for <em>σ </em>= 20 and set <em>C </em>= 1. Plot the classifier and the margin. Moreover, find the support vectors (i.e., the points with nonzero Lagrange multipliers that contribute to the expansion of the classifier) and plot them as circled points.</li>

 <li>Repeat step (b) using <em>C </em>= 0<em>.</em>5<em>,</em>0<em>.</em>1<em>,</em>0<em>.</em></li>

 <li>Repeat step (b) using <em>C </em>= 5<em>,</em>10<em>,</em>50<em>,</em></li>

 <li>Comment on the results.</li>

</ul>