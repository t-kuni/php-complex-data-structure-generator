このプロジェクトは没になりました。

理由：　デモを作成した結果、当初、描いていたユースケースは現実的にはそれほど発生しない。

# About

This repository is in development.

# Load map

Phase 1.  
Consider effectiveness through building demo.  

Phase 2.  
Consider the architecture.  

Phase 3.  
Development.


# Build

Build container.

```
docker-compose build app-debug
```

Install php libraries.

```
docker-compose run --rm app composer install
```

Install node packages.  
Run follow command on host OS.

```
npm install
```

# Run

```
docker-compose run --rm app
```

# Boot shell

```
docker-compose run --rm app sh
```