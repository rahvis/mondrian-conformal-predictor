# mondrian-conformal-predictor
Prereq: 
pip install scikit-learn==0.17 
% python -V                
Python 2.7.15


#How to run?  
python mcp/mcp.py -i a1 -t a2 -o output. <br>

"-i" input train file; "-t" test file; "-o" output directory. 

a1 and a2 are the dataset (split in train and test; a1 - train; a2 - test)

File format is libsvm format example. 
https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/. 
https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_svmlight_file.html. 

 
