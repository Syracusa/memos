# memos

윈도우 ARP 캐시 삭제
cmd 관리자권한 실행
netsh interface ip delete arpcache

# Docker

컨테이너의 조건

Not negotiable: They have to run on a single host. Okay, so two computers cannot run a single container.

Clearly: They are groups of processes. You might know that Linux processes live inside a tree structure, so we can say containers must have a root process.

Okay: They need to be isolated, whatever this means in detail.

Not so clear: They have to fulfill common features. Features in general seem to change over time, so we have to point out what the most common features are.
