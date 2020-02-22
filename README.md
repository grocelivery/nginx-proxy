# Odwrotny serwer proxy Nginx

Kontener z zawierający odwrotny serwer proxy Nginx służący zarządzaniu wieloma wirtualnymi adresami hostów w wewnętrznej sieci Docker.

### Wymagania
```
- Docker
- Docker Compose
```

### Instalacja

Uruchomienie kontenera docker'owego:
```
docker-compose up -d
```
Po zainstalowaniu serwer powinien być dostępny na:
```
localhost:80
```

Narzędzie nginx-proxy zaczerpnięto z publicznego repozytorium GitHub:
[https://github.com/jwilder/nginx-proxy](https://github.com/jwilder/nginx-proxy)
