FROM fedora

RUN dnf update -y; dnf install -y stress

ENTRYPOINT ["/bin/bash", "pwd"]

# RUN stress --cpu 2 --io 1 --vm 1 --vm-bytes 128M
