<!----Project Summary---->
This project implements a qiskit [state vector machine](https://en.wikipedia.org/wiki/Support-vector_machine) (QSVM) for calculating a kernel matrix

It's based on [this qiskit tutorial](https://qiskit.org/documentation/machine-learning/tutorials/03_quantum_kernel.html)

<!----Install---->
Qiskit is a fairly large package so I recommend using a virtual environment so you don't bloat the global environment. This can be done using venv [like in this tutorial](https://docs.python.org/3/tutorial/venv.html)
```
python3 -m venv <virtual env name>
```
The virtual environment needs to be then activated by using

**Windows**
```
<virtual env name>\Scripts\activate.bat
```

**Unix/Mac**
```
source <virtual env name>/bin/activate
```

By default the pip version is old so it needs to be upgraded as soon as the virtual environment is created
```
pip install --upgrade pip
```

All of the python requirements are in requirements.txt so running a file based install works best!
```
pip install -r requirements.txt
```