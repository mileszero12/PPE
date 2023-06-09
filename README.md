# PPE

## Read data: 
Create an instance of the `PPE()` class named "ppe" by passing the filename and the argument set to True. This indicates that the setup fee should be considered. Alternatively, setting the argument to False will exclude the consideration of setup fees.
      
## N95 mask setup fee (Deterministic)
Invoke the function `backward()` with the argument set to True, which indicates that the result should be printed using N95 production seasons. Alternatively, setting the argument to False will display the result based on time stages.

## Surgical mask setup fee (Deterministic)
Invoke the `backward()` method to obtain the solution considering only the N95 mask setup fee. Following this, invoke the `backward2()` method to further develop an optimal solution based on the obtained results.

## N95 mask setup fee (Stochastic)
In the context of considering two scenarios, namely low demand and high demand, we instantiate an object of the `StoPPE()` class named "sto_ppe" by providing the filename and setting the argument to True. Subsequently, we invoke the `Stochastic()` function.
