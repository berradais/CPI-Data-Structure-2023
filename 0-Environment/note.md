# The chapter tips

1 ) Git

- We can use it any environment
- Git workflow
- Make examples using pull request in github
- Show config files and ignore file
- Attention of git pull: it can be problematic
- Git Installation
  - download cli github <https://cli.github.com>
    - main commands:
      1) gh pero create
      2) git init .
      3) ...

2 ) Markdown

- Just some examples of writing paragraphs and list, ...

3 ) IPyhton

- Most of shortcut are not working with VS but are perfect in notebook: online help, tab+shift, ?, ...

4 ) Simlab

- module load anaconda/3-5.3.1

- squeue: voir qui dans le pipe

- sinfo: voir les particitions

- srun -p shortq --time=1:00:00 --pty bash

- jupyter notebook --ip localhost --port 8500 --no-browser

- conda create -n my_env

- (en cas de probleme de conda can't not initial): source .bashrc

- conda activate my_env

- ssh -t -L 8500:localhost:8500 iberrada@simlab-cluster.um6p.ma ssh -N -L 8500:localhost:8500 node06

- 8501:localhost:8500  gpuadmin@196.200.146.19 -p 10001
