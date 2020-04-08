# Maze Solver using OpenCV

Give an image of a maze and it will find the path

Assuming that the input image has a green color at the start and red color at the end and the explorable space to be white with walls in black this program can take any image of a maze and give the path.

Breadth First Search was used in 'maze-solve.py'. To generate the mazes, an online maze generator tool has been used.

## Tools Used

  - OpenCV 3.4
  - Python 3.6

## Installation

1) cd /path/to/Maze-Solver(Path finder)/maze/

2) pip install -r requirements.txt

3) pip install -e .

## Task Analysis

### OpenCV
OpenCV (Open Source Computer Vision Library) is an open source computer vision and machine learning software library. OpenCV was built to provide a common infrastructure for computer vision applications and to accelerate the use of machine perception in the commercial products. The library has more than 2500 optimized algorithms, which includes a comprehensive set of both classic and state-of-the-art computer vision and machine learning algorithms.
OpenCV's application areas include:
  - Facial recognition system
  - Gesture recognition
  - Human–computer interaction (HCI)
  - Mobile robotics
  - Motion understanding
  - Object identification

## Usage

If you want to use your own maze,put it in 'mazes' folder and type python3 maze-solver.py mazes/your_maze.jpg