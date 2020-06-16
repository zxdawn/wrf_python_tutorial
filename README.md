# wrf_python_tutorial
Student Workbook Repository for the wrf-python Tutorial

## nuist_workshop_2020

### Env

1. Download the latest anaconda package from [TUNA](https://mirrors.tuna.tsinghua.edu.cn/anaconda/archive/?C=M&O=A)

2. Install anaconda by running the `.sh` or `.exe` file

3. Add Anaconda to the system environment following this [tutorial](https://www.pythonlikeyoumeanit.com/Module1_GettingStartedWithPython/Installing_Python.html) or any online tutorial

4. Check whether the Anaconda environment is set successfully

   ```
   which conda
   ```

5. Create the new environment in the terminal or cmd window

   ```
   conda env create -f nuist_env.yml
   ```

6. Activate the environment

   ```
   conda activate tutorial_2020
   ```

7. Test the jupyterlab

   ```
   jupyterlab
   ```


### Data

Switch to the `wrf_python_tutorial` directory and download the data from the dqwl HPC

   ```
   cd <your_dir>/wrf_python_tutorial
   scp -r <username>@<hpc_ip>:/wrf_tutorial_data ./
   ```

   ​

