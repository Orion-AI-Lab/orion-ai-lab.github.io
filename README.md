# Orionlab research page

## Initial Setup

1. Run codespaces
2. Create a new conda environment with python3.11
```
conda create --name myenv python=3.11
source activate myenv
pip install academic
```

## Running the server locally

1. Run codespaces
2. Run the server. Go to the terminal and hit the following:

```
./hugo server
```
3. Open the browser from the ports tab

## Adding a new publication

1. Activate the conda environment

```
source activate myenv
```

2. Add the .bib file (let's say my_bib.bib) for your publication to content/publication/bibdir

3. Import the .bib file

```
academic import content/publication/bibdir/my_bib.bib content/publication -v --compact
```

4. Edit the created index.md to add more info and additional links to pdf, code, etc.

5. Add an image called `featured.(jpg|png)` to the created directory.
