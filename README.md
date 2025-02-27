# BayesianForceInference_GoogleColab
Perform MAP estimation of junction tensions and cell pressures based on the force balance relationship at cell vertices.

As presented in:
*   Shuji Ishihara and Kaoru Sugimura.
["Bayesian inference of force dynamics during morphogenesis."](https://www.sciencedirect.com/science/article/pii/S0022519312004316?via%3Dihub)
Journal of Theoretical Biology 313, 201–211 (2012).

*   S. Ishihara, K. Sugimura, S. J. Cox, I. Bonnet, Y. Bellaïche, F. Graner.
["Comparative study of non-invasive force and stress inference methods in tissue."](https://link.springer.com/article/10.1140/epje/i2013-13045-8)
The European Physical Journal E 36, 1–13 (2013).

This Google Colab notebook was implemented by Xin Yan and Kaoru Sugimura. 

The original Python code is available on [Ishihara Lab's GitHub page](https://github.com/IshiharaLab/BayesianForceInference).


# How to Use
Test sample:
1. Download files from [Github](https://github.com/Sugimuralab/BayesianForceInference_GoogleColab).
2. Upload them to your Google Drive. Make sure that you put BayesianForceInference.ipynb and lib/ in the same directory (YourDirectory/BayesianForceInference.ipynb, YourDirectory/lib/).
3. Select `InputData-ForceInference/Vertex/VDat_140408-T001.dat` as the input file in step 3.
4. Select `OutputData-ForceInference/' as the output directory in step 4. Alternatively, you can create a new directory and set it as the output directory.
5. Select the directory that you put this notebook, BayesianForceInference.ipynb, as the current working directory in step 5.

Your samples:
1. Download files from [Github](https://github.com/Sugimuralab/BayesianForceInference_GoogleColab).
2. Upload BayesianForceInference.ipynb and lib/ to your Google drive. Put them in the same directory (YourDirectory/BayesianForceInference.ipynb, YourDirectory/lib/).
3. Prepare an input file in the same format as `InputData-ForceInference/Vertex/VDat_140408-T001.dat`. **GetVertex**, a Fiji/ImageJ plug-in for generating such a file from a segmented image, is available from [Github](https://github.com/Sugimuralab/GetVertexPlugin).
4. Upload the input file to your Google Drive.
5. Select the input file in step 3.
6. Set an output directory of your choice in step 4.
7. Select the directory that you put this notebook, BayesianForceInference.ipynb, as the current working directory in step 5.

[Instruction](https://github.com/Sugimuralab/BayesianForceInference_GoogleColab/blob/main/docs/Instruction.pdf)

