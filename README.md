# Mars Landing Simulation


- Simple Python program that uses an image of the Mars Orbiter Laser Altimeter (MOLA) to choose the 20 safest
670 km X 335 km regions near the Martian equator from which to select landing ellipses for the Orpheus Lander.



![demo](img/GUIProgram.png)


**Virtual Env Setup**
---
- with Venv
```
python3 -m venv /path/to/new/virtual/environment

source .venv/bin/activate
```

- with Conda

```
conda create --name main (pythonversion)
conda activate main
```


**Installation Requirements**
---

1. Install PIL & OpenCV [`PIL`](https://pypi.org/project/Pillow/) & [`OpenCV`](https://pypi.org/project/opencv-python/)
    + `$ pip install Pillow`
    + `$ pip install opencv-python`

2. Once imports are complete, run `python site_selector.py` in the console.





