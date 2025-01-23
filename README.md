# ead_java_alura_java-servlet-programacao-web-java

## Setup com Podman

- Inicie o Podman

```sh
podman machine init
podman machine start
```

> Caso precise mexer nos containers, pare eles com `podman-compose down --remove-orphan` e, após modificações, inicie novamente com `podman-compose up --build`

- Inicie o ambiente

```sh
podman-compose up
```

- A cada modificação, compile novamente

```sh
podman-compose exec compiler mvn clean package
```

- Acesse a partir de `http://localhost:8080/ead_java_alura_servlet-prog-web-java`
