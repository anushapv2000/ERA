# ERA
![image](https://github.com/anushapv2000/ERA/assets/71582463/30124ba7-afe2-47cf-963c-aa602845d10d)
</br>
## The above shown is a sample neural network inorder to showcase the steps for forward and backward propagation
## Forward Propagation steps:
![image](https://github.com/anushapv2000/ERA/assets/71582463/1880d764-5af4-4695-ad5b-0036244fed07)
</br>
### The above steps computes :
* weights multiplication for the nodes h1,h2 o1, o2
* activation output for h1,h2 o1, o2
* total value Etotal

## Backward Propagation
Here ,the deriavative all weights are computed and updated with respect to loss
eg: the weight5 with respect to loss is by finding derivative through chain process
* first E1 with a_o1 ,a_o1 with o1,o1 with w5
* ∂E_total/∂w5 = ∂E1/∂w5 = ∂E1/∂a_o1*∂a_o1/∂o1*∂o1/∂w5
* ∂E_total/∂w5 = (a_01 - t1) * a_o1 * (1 - a_o1) *  a_h1					
  </br>
  
![image](https://github.com/anushapv2000/ERA/assets/71582463/50b722a4-91fe-4cc4-aa1f-aceed335c6f3)
</br>
In the same way all the weights can be computed by the following steps
</br>
* ![image](https://github.com/anushapv2000/ERA/assets/71582463/0449cedd-1d40-4aba-bc2e-b15fb428e625)
* ![image](https://github.com/anushapv2000/ERA/assets/71582463/82b4598b-a944-4bf1-afb8-5da4f827d8e2)
* ![image](https://github.com/anushapv2000/ERA/assets/71582463/e4c89398-4d62-46ae-b40d-4b546673744a)



