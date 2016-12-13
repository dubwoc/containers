FROM debian:stable
RUN apt-get install -y bash
RUN dd if=/dev/zero of=/fatfile bs=1G count=100
CMD ["/bin/bash"]
