This Docker image is set up to rerun submission 69 in the M4 competition.

The method is called "Generalized Rolling Origin Evaluation Combination (GROEC)" and is originally written by Fiorucci and Louzada from the University of Brasilia and the University of São Paulo.

The methods was the 5th best in the M4 competition according to OWA.

To rerun the code:
1. Install Docker
2. Run an instance of the image in detached interactive mode with the command "docker run -it mariasoleim/m4-reproduction-69"
3. Run the code with "nohup Rscript jafiorucci.R". This may take a while.
