TFM WEB3

Se incluyen los siguientes *notebooks* (Python) para el tratamiento y carga de datos en una base de datos MongoDB llamada **web3_tfm**:  
1. initialization_parms.ipynb      👈🏽
2. load_account_balances.ipynb     👈🏽
3. load_account_transactions.ipynb 👈🏽
4. transaction_optimization.ipynb  👈🏽

Para la ejecución de estos notebooks se requiere:
1. Disponer de ApiKey de Etherscan (https://docs.etherscan.io/)
2. Disponer de ApiKey de Infura (https://docs.infura.io/api)
3. Tener una base de datos de MongoDB accesible

Ello deberá ser parametrizado en el fichero .env (Existe un fichero .env.demo que puede servir de referencia) bajo los siguientes valores:
1. URL_INFURA=https://mainnet.infura.io/v3/xxxxxxxxxxxxxxxxxxxxxxxxx
2. APIKEY_ETHERSCAN=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
3. MONGODB_SERVER=mongodb://localhost:27017/

Otra alternativa es carga las colecciones de la base de datos de MongoDB utilizando los ficheros ***web3_tfm.**** disponibles en el directorio ***\data\load_mongo***

Indicar que, debido al gran tamaño del fichero *web3_tfm.account_transactions.json* (900 Mb), este ha sido comprimido en formato ZIP y particionado en trozos de 100 Mb para poderlo subir a GitHub

En el siguiente link se puede descargar el cuadro de mando creado con PowerBI para la viualización de los datos (no se ha podido almacenar en GitHub por ocupar más de 100Mb):
- **[Cuadro_de_mando.pbix](https://drive.google.com/file/d/1HHcurbpmCao7ZdjpYYFwWYYvgg3mFHQQ/view?usp=sharing)** 👈🏽

En caso de que no se disponga de PowerBI o no sea posible descargar el fichero .pbix, también se incluye el cuadro de mando en formado PDF:
- **Cuadro_de_mando.pdf**