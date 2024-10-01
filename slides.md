
.center[

<br/>
<br/>
<br/>
<br/>


## A Deeper Dive into AI

<br/>
<br/>
<br/>
<br/>



Darren Kessner  
Marlborough School   
Educator Workshop  
October 4, 2024  

<br/>
<br/>

[dkessner.github.io/ai_pd_2024](http://dkessner.github.io/ai_pd_2024)  


]

---

### Linear regression


.split-60[

.column[
<img src="pix/linear_regression_0.jpg" width="90%"/>
]
.column[
__Data__  
x: input  
y: output  
]

]



---

### Linear regression

.split-60[

.column[
<img src="pix/linear_regression_1.jpg" width="90%"/>
]

.column[
__Data__  
x: input  
y: output  
  
__Model__  
line     
y = mx + b
  
__Parameters__   
m (slope)  
b (intercept)  

__Training / Learning__ 
finding the best parameters - 
minimizing a loss function

]
]


---

### Linear regression


.split-60[

.column[
<img src="pix/linear_regression_2.jpg" width="90%"/>
]

.column[
__Data__  
x: input  
y: output  
  
__Model__  
line     
y = mx + b
  
__Parameters__   
m (slope)  
b (intercept)  

__Training / Learning__ 
finding the best parameters - 
minimizing a loss function

__Overfitting__  
using too many parameters

]
]

---

### Training the model

.split-50[

.column[
<img src="pix/gradient_descent.png" width="90%"/>
]

.column[
__Train the model__  

&nbsp; = learn from data

&nbsp; = find best parameters  

&nbsp; = minimize loss function  

<br/>

__Gradient Descent__  

- give training data to model as input

- calculate gradient of loss function

- adjust parameters in the direction of the gradient

]
]


---

### Neural networks

.split-60[

.column[
<img src="pix/neuron.png" width="80%"/>
<br/>
<br/>
<img src="pix/artificial_neuron.png" width="80%"/>
]

.column[
<br/>
<img src="pix/neural_network.png" width="100%"/>
]
]


---

### Neural networks 


.center[

<img src="pix/neural_network_composition.ppm" width="70%"/>

<br/>

__Neural network__   
composition of functions   
(linear transformations / matrix multiplication)

<br/>

__Backpropagation algorithm__  
calculation of gradient   
(chain rule)  

]


---

### Cosine similarity

.center[
<img src="pix/cosine.png" width="60%"/>
]

$$
\cos \theta = \dfrac{u \cdot v}{|u||v|}
$$



---

### Semantic embedding

.split-60[

.column[
<img src="pix/word_vectors.jpg" width="90%"/>
]

.column[
__Embedding__  

mapping of words to vectors in a high-dimensional vector space

<br/>

__Semantic similarity__   

words with the same meaning have a higher
cosine similarity (shorter distance)

]

]






