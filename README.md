# cudaml

ROOT6 TMVA with GPU support.
Additional pgks available: sklearn, matplotlib, numpy, root_pandas, tensorflow, keras 

    XSOCK=/tmp/.X11-unix/X0
    xhost +SI:localuser:root

    sudo nvidia-docker run -ti --rm -v $PWD:/data -e DISPLAY=$DISPLAY -v $XSOCK:$XSOCK dciangot/cudaml <your command>

If you want to try root cern with TMVA on GPU your command=root -l
