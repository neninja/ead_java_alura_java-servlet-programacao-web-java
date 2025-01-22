# ead_java_alura_java-servlet-programacao-web-java

## Setup com Podman

- Inicie o Podman

```sh
podman machine init
podman machine start
```

- Inicie o ambiente

```sh
podman-compose up
```

> Caso precise mexer nos containers, pare eles com `podman-compose down --remove-orphan` e, após modificações, inicie novamente com `podman-compose up --build`
