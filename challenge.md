# Challenge Answers

1. Installed and ran htop. It displays running processes and system resource usage.
   Commands: sudo apt install -y htop, htop

2. Apache2 version offered by Ubuntu: [write version from apt show].
   Command: apt show apache2

3. Installed packages: [write your count].
   Command: apt list --installed | wc -l

4. Docker Alpine output: Hello from Alpine.
   Command: sudo docker run --rm alpine echo "Hello from Alpine"

5. Docker key: /etc/apt/keyrings/docker.asc
   Docker source: /etc/apt/sources.list.d/docker.sources

6. Removed htop and verified it was unavailable.
   Commands: sudo apt remove -y htop, hash -r, htop
