# lets-plot-pycharm-samples

This project contains a couple of scripts which demonstrate plotting in PyCharm SciView using the Lets-Plot plotting library:

- `density_plot.py` : a simple density plot.
- `interactive_map.py` : an interactive map showing locations of the major JetBrains offices worldwide.

## How to use

- Create new conda environment "lets-plot-pycharm-samples" specified in the `environment.yml` (included):

`conda env create -f environment.yml`  

- Open the project in PyCharm Professional Edition.

- Make sure the "lets-plot-pycharm-samples" environment is configured as a project interpreter.

- Make sure the *View/Scientific Mode* checkmark is on (main menu).

- Install the [Lets-Plot in SciView](https://plugins.jetbrains.com/plugin/14379-lets-plot-in-sciview) plugin.

- Select any script in the `scripts` folder and select *Run <script name>* from the context menu.