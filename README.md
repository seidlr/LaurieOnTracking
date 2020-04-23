# LaurieOnTracking
Laurie's code for reading and working with Metrica's tracking and event data.

The sample data can be found in Metrica's github repository here: https://github.com/metrica-sports/sample-data

We'll be updating this repo as the friends of tracking series develops, adding code for measuring player velocity and acceleration, measuring team formations, and evaluating pitch control using a model published by Will Spearman. 

To create movies from the tracking data you'll need to have ffmpeg installed. You can do this by following the instructions here: https://anaconda.org/conda-forge/ffmpeg (you may need to restart python afterwards).

## Notebooks
If you want to run the notebooks for each session, you can either install the repository locally or run it directly in Binder.

| Lesson | Binder |
| --- | --- |
| [Lesson 4 - Basic Plotting of Event and Tracking Data](Lesson4.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/seidlr/LaurieOnTracking/master?filepath=Lesson4.ipynb) |
| [Lesson 5 - Advanced Plotting and Summary Statistics](Lesson5.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/seidlr/LaurieOnTracking/master?filepath=Lesson5.ipynb) |
| [Lesson 6 - Pitch Control](Lesson6.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/seidlr/LaurieOnTracking/master?filepath=Lesson6.ipynb) |
 
### Local installation
1. Download Anaconda
2. Clone repository
3. Create environment `friends-of-tracking-data-env`:
```
conda env update
```
4. Start jupyter notebook server
```
jupyter notebook
```