# SequentialSamplingModels.jl: Simulating and Evaluating Cognitive Models of Response Times in Julia

> **SequentialSamplingModels.jl: Simulating and Evaluating Cognitive Models of Response Times in Julia**  
> Kianté Fernandez<sup>1</sup>, Dominique Makowski<sup>2</sup>, and Christopher Fisher<sup>3</sup>  
> <sup>1</sup>Department of Psychology, University of California, Los Angeles, CA, USA  
> <sup>2</sup>School of Psychology, University of Sussex, Brighton, UK  
> <sup>3</sup>Independent Researcher  

## Abstract

Sequential sampling models (SSMs) are a widely used framework describing decision-making as a stochastic, dynamic process of evidence accumulation. SSMs popularity across cognitive science has driven the development of various software packages that lower the barrier for simulating, estimating, and comparing existing SSMs. Here, we present a software tool, SequentialSamplingModels.jl (SSM.jl), designed to make SSM simulations more accessible to Julia users, and to integrate with the Julia ecosystem. We demonstrate the basic use of SSM.jl for simulation, plotting, and Bayesian inference.

## Building the Paper

Requirements:
- LaTeX distribution
- Julia 1.9 or higher

To build the paper locally:

1. Clone this repository
2. Navigate to the paper directory
3. Build using latexmk:
   ```bash
   latexmk -bibtex -pdf paper.tex
   ```

To clean up the build files:
   ```bash
   latexmk -c
   ```

Note: This will re-generate header.tex, bib.tex, journal_dat.tex and build the final PDF.

## Package Links

- SSM.jl Package: [https://github.com/itsdfish/SequentialSamplingModels.jl](https://github.com/itsdfish/SequentialSamplingModels.jl)
- Documentation: [https://itsdfish.github.io/SequentialSamplingModels.jl/dev/](https://itsdfish.github.io/SequentialSamplingModels.jl/dev/)

## Citation

If you use SSM.jl in your research, please cite:

```bibtex
@article{fernandez2024sequential,
  title={SequentialSamplingModels.jl: Simulating and Evaluating Cognitive Models of Response Times in Julia},
  author={Fernandez, Kiant{\'e} and Makowski, Dominique and Fisher, Christopher},
  journal={Proceedings of JuliaCon},
  volume={1},
  number={1},
  year={2024}
}
```

## License

This paper and associated materials are licensed under MIT License. The SSM.jl package is licensed under its own terms.
