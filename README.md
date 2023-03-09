### Useful installation steps if running the notebook locally, using a virtual environment

## Dataset
You can find the dataset at the following location: https://drive.google.com/drive/folders/1Xm3Z0qgIEZvmgefEs6gkn4xFCElqeoEj?usp=share_link

Please contact me at a.stoica@student.rug.nl if you cannot access the dataset.


## Build and run the project

1. Navigate to the directory where you want to store the project.
```bash
cd your/directory/for/the/project
```

2. Clone the repository.
```bash
git clone https://github.com/andreistoica12/research-internship.git
```

3. Navigate to the root directory of the project.
```bash
cd research-internship/
```

4. Switch to the covaxxy branch.
```
git checkout pheme
```

5. Use the package manager [pip](https://pip.pypa.io/en/stable/) to install `virtualenv`.
```bash
pip install virtualenv
```

6. Create a virtal environment named `venv`.
```bash
python3 -m venv venv
```
7. Activate the virtual environment.
```bash
source venv/bin/activate
```

8. Install all the dependencies from the `requirements.txt` file into your virtual environment.
```bash
pip install -r requirements.txt
```

9. Select the virtual environment you just created as the kernel (from VS Code). Easily run and debug cells.
