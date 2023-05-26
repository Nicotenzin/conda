# conda
Transfer the conda environment between two computers

'''
conda install -c conda-forge conda-pack

conda activate yyc

conda pack yyc

conda env list
hhh     /home/qing/.conda/envs/hhh
yyy     /home/qing/.conda/envs/yyy
base    /opt/conda
xxx     /opt/conda/envs/xxx

cd /home/qing/.conda/envs/

mkdir myconda

tar -xzf yyc.tar.gz -C /home/qing/.conda/envs/myconda/

conda env list
hhh     /home/qing/.conda/envs/hhh
yyy     /home/qing/.conda/envs/yyy
myconda /home/qing/.conda/envs/myconda
base    /opt/conda
xxx     /opt/conda/envs/xxx
'''
