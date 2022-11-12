# nyu-hpc-guide

### Request for HPC account

### 

### Preliminaries. 
This is a list of things that can help you understand/work with the hpc better. (No need to be an expert, but some basic knowledge will be super helpful)

- if you don't know what is conda (Anaconda) and pip, please do some google search to have a basic understanding. And you should have conda installed on your machine. 
- What is virtualenv: 
https://www.youtube.com/watch?v=mIB7IZFCE_k&t=458s  (video on conda virutal env, 10min)
https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html 
You should understand the basic concept of a virtual environment, how to create one and why we use it. Please watch the video and read the conda manage environment page. 
To test your skills, you should actually try to create and use a conda environment, to feel how it works. (there are different ways of using a virutalenv, in our case, we will use conda to create and manage python virtual environments)

- Git basics (32min) 
https://www.youtube.com/watch?v=SWYqp7iY_Tc
Watch the video or find some other git tutorials online. You should know some basics about git, in particularly, you should know well what is git pull, push, and commit, and you should have some understanding of what are issues, merge, pull request, etc. To test your skills, you should try to create a git repo and then push a few commits. Even better, ask your friend to be a collaborator and try to merge your commits. 

- linux command line basics (19min)
https://www.youtube.com/watch?v=IVquJh3DXUA very basic
Either watch this video or search for some other tutorials to get a very basic understanding of linux commands (if you use mac, many linux commands can be also used on your computer). To test your skills, try to use linux commands on your computer to move around, create files and do other things. On Windows you can use git bash (other alternatives also exist).

- Argparser (19min)
https://www.youtube.com/watch?v=rnatu3xxVQE
Get a basic idea of how argparser works in python. It's super simple. To test your skills, try use a parser in your own program so you can specify parameters from the command line. 

- hpc, remote server, gpu: search online and get a wikipedia level understanding of what they are. 

- ssh: 
https://www.youtube.com/watch?v=ORcvSkgdA58 (9min casual talk on what ssh is)
Get a basic understanding of what ssh is. No need to actually test it (but if you have time, you can try ssh with github).

- parallel computing
https://www.udacity.com/blog/2020/04/what-is-python-parallelization.html (short article)
If you never learned about parallel computing, read this short article or search for other resources to get a very basic understanding of what "parallel" means. To test your skills, try write a hello world level parallel computing program using python. It's actually super easy. 

- OpenAI Gym
https://gym.openai.com/
Simply take a look at this website. To have some fun, try install gym in your conda virtual env, and try init an environment, and render it (for example, cartpole) with a random policy. 

- bash scripting basics: 
https://www.youtube.com/watch?v=Zl7npywCB84 (24min)
Just get a basic idea of what bash scripting is about will be enough. Learn about linux command line before you watch this. 

- improve your understanding of neural networks, if you didn't get a solid understanding of neural networks in your ML class (or even if you do, just for fun you can) consider watch some super cool visualizations by 3Blue1Brown: 
https://www.youtube.com/watch?v=aircAruvnKk&t=284s (watch it for fun)

- Pytorch basics
https://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html 
If you haven't used a deep learning framework before, you might want to try Pytorch and make some neural networks. 

- tensorboard
https://pytorch.org/tutorials/recipes/recipes/tensorboard_with_pytorch.html (short tutorial)
Super easy to use and helpful tool, you can use them in your courses to help analyze results and debugging. When you use them, try to get a better idea of how debugging information is logged during training, and think about how you can do logging, plotting and analyzing efficiently. 