# Reproducing Our Simulation Results
We provide our Python implementation of our algorithm as well as that of (Ahn et al., 2018) so that one can easily reproduce all of our experimental results.
One can easily reproduce any figure simply by opening the corresponding subfolder and run three or four Jupyter notebooks in order.  (Click "Run All" in each Jupyter notebook).
Then, simulation results will be saved as a figure within the subfolder.
For instance, one can reproduce Fig.1 by running Step_1_new_alg.ipynb, Step_2_prev_alg.ipynb, and Step_3_output_figure_1.ipynb in order.
While the values reported in our figures were the average performance over T=100 random runs, the default configuration in our codes is T = 2.
This way, one can quickly reproduce rough versions of our figures in a few minutes on a typical machine.
If one wants to reproduce more precise simulations results, one may want to change the value of T from 2 to 100 by modifying the first cell of each Jupyter notebook.
