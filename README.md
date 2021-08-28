**Lazy-Loader for FASTA files**

  LazyLoader to efficiently load FASTA files for model training. Input directories should contain only genomic sequences formatted as FASTA(text) files. This       LazyLoader will traverse through the given directories for all valid FASTA files and parse them  into files of 10,000 sequences accordingly. Sequences will them   be batch-loaded as Pytorch Datasets available to be loaded with DataLoader. A simple Pytorch model is provided for sample loading and training. The efficient     LazyLoader can load millions of FASTA sequences on an Duo-core CPU without memory exhaustion.
  
  

  **Package Requirements**
  
    -SeqIO 
  
    -Pytorch 
  
    -tqdm 
