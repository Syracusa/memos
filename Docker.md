# Docker

docker
단일 목적을 가진 최소사양의 컨테이너(가상머신) 제공
다양한 목적에 맞게 이미 준비된 수많은 컨테이너들이 준비되어있음
컨테이너는 실행에 필요한 모든것을 갖추고 있음(개발환경과 배포환경 동일화)


Demystifying Containers - Part I: Kernel Space

https://medium.com/@saschagrunert/demystifying-containers-part-i-kernel-space-2c53d6979504

컨테이너의 조건

Not negotiable: They have to run on a single host. Okay, so two computers cannot run a single container.

Clearly: They are groups of processes. You might know that Linux processes live inside a tree structure, so we can say containers must have a root process.

Okay: They need to be isolated, whatever this means in detail.

Not so clear: They have to fulfill common features. Features in general seem to change over time, so we have to point out what the most common features are.


