# Reproducible Fuzzer Evaluations

This organization accompanies our paper "[SoK: Prudent Evaluation Practices for Fuzzing](https://doi.ieeecomputersociety.org/10.1109/SP54263.2024.00137)" accepted to the IEEE Security & Privacy Symposium (S&P) 2024. You can find the preprint [here](https://mschloegel.me/paper/schloegel2024sokfuzzevals.pdf).

Most importantly, we would like to initiate a discussion on how future fuzzing papers can ensure their evaluations are robust and reproducible. We have collected all our lessons learned as guidelines at: https://github.com/fuzz-evaluator/guidelines

**Contributions in form of discussions or changes are welcome!** Our goal is to keep this repository up-to-date to provide a sensible and helpful set of guidelines for future research.


## Quick Overview
For our paper, we have read 150 fuzzing papers published at prestigious conferences and studied how they conduct their evaluations. We find that there is much room for improvement, for example, in terms of a statistical evaluation. Please check out the [paper](https://doi.ieeecomputersociety.org/10.1109/SP54263.2024.00137) (or [preprint](https://mschloegel.me/paper/schloegel2024sokfuzzevals.pdf)) to learn more about the details of our results. Beyond this literature survey, we further made an effort to reproduce the artifacts of eight papers. For each of them, you can find our reproduction artifact as part of this organization's repositories (in alphabetical order):
- [DARWIN](https://github.com/fuzz-evaluator/DARWIN-eval)
- [EcoFuzz](https://github.com/fuzz-evaluator/EcoFuzz-eval)
- [Firm-AFL](https://github.com/fuzz-evaluator/firmafl-eval)
- [FishFuzz](https://github.com/fuzz-evaluator/FishFuzz-eval)
- [FuzzJIT](https://github.com/fuzz-evaluator/fuzzjit-eval)
- [MemLock](https://github.com/fuzz-evaluator/MemLock-Fuzz-eval)
- [PolyFuzz](https://github.com/fuzz-evaluator/PolyFuzz-eval)
- [SoFi](https://github.com/fuzz-evaluator/SoFi-eval)

We emphasize that this is not intended to point fingers but about identifying potential pitfalls and making sure future fuzzing evaluations can avoid them. We all make mistakes -- the best thing we can do is to learn from them!

Finally, based on our findings from the literature survey and artifact evaluation, we provide [revised recommendations](https://github.com/fuzz-evaluator/guidelines) (again, your input is welcome!). Regarding the statistical analysis, you can find our scripts [here](https://github.com/fuzz-evaluator/statistics).


## Citation

To cite our work, feel free to use the following bibtex entry:
```
@inproceedings{schloegel2024fuzzingsok,
  title = {SoK: Prudent Evaluation Practices for Fuzzing},
  author = {Moritz Schloegel and Nils Bars and Nico Schiller and Lukas Bernhard and Tobias Scharnowski and Addison Crump and Arash Ale-Ebrahim and Nicolai Bissantz and Marius Muench and Thorsten Holz},
  booktitle = {IEEE Symposium on Security and Privacy (SP)},
  year = {2024},
  doi = {10.1109/SP54263.2024.00137},
}  
```
