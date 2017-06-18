# cudaml

XSOCK=/tmp/.X11-unix/X0
sudo nvidia-docker run -ti -v $PWD:/data -e "DISPLAY=:0" -v $XSOCK:$XSOCK dciangot/cudaml root -l
