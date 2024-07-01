import matplotlib.pyplot as plt
import numpy as np
x = np.array([5,7,8,9,4,5,6,1,2,3])
y = np.array([10,20,30,40,50,60,70,80,90,100])

plt.scatter(x,y)
plt.show()//////




import matplotlib.pyplot as plt
import numpy as np
x = np.array([5,7,8,9,4,5,6,1,2,3])
y = np.array([10,20,30,40,50,60,70,80,90,100])
sizes = np.array([20,30,40,50,60,70,80,90,40,5])

plt.scatter(x,y, s=sizes)
plt.show()
