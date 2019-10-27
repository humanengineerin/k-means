### __K-MEANS algorithm project__

#### Overview
2D points k-means algorithm visualization. <br>
Grouping image colors using k-means algorithm. <br>

#### Requirements
 - python 3
 - pip

#### Image processing demo

![Alt Text](docs/demo_assets/horse_image_demo.png)

#### Set up
Create new virtualenv:
```
virtualenv -p python3 venv
```
Activate environment
On Linux:
```
source venv/bin/activate
```
On Windows:
```
venv\Scripts\activate.bat
```
Install required packages:
```
pip install -r requirements.txt
```

#### Run
First set variables in src/k_means/settings.py

To run image processing algorithm in project directory run:
```
python src/k_means/main.py IMAGE
```
To run points visualization algorithm in project directory run:
```
python src/k_means/main.py POINTS
```