# PyTrace_Next_Week

![image2](./references/final_scene.png)

A (nearly) pure Ray Tracing Project for Python

This work is based off the books **[Ray Tracing: the Next Week](https://github.com/RayTracing/raytracingthenextweek)** by Peter Shirley but ported to Python 

dependencies include: 
1. pypy3 (note all other dependencies must be installed within pypy3)
2. numpy 
3. matplotlib
4. tqdm
5. noise


## Quickstart guide: 
1. Install Anaconda
2. conda env create -f environment.yaml
3. conda activate PyTrace_env
4. pypy3 -m ensurepip
5. **if on mac you may need to fake a linked library described [here](https://bitbucket.org/pypy/pypy/issues/2942/unable-to-install-numpy-with-pypy3-on)**
6. pypy3 -m pip install -r requirements.txt
7. pypy3 main.py 



Technically, you can run w/o pypy3 installed but it is very slow w/o the JIT compilation, as seen below 

## PyTrace_Next_Week Benchmark: 
Note: Iterations per second are how many output pixels are processed per second 
 
### W/ Cornell Box Rotated: 
2048 spp

800 x 800

Standard Implementation w/ PyPy

avg: 116.79 it/s

time: 1:31:19

### W/ Final Scene: 
2048 spp

800 x 800

Standard Implementaiton w/ Pypy

avg: N/A 

time: ~ 3 Hours


