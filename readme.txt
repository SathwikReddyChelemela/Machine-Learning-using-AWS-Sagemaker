Install Anaconda

conda --version


conda info --envs


conda create --name development python=3.9


you will see this:
(development) sathwik@Sathwiks-MacBook-Air AWS Sagemaker

you can deactivate with conda deactivate

or 

(best method)

conda create -p myenv python=3.8

this will create folder myenv for setting environment

then, 

conda activate development   /  conda activate myenv/\


then, inside myenv, install:
pip install -r requirements.txt


select myenv kernel

now run the code!





