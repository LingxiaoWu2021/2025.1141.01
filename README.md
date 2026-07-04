[![INFORMS Journal on Computing Logo](https://INFORMSJoC.github.io/logos/INFORMS_Journal_on_Computing_Header.jpg)](https://pubsonline.informs.org/journal/ijoc)

# Scalable Multi-Stage Stochastic Optimization for Freight Procurement in Transportation-Inventory Systems

This archive is distributed in association with the [INFORMS Journal on Computing](https://pubsonline.informs.org/journal/ijoc) under the [MIT License](LICENSE.txt).

The software and data in this repository are a snapshot of the software and data that were used in the research reported on in the paper 
[Scalable Multi-Stage Stochastic Optimization for Freight Procurement in Transportation-Inventory Systems](https://doi.org/10.1287/2025.1141) by Lingxiao Wu, Wenxuan Shan, Yossiri Adulyasak, and Jean-François Cordeau. 

## Cite

To cite the contents of this repository, please cite both the paper and this repo, using their respective DOIs.

https://doi.org/10.1287/ijoc.2025.1141

https://doi.org/10.1287/ijoc.2025.1141.cd

Below is the BibTex for citing this snapshot of the repository.

```
@misc{SFPTMP,
  author =        {Lingxiao Wu and Wenxuan Shan and Yossiri Adulyasak and Jean-Fran{\c{c}}ois Cordeau},
  publisher =     {INFORMS Journal on Computing},
  title =         {Scalable Multi-Stage Stochastic Optimization for Freight Procurement in Transportation-Inventory Systems},
  year =          {2026},
  doi =           {10.1287/ijoc.2025.1141.cd},
  url =           {https://github.com/INFORMSJoC/2025.1141},
  note =          {Available for download at https://github.com/INFORMSJoC/2025.1141},
}  
```

## Description

- Code supplement for the paper "Optimizing Freight Procurement for Transportation-Inventory Systems Under Supply and Demand Uncertainty" by Lingxiao Wu, Wenxuan Shan, Yossiri Adulyasak, and Jean-François Cordeau.
- The details of the four benchmark methods (NC, MD, HS, and TS) are reported in the PDF file "Benchmark Methods".
- If you need help using the code, please send an email to lingxiaowu513[at]gmail[dot]com.
- The code and data sets are also available from https://github.com/LingxiaoWu2021/SFPTMP.

## Repository Structure

The repository is organized as follows:

### DATASETS:
* The instance data are provided in the folder "instances".
* For a detailed explanation of the instance data, find the "README" file in the folder "instances". 

### RESULTS:
* The detailed results obtained by each solution method for all instances are provided in the folder "Results". 

### CODE:
* Code of all algorithms used in our computational experiments is provided in the folder "sourcecode". 
* List of .cpp files in the subfolder "src":
  1. S0: code for S0
  2. S1: code for S1
  3. S2: code for S2
  4. CPLEX: code for running CPLEX on model P 
  5. NC: code for NC
  6. MD: code for MD
  7. HS: code for HS
  8. TS: code for TS

* List of .h files in the subfolder "inc":
  1. Avgminmax02.h:         user-defined c++ library header file
  2. Seqinsertion.h:         user-defined c++ library header file

## Replicating
- To run an algorithm for solving an instance:
  1. Copy the instance data from the "data" folder;
  2. Load the data into the code for the algorithm between lines "//input data starts here" and "//input data ends here";
  3. Build and run the code.

## Ongoing Development

This code is being developed on an on-going basis at the authors' [Github site](https://github.com/LingxiaoWu2021/SFPTMP).

## Support

For support in using this software, submit an [issue](https://github.com/tkralphs/JoCTemplate/issues/new).
