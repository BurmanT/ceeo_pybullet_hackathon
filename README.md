1. Install anaconda (https://www.anaconda.com/download)
3. Create conda environment on terminal: **conda create -n myenv python=3.8.10**
4. Activate the conda environment (https://conda.io/projects/conda/en/latest/user-guide/getting-started.html#managing-python): **conda activate myenv**
5. Install pybullet (https://pypi.org/project/pybullet/): **pip install pybullet**
6. Clone the repo, cd into repo
7. Run: **python3 ballbeam.py**
    How does the lever move when toggling the slider on the right?  
9. Explore:
    Can you add a different object to the simulation?
    Can you modify ballbeam/ballbeam.urdf to make the pivot in the center instead of all the way in the left of the beam?
    Can you change the mass/size of the ball? How does this change the movement of the ball?

Helpful Resources:
https://medium.com/@chand.shelvin/pybullet-getting-started-a068a0e3d492
https://gerardmaggiolino.medium.com/creating-openai-gym-environments-with-pybullet-part-1-13895a622b24]


ballbeam.py: script for interacting with the objects in the simulation

resources/: contains urdf files for the ball and the ball beam structure 


