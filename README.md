# Parallel_Prog

les codes sources sont dans le répertoire src :  

- convol.c : code séquentiel de convolution
- convolution.c : code parallèle OpenMPI avec envoi de messages bloquants
- convolution_nbp.c : code parallèle OpenMPI avec envoi de messages non bloquants
- convol_omp.c : code parallèle OpenMP

- mandel.c : code séquentiel Mandelbrot
- mandel_mpi.c : code parallèle OpenMPI avec distribution de charge statique
- mandel_mpi_d.c : code parallèle OpenMPI avec distribution de charge dynamique
- mandel_omp.c : code parallèle OpenMP 

