## Introduction
The project is the bent routing pattern for FPGA in VTR. For information about the overall  Verilog-to-Routing (VTR) project, you can go to https://github.com/verilog-to-routing/vtr-verilog-to-routing.  The architecture file format is enhanced to support bent wires,  more information can be seen in the  [paper](https://ieeexplore.ieee.org/document/8892074). In this paper,`ST` represents the straight type, `CC` represents the counterclockwise type and `CW` represents the clockwise type. For simplification, we use `-` to represent straight type, `U` to represent counterclockwise type, `D` to represent clockwise type. You can find an architecture file with bent wires in  https://github.com/shikc/VTR_bent_wire/tree/main/vtr_flow/arch/bent.

The bent routing pattern is proposed by X. Sun et al. in FPL 2019. In 2022, K. Shi et al. enhance GIB architecture with bent wires for FPGA in TRETS 2022. For more details, you can see the following papers.

Bibtex:

```
@inproceedings{sun2019bent,
  title={Bent routing pattern for FPGA},
  author={Sun, Xibo and Zhou, Hao and Wang, Lingli},
  booktitle={2019 29th International Conference on Field Programmable Logic and Applications (FPL)},
  pages={9--16},
  year={2019},
  organization={IEEE}
}

@inproceedings{shi2020gib,
  title={GIB: A novel unidirectional interconnection architecture for FPGA},
  author={Shi, Kaichuang and Zhou, Hao and Zhou, Xuegong and Wang, Lingli},
  booktitle={2020 International Conference on Field-Programmable Technology (ICFPT)},
  pages={174--181},
  year={2020},
  organization={IEEE}
}

@article{shi2022optimized,
  title={An Optimized GIB Routing Architecture with Bent Wires for FPGA},
  author={Shi, Kaichuang and Zhou, Xuegong and Zhou, Hao and Wang, Lingli},
  journal={ACM Transactions on Reconfigurable Technology and Systems (TRETS)},
  year={2022},
  publisher={ACM New York, NY}
}
```


