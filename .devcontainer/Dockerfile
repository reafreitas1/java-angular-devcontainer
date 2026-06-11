# Usando Bookworm, que é mais recente que o Bullseye e evita o erro de chaves GPG
FROM mcr.microsoft.com/devcontainers/java:17-bookworm

# Instalação simplificada sem dar update manual pesado, o dev container já faz isso
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends curl git ca-certificates