# PeeNumerical

### Docker

Docker Ram > 3 Gb.

```
docker build -t pee-numer .
```  
```
docker run -itd -v ${pwd}:/app -v /app/node_modules -p 3000:3000 pee-numer
```
