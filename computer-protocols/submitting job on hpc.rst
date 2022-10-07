.. include:: ../../links.rst
.. |date| date:: %d %B %Y %H:%M %Z (%z)

Submission of job on HPC
===============================


:Author: Vinay K L
:Copyright: None
:Date: 07/10/2022

Purpose
-------
To set up a job on the HPC cluster.

#. To connect, use IP 172.27.1.152
#. Our institute has limited resource cluster with 14 nodes (1 login node) with 40 cores (Intel Xeon W series) on each nodes. Each node hosts a 196GB RAM and 2 nodes with Nvidia GPU.
#. By default each user can request maximum 80 cores at a given time. But on special request to IT department this can be extended.
#. There are 5 different time Q based on walltime. 1) ShortQ (24:00:00) 2) MidQ (48:00:00) 3) LongQ(96:00:00) 4) ELongQ(128:00:00) 5)iiserq (Unlimited, but without prior IT approval, job can be killed without notice)
#. PBS is used as job scheduler and handler and below is a PBS template for reference.

+--------------------------------------------------------------------------------------+
#PBS -N Name_reflecting_in_queue
#PBS -q iiser
#PBS -l select=1:ncpus=40
#PBS -l walltime=128:00:00
#PBS -M vinaykl@students.iisertirupati.ac.in
#PBS -V
#PBS -o name_of_log.o
#PBS -e name_of_log.err

ncores=`cat $PBS_NODEFILE|wc -l`


#source /home/app/intel/compilers_and_libraries/linux/bin/compilervars.sh intel64
#source /home/app/intel/compilers_and_libraries/linux/mpi/bin64/mpivars.sh intel64
#source /home/app/intel/compilers_and_libraries/linux/mkl/bin/mklvars.sh intel64

cd $PBS_O_WORKDIR
cd /path/to/your/current/working/directory

command
+---------------------------------------------------------------------------------------+
