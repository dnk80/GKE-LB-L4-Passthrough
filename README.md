# GKE-LB-L4-Passthrough



kubectl get svc -n log-namespace
NAME         TYPE           CLUSTER-IP      EXTERNAL-IP    PORT(S)          AGE
log-parser   LoadBalancer   10.27.218.204   35.196.30.64   5514:30060/TCP   11m


telnet 35.196.30.64   5514
Trying 35.196.30.64...
Connected to 35.196.30.64.
Escape character is '^]'.
^]
telnet> quit
Connection closed.

