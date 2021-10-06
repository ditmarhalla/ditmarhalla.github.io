---
layout: default
---


I am an Applied Mathematics student. My interests are vast. From computer vision and image processing, to more hardware related projects like using a raspbery pi. I mostly use Python, as that is the language I have the most proficiency in. But I am trying to learn C++, since I like to have knowledge in a language that is close to the hardware and also fast when I need it.

Currently I am working as a research assistant with one of my professors at the university in High Performance Computing (HPC) for simulations. My work consists in running simulations for fluid dynamics using Linux and some Shell scripting in order to automate the tasks. Feel free to check my [GitHub](https://github.com/ditmarhalla) to see what project I am working on.


### [Clasification Project (Python + NumPy)](https://github.com/ditmarhalla/Clasification-Project-)

```python
from nearest_neighbor import Nearest_Neighbour
import numpy as np
import time 


print("The program has started calculating the class of the untrained vectors")
print ("-"*100)

start = time.time()
#root
trained_data ='C:\\Users\\Ditmar\\Desktop\\University\\2 Semester\\Introduction to Programing\\Clasification-Project-\\trained.txt'
untraiend_data = 'C:\\Users\\Ditmar\\Desktop\\University\\2 Semester\\Introduction to Programing\\Clasification-Project-\\untrained.txt'

#Load the data
trained_file = np.loadtxt(trained_data,dtype=np.float16)
untrained_file= np.loadtxt(untraiend_data,dtype=np.float16)
time_data_load = time.time()
print("Time it takes to load the data",round(time_data_load - start,1)," seconds")

#Classifie the data
time_start_classifie = time.time()

run = len(untrained_file) - 1
for i in range(run):
    classification = Nearest_Neighbour(trained_file,untrained_file[run])

classification.distance()

time_end_classifie = time.time()
print("Time it takes to load the data",round(time_end_classifie -time_start_classifie,5)," seconds")
print(" ","-"*29)
print("| The program is done runnign  |")
print(" ","-"*29)
```

### [Numerical Mathematics (Matlab)](https://github.com/ditmarhalla/numerical_mathematics)

![Matlab](https://raw.githubusercontent.com/ditmarhalla/numerical_mathematics/main/fig2.jpg)



### [Sunspot Detection (Python + cv2 )](https://github.com/ditmarhalla/astronomy/tree/main/sunspot_detection)
![Sunspot_detection](https://raw.githubusercontent.com/ditmarhalla/astronomy/main/sunspot_detection/Finish.png)

    
