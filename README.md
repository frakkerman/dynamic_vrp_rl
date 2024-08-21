# A Comparison of Reinforcement Learning Policies for Dynamic Vehicle Routing Problems with Stochastic Customer Requests

This project contains code for the paper titled "A Comparison of Reinforcement Learning Policies for Dynamic Vehicle Routing Problems with Stochastic Customer Requests" by Fabian Akkerman, Martijn Mes, and Willem van Jaarsveld, see: [https://doi.org/10.1007/s10479-022-04674-8.](https://research.utwente.nl/en/publications/a-comparison-of-reinforcement-learning-policies-for-dynamic-vehic)

## Citation

When using the code or data in this repo, please cite the following work:

```
@Article{Akkerman2024,
	author={Akkerman, Fabian
  and {van Jaarsveld}, Willem
	and Mes, Martijn},
	title={A Comparison of Reinforcement Learning Policies for Dynamic Vehicle Routing Problems with Stochastic Customer Requests},
	year={2024}
}
```

## Environment

The code is written in C++20, in the reinforcement learnign toolbox DynaPlex. We tested our project on a Windows 11 environment and on a Linux HPC.


## Structure

The submodule folder links to the branch "dynamic_vrp" in the DynaPlex code repository.


## To the make the code work

Ensure that you clone the repository with submodules:

```
git clone --recurse-submodules
```

For further information, we refer to the documentation of DynaPlex
 
## Contributing

If you have proposed extensions to this codebase, feel free to do a pull request! If you experience issues, feel free to send us an email.

## License
* [MIT license](https://opensource.org/license/mit/)
* Copyright 2024 © [Fabian Akkerman](https://people.utwente.nl/f.r.akkerman), [Martijn Mes](https://www.utwente.nl/en/bms/iebis/staff/mes/) [Willem van Jaarsveld](https://www.tue.nl/en/research/researchers/willem-van-jaarsveld)
