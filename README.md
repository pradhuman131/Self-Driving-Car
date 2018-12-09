# Self-driving-car
This is a  simple Deep Reinforcement learning self driving car model using Deep Q-learning algorithm.In this model the car is trying to reach `upper-left` corner or `bottom-right` corner as two destination places.
<img src = "https://github.com/pradhuman131/Self-driving-car/blob/master/image/preview.gif" width= "700" height = "600">

## Dependencies
You can install all dependencies by running the following commands
```python
# Install Pytroch
pip3 install torch torchvision

# Install kivy
sudo add-apt-repository ppa:kivy-team/kivy
sudo apt-get update
sudo apt-get install python3-kivy
```

## Usage


### Run the application
Run the map.py file 
```python
python3 map.py
```
After running map.py python file following ouptut screen is displayed
<img src = "https://github.com/pradhuman131/Self-driving-car/blob/master/image/output.png">

### Buttons
**clear:** `clear all the screeen content` <br />
**save:** `save the brain of AI as last_brain.pth` <br />
**load:** `load the last saved brain last_brain.pth` <br />

### Performance of saved brain
It shows the mean reward <br />
<img src = "https://github.com/pradhuman131/Self-driving-car/blob/master/image/Figure_1-1.png">


### Draw objects
Draw any roads and obstacles using mouse and let the car adjust according to environment

## Results
Here are some examples of levels with different difficulties in which car is driven automatically

<img src = "https://github.com/pradhuman131/Self-driving-car/blob/master/image/level1.gif" width= "700" height = "600">

<img src = "https://github.com/pradhuman131/Self-driving-car/blob/master/image/level2.gif" width= "700" height = "600">

<img src = "https://github.com/pradhuman131/Self-driving-car/blob/master/image/level3.gif" width= "700" height = "600">

<img src = "https://github.com/pradhuman131/Self-driving-car/blob/master/image/level4.gif" width= "700" height = "600">
