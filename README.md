# FABP_MD

This text is a list of all original data.
Reference: Haiyi Chen, Yue Guo, Shengqing Ye, et al. On the Dynamic Mechanism of Long-Flexible Fatty Acid Binding to Fatty Acid Binding Protein: Resolving the Long-Standing Debate. JCIM.

1. Conventional MD of FABP-SA complex
	
    1.1 The initial structure in inpcrd format and the topology file;
    1.2 The input parameter file of production run of cMD;
    1.3 An example of the cMD trajectories (without water and ions).

2. BE-MetaD
    2.1 The initial structure file and toplogy file of FABP-SA (*.gro and *.top format);
    2.2 The gromacs input *.mdp file;
    2.3 The plumed.dat input file which contains the definition of four CVs;
    2.4 The simulation trajectories of BE-MetaD (without water and ions).

3. The calculation of Koff (Path CVs) for FABP-SA
    3.1 The initial ligand-bounded conformation of the MetaD run (*.gro and *.top format);
    3.2 The intermediate conformations which define the unbinding events of each pathway;
    3.3 The gromacs input *.mdp file;
    3.4 The plumed.dat input file which contains the definition of the path CVs s(x), z(x);
    3.5 The simulation trajectories of path-cv metadynamics (without water and ions).

