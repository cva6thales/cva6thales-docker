# Installation
## Install Docker & Git

```bash
apt update
apt install -y docker docker-ce docker.io git
```

## Clone the Repositorie

```bash
git clone https://github.com/cva6thales/cva6thales
```

## Install Docker Conatiner

```bash
cd cva6tahles
./install
```

## Execute Docker Container

```bash
docker exec -ti riscv-debian-buster:ci-platform-verilator-spike bash
```

