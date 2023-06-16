# Comando a utilizar:

### Fazer o Docker build assim:
docker build -f Dockerfile.dev -t norisjunior/frontend:latest .

o container resultante foi: a51e2bd75d89401324

### Subir a aplicação assim:
docker run -p 3000:3000 -v /home/node/app/node_modules -v /home/noris/stephengrider/prod/frontend:/home/node/app a51e2bd75d89401324