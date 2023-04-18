Welcome to our final project- Computer Science Degree

Follow next instructions for running our project:

1.)
open the next link:
<a href="https://colab.research.google.com/github/yoav1995/highway-env2/blob/master/FinalProjectEdit_highway_planning.ipynb" rel="nofollow">
<img src="https://camo.githubusercontent.com/84f0493939e0c4de4e6dbe113251b4bfb5353e57134ffd9fcab6b8714514d4d1/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667" alt="Open In Colab" data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg" style="max-width: 100%;">
</a>


2.)
before running all scripts make sure your enviorment is set:
*** configuration of the enviorment is set under the "RUN EPISODE" script below the "agent config" part



our project prepares:
env.config["offroad_terminal"]=True
env.config["duration"]=40
env.config["vehicles_count"]=100
env.spec.disable_env_checker=True
env.reset()

3.)

press RunTime on the tool bar at the Left-Top corner of the page---> than press Run all
that will run one scenario of our edit project

for best examing result run 15 scenarios at least

4.)
for comparing our edit with the original optimistic algorithm run 15 scenarios of the next project:
<a href="https://colab.research.google.com/github/eleurent/highway-env/blob/master/scripts/highway_planning.ipynb" rel="nofollow"><img src="https://camo.githubusercontent.com/84f0493939e0c4de4e6dbe113251b4bfb5353e57134ffd9fcab6b8714514d4d1/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667" alt="Open In Colab" data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg" style="max-width: 100%;"></a>


***IMPORTANT***

Make sure that the next details is configured before running the original project:
env.config["duration"]=40
env.config["vehicles_count"]=100
env.reset()



this project is based on the original project referenced at the CITATION file.

