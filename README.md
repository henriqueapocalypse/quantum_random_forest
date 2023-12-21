# Quantum-Random-Forest
The model is based off the paper Srikumar et al., "A kernel-based quantum random forest for improved classification", (2022). The code is intended for research purposes and the development of proof of concepts. For questions about the code and its use in the paper, please email maiyuren.s@gmail.com for clarification.

-----

## Required packages

Python=3.8.10 was used with the following libraries:

    - cirq==0.11.0
    - cirq-core==0.11.0
    - matplotlib==3.4.2
    - more-itertools==8.8.0
    - numpy==1.19.5
    - pandas==1.3.0
    - qiskit==0.27.0
    - scikit-learn==0.24.2
    - scipy==1.7.0
    - tqdm==4.61.1
    - tensorflow==2.4.1

-----
# Creating a Virtual Environment
To create a virtual environment in Visual Studio Code (VSCode), you can use venv (Virtual Environment) or conda (if you are using Anaconda).

Using venv, first, access the terminal with the command **Ctrl + Shift + '** (backtick).

With the terminal open, type:
<pre>
$ python3.8 -m venv venv
</pre>

Replace *venv* with the name of the virtual environment you desire.

Now, to activate the virtual environment on Windows, use the command:
<pre>
$ venv\Scripts\activate
</pre>

On macOS/Linux, run the command:
<pre>
$ source venv/bin/activate
</pre>

After executing the above command, you will see the name of the current virtual environment at the beginning of the command line in the terminal, indicating that the environment is activated and ready.

With your virtual environment activated, navigate to the /doc folder using the following command:
<pre>
$ cd .\doc\
</pre>
Next, use the following command to install all the necessary dependencies:
<pre>
$ pip install -r requirements.txt
</pre>
Now your virtual environment is set up and configured with all the dependencies.


Example code is found in the example_notebook.ipynb file. Feel free to try with your own datasets.      

Note, only IQP and Efficient-Anzatz embeddings are available. Feel free to construct other embeddings from scratch and add to the pqc.py and split_function.py files.