From ubuntu:18.04

COPY kube-batch /usr/local/bin
COPY kubeconfig.kubemark  /opt/
COPY test.sh .
#ENTRYPOINT ["/usr/local/bin/kube-batch  --logtostderr --v 3 --enable-namespace-as-queue --kubeconfig /opt/kubeconfig.kubemark"]
CMD ["sh", "test.sh"]
#ENTRYPOINT ["/usr/local/bin/kube-batch"]
