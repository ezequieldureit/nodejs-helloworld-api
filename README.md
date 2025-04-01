# NodeJs, helloworld API for test propouses.

This is a simple API that returns a welcome message.

## Run your local environment

### Clone the repository
```bash
git clone https://github.com/yosoyfunes/nodejs-helloworld-api.git
```

### Install dependencies
```bash
npm install
```

### Run the tests
```bash
npm test
```

### Start the server
```bash
npm start
```

### Make a request
```bash
curl http://localhost:3000
```
# test job

## **Desafio 2**  

### **Requisitos**  
- Jenkins con los plugins: Git, GitHub, NodeJS.  
- ngrok para exponer Jenkins a internet.  

### **Configuración**  
1. **Webhook en GitHub:**  
   - URL: `https://[TU-NGROK].ngrok.io/github-webhook/`  
   - Eventos: `Push` y `Pull requests`.  

2. **Pipeline en Jenkins:**  
   - Clona este repositorio.  
   - Ejecuta `npm install` y `npm test`.  

### **Evidencias**  
![Pipeline exitoso](screenshots/pipeline-success.png)  
![Tests pasando](screenshots/test-results.png)  
