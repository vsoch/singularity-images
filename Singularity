bootstrap: docker
From: tensorflow/tensorflow:latest
IncludeCmd: yes

%runscript

    exec /usr/bin/python "$@"

%post

    chmod 755 /usr/lib/python2.7/dist-packages/.wh*

