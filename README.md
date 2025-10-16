# warracker
Control de garantías - Docker compose


## Clona el repositorio
```
 git clone https://github.com/mclitos/warracker
```
Entra a la carpeta
```
cd warracker
```
Edita el docker-compose.yaml con contraseñas seguras si no lo vas a usar para pruebas y tambien cambia el secret key
```
sudo nano docker-compose.yaml
```
Para SECRET_KEY crea una llave puedes usar este comando
```
openssl rand -base64 32
```
Levanta el contenedor
```
docker compose up -d
```
## Ver en:
"http://localhost:8200" o "ip:8200"
