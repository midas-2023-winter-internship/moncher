### Clone and update submodule

```bash
git clone https://github.com/midas-2023-winter-internship/moncher.git
git submodule update --init --recursive
```

### Pull submodule
```bash
git submodule update --recursive --remote
```

### Run server

```bash
docker-compose up -d
```