##############################################################################
Hummingbird
##############################################################################

Hummingbird is a flying robot for fun.


==============================================================================
How It Runs
==============================================================================

Prequisites:

- Simulator: https://github.com/udacity/FCND-Simulator-Releases
- Python: 3.6.3
- MiniConda

MiniConda

::

    # download miniconda at https://conda.io/miniconda.html
    $ bash ./Miniconda3-latest-MacOSX-x86_64.sh
    $ export PATH=/Users/<username>/miniconda3/bin:$PATH
    
    # conda commands
    $ conda env <create/update> environment.yml
    $ source activate <project_name>
    $ source deactivate

Hummingbird

::

    $ git clone https://github.com/alpesis-ai/hummingbird.git
    $ cd hummingbird

    $ /Users/<username>/miniconda3/bin/conda env create -f environment.yml
    $ source activate hummingbird
    # source deactivate 

    $ cd hummingbird
    # open the simulator, and then run flyer.py
    $ python flyer.py
