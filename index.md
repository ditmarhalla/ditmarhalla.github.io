---
layout: default
---




### Languages

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="50" height="50"/><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/matlab/matlab-original.svg" alt="Matlab" width="50" height="50"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/r/r-original.svg" alt="R" width="50" height="50"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-line.svg" alt="cpp" width="50" height="50"/>

### Technologies

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/numpy/numpy-original.svg" alt="Numpy" width="50" height="50"/><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original-wordmark.svg" alt="Pandas" width="50" height="50"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/raspberrypi/raspberrypi-original.svg" alt="Raspberry-Pi" width="50" height="50"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="Linux" width="50" height="50"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bash/bash-original.svg" alt="Bash" width="50" height="50"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL" width="50" height="50"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" alt="git" width="50" height="50"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/github/github-original.svg" alt="GitHub" width="50" height="50"/>

### Tools

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vim/vim-original.svg" alt="VIM" width="50" height="50"/><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vscode/vscode-original.svg" alt="VSCode" width="50" height="50"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jupyter/jupyter-original.svg" alt="Jupyter" width="50" height="50"/>

---


I am an Applied Mathematics student. My interests are vast. From computer vision and image processing, to more hardware related projects like using a raspbery pi. I mostly use Python, as that is the language I have the most proficiency in. But I am trying to learn C++, since I like to have knowledge in a language that is close to the hardware and also fast when I need it.

Currently I am working as a research assistant with one of my professors at the university in High Performance Computing (HPC) for simulations. My work consists in running simulations for fluid dynamics using Linux and some Shell scripting in order to automate the tasks. Feel free to check my [GitHub](https://github.com/ditmarhalla) to see what project I am working on.

One of my hobbys is also rugby. I used to practice the sport back in Tirana, Albania and to help the team I managed the Instagram account of the [Tirana Rugby Club](https://www.instagram.com/tirana.rugby.club/) untill recently. One of the things I am proud of is during the time I managed the Instagram we gained 1900 followers, from 200 followers to 2100. I used Gimp and Adobe to create posters and edit pictures which I enjoyed and also learned a lot from. As a way to help the team I also created two websites using Wordpress. [K.R. Tirana](https://krtirana.wordpress.com/) and [Albania R.L.](albaniarl.wordpress.com). It was a simple task using wordpress. All in all I am happy that I "wasted" my time as I learned a lot creating the websites, creating and managing content for Instagram page and learning tricks on the way.


### [Clasification Project (Python + NumPy)](https://github.com/ditmarhalla/Clasification-Project-)

```python
from nearest_neighbor import Nearest_Neighbour
import numpy as np
import time 


print("The program has started calculating the class of the untrained vectors")
print ("-"*100)

start = time.time()
#root
trained_data ='\trained.txt'
untraiend_data = '\untrained.txt'

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

    
