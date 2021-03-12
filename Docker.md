# Docker

Demystifying Containers - Part I: Kernel Space

https://medium.com/@saschagrunert/demystifying-containers-part-i-kernel-space-2c53d6979504

컨테이너의 조건

Not negotiable: They have to run on a single host. Okay, so two computers cannot run a single container.

Clearly: They are groups of processes. You might know that Linux processes live inside a tree structure, so we can say containers must have a root process.

Okay: They need to be isolated, whatever this means in detail.

Not so clear: They have to fulfill common features. Features in general seem to change over time, so we have to point out what the most common features are.

