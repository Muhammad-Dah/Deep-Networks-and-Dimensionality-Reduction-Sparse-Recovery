
use :


	srun -c 2 --gres=gpu:1 --pty jupyter-lab.sh

To run jupyter on a compute node by running a small script what we provide, jupyter-lab.sh.,
Here the -c 2 and --gres=gpu:1 options specify that we want to allocate 2 CPU cores and one GPU to the job,
the --pty option is required for the session to be interactive.

the connection URL in the console will show the IP of the compute node that the server is actually running on.
Use the first url to open jupyter in your browser.


---------------------------------------------------------------------------------------------------------------------

To view the notebook results: 
open 
	
	`Compressed_Sensing.html` 

file in your browser

---------------------------------------------------------------------------------------------------------------------

