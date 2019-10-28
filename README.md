# scratch-debug
Installs busybox -based debug environment for Scratch-based Docker-containers. Works with Docker and Kubernetes.

The problem is that if you build a high security container with minimum attack surface, and the most lightweight container possible, you don't have any debug tools.

#Final phase
FROM scratch

Usage:
    ./debug.sh podname -k kubeconfig.yml -n my-namespace

See
    https://ahmet.im/blog/debugging-scratch/
