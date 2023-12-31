<h1 align="center" id="title">Protein_Structure_MongoDB</h1>

<p id="description">This project helps user to add delete and update protein structures and sequences and make queries. We provide this project with a dataset for PDB so it becomes more easy for the users to know the types of data that they deal with. We create a website using streamlit to make it easy for our users to perform their queries and upload the dataset on cloud so they don't need to download any programs to use our website.

You will find the website link at the end of this README file. 
</p>

<h2>Dataset Description</h2>

This is a protein data set retrieved from Research Collaboratory for Structural Bioinformatics (RCSB) Protein Data Bank (PDB).

The PDB archive is a repository of atomic coordinates and other information describing proteins and other important biological macromolecules. Structural biologists use methods such as X-ray crystallography, NMR spectroscopy, and cryo-electron microscopy to determine the location of each atom relative to each other in the molecule. They then deposit this information, which is then annotated and publicly released into the archive by the wwPDB.

The constantly-growing PDB is a reflection of the research that is happening in laboratories across the world. This can make it both exciting and challenging to use the database in research and education. Structures are available for many of the proteins and nucleic acids involved in the central processes of life, so you can go to the PDB archive to find structures for ribosomes, oncogenes, drug targets, and even whole viruses. However, it can be a challenge to find the information that you need, since the PDB archives so many different structures. You will often find multiple structures for a given molecule, or partial structures, or structures that have been modified or inactivated from their native form. 

  
<h2>🧐 Features</h2>

Here're some of the project's best features:

*   Easy to use
*   Add new protein structures details and sequences
*   delete / update existing protein structures details and sequences
*   Select the table to make a query
*   Make queries to get the required output

<h2>🛠️ Installation Steps:</h2>

<p>1. Clone the repository</p>

```
git clone "https://github.com/MiraRafat12/Protein_Structure_MongoDB.git"
```

<p>2. Install npm modules</p>

```
pip install -r requirements.txt
```

<p>3. Start running of streamlit website using below command</p>

```
streamlit run Protein_Structure_code.py
```

  
  
<h2>💻 Built with</h2>

Technologies used in the project:

*   pandas
*   pymongo
*   streamlit
*   streamlit-aggrid
