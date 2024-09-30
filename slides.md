
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
__data__  
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
__data__  
x: input  
y: output  
  
__model__  
line     
y = mx + b
  
__parameters__   
m (slope)  
b (intercept)  
]

__training the model__ 
finding the best parameters - 
minimizing a loss function

]


---

### Linear regression


.split-60[

.column[
<img src="pix/linear_regression_2.jpg" width="90%"/>
]

.column[
__data__  
x: input  
y: output  
  
__model__  
line     
y = mx + b
  
__parameters__   
m (slope)  
b (intercept)  
]

__training the model__ 
finding the best parameters - 
minimizing a loss function

__overfitting__  
too many parameters

]

---

### Training the model



.split-60[

.column[
<img src="pix/gradient_descent.png" width="90%"/>
]

.column[

Train the model  

= find the best parameters  

= minimize a loss function

<br/>
<br/>


Gradient Descent

- input training data

- compare to known output, calculate gradient

- adjust parameters in the direction of the gradient


]

]


_


