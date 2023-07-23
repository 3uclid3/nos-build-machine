FROM ubuntu:jammy

# copy scripts
COPY . /

# run installation script
RUN ./install.sh --llvm 16

# set entrypoint bootstrap scripts
ENTRYPOINT ./bootstrap.sh --llvm 16
