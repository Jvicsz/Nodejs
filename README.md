!para ativar o Nodejs vc precisa estar com ele instalado!

Abra o terminal
"Crtl+Alt+T"

Redirecione sua saida de comando para a patsa onde esta instalado
"cd ParaOndeEsta/NodeJS-ENV"

Depois de instalar para ativar digite:
"source ./nodejs-env/bin/activate"

Após ativado abra a pasta src 
"CD NODEJS-ENV/SRC"

Abra o arquivo index.js
"sudo nano index.js"

Copie o esse codigo
"var http = require('http');

http.createServer(function (req, res) {
  res.writeHead(200, {'Content-Type': 'text/plain'});
  res.end('João Victor de Souza Cravalho 20/09/2023');
}).listen(8016);
"

Por fim ative o arquivo
"node index.js"

no navegador de sua preferencia e digite

"localhost:8016
