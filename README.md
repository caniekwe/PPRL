# Privacy Preserving Record Linkage (PPRL)

This project demonstrates steps to implement privacy preserving record linkage using different approaches of bloom filter encoding. This project was implemented using the FEBRL synthetic dataset.

### Project Features
1. Data pre-processing (data cleaning, phonetic encoding)
2. Privacy preservation (field-level & record-level bloom filters, bloom filter hardening techniques)
3. Blocking and indexing
4. Comparison (dice coefficient similarity)
5. Classification (supervised and unsupervised)
6. Evaluation (blocking:pair completeness, reduction ratio; linkage: accuracy, f1 score, precision, recall)

### Requirements
Complied using:
* python 3.9.7
* pandas 1.3.4
* hashlib: https://docs.python.org/3/library/hashlib.html
* record linkage toolkit (recordlinkage 0.15): https://pypi.org/project/recordlinkage/ 

### Referenced projects
This project uses a few other projects as below:
* Implementation examples of Python Record Linkage Toolkit: https://github.com/mayerantoine/recordlinkage 
* PPRL hardening technique and attack: https://dmm.anu.edu.au/pprlattack/
* FEBRL: http://users.cecs.anu.edu.au/~Peter.Christen/Febrl/febrl-0.3/febrldoc-0.3/manual.html 
* Python record linkage toolkit: https://recordlinkage.readthedocs.io/en/latest/about.html 
* Bloom filter examples: https://github.com/onnovalkering/notebooks/tree/master/record-linkage

# ----
### License
This project is licensed under the GNU General Public License v3.0

