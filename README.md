# oauth2-client_credentials-flow
OAuth 2.0 Client Credentials Flow - Lab

1. Clonar este repositorio:
```
git clone https://github.com/jbeutke/oauth2-client_credentials-flow.git
```

2. Abrir archivo ./server.js.
   > En la seccion debajo de la linea '//Step 1: Get the access token' modificar las constantes con los siguientes valores:
   ```
    const Token_Endpoint = `http://localhost:8080/v1/oauth/tokens`;
    const Grant_Type = 'client_credentials';
    const Scope = 'read_write';
    const CLIENT_ID="test_client_1";
    const CLIENT_SECRET="test_secret";
    
    Estos son los parametros que requiere el Authorization Server para entregar un access token. En base a estos parametros se armara un request para solicitarlo.

   ```


2. Desde la terminal, ingresar a la carpeta 'oauth2-client_credentials-flow' y ejecutar 'npm install'.

3. Ejecutar 'npm start'

4. Ingresar a http://localhost:8000 desde el navegador.

5. Seguir las instrucciones.
