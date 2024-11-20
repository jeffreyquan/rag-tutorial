## Tutorial using Retrieval Augmented Generation (RAG)

Refer to [LangChain RAG tutorial](https://python.langchain.com/docs/tutorials/rag/)

### **1. Install Conda**

Download and install **Miniconda** or **Anaconda**:

- **Miniconda** (lightweight)
- **Anaconda** (comes with many pre-installed packages, including Jupyter)

### **2. Create a Conda Environment**

```bash
conda create --name rag python=3.12
```

- Replace `rag` with your desired environment name.
- Replace `3.12` with the version of Python you need.

Activate the environment:

```bash
conda activate rag
```

---

### **3. Install Jupyter Notebook**

With your environment activated, install Jupyter Notebook:

```bash
conda install -c conda-forge notebook
```

---

### **4. Install Additional Packages (Optional)**

Install specific libraries:

```bash
conda install langchain langchain-community langchain-chroma langchain-openai -c conda-forge
```

---

### **5. Launch Jupyter Notebook**

Start Jupyter Notebook:

```bash
jupyter notebook
```

This will open Jupyter in your default web browser. If it doesn’t, copy the URL shown in the terminal and paste it into your browser.

---

### **6. Add Your Conda Environment to Jupyter (Optional)**

To make your Conda environment available as a kernel in Jupyter Notebook:

1. Install the `ipykernel` package in your Conda environment:

```bash
conda install ipykernel
```

2. Add the environment to Jupyter:

```bash
python -m ipykernel install --user --name=my_env --display-name "Python (rag)"
```

Replace `rag` with your environment name.

When you create or open a notebook, you can select this environment as the kernel.

---

### **7. Verify Setup**

In the Jupyter Notebook interface:

- Create a new notebook.
- Ensure the kernel is set to the Conda environment you configured (`Python (rag)`).
