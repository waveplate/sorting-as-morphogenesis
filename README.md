# sorting-as-morphogenesis

[![View Live App](https://img.shields.io/badge/View-Live_App-2ea44f?style=for-the-badge)](https://waveplate.github.io/sorting-as-morphogenesis/)

A static web visualization demonstrating sorting algorithms as a model of morphogenesis. It runs a "cell-view" sorting simulation to show how simple, local policies can result in emergent, system-level behaviors like delayed gratification and spatial clustering. 

## Controls

* **Experiment 1: Delayed Gratification:** Populates the array with active agents and static "frozen" barriers. Used to observe how the algorithm temporarily decreases global sortedness to navigate around defects.
* **Experiment 2: Chimeric Clustering:** Populates the array with a mix of "Ascending" and "Descending" agents. Used to observe how conflicting local policies cause agents of the same type to aggregate spatially.
* **Play / Pause:** Toggles the execution of the sorting simulation.
* **Speed Slider:** Controls the number of operations the algorithm executes per interval (1 to 20x).

## References

The logic, experiments, and concepts visualized in this repository are directly based on the following paper:

* *Sorting Algorithms as a Model of Morphogenesis: Visualizing Unexpected Competencies in Minimal Models of Intelligence* by Taining Zhang, Adam Goldstein, and Michael Levin. 
* Available at: [arXiv:2401.05375](https://arxiv.org/abs/2401.05375)
