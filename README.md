# Image-Reader-API-TS
Repositório usado para para armazenar uma API integrada com o Google Gemini, utilizando NodeJs em TypeScript.

OBS: A api do Google Gemini, modelo "gemini-1.5-pro" trava constantemente e traz informações erradas... Enquanto o moelo "gemini-1.5-flash" é mais preciso e leve/rápido, normalmente sem travamentos, mas "quebra" ao tentar analizar o valor de um medidor do tipo "gas".

OBS: O arquivo .env contendo a GEMINI_API_KEY é necessário para rodar a api, seja local ou através do docker. Propoitalmente, a api é quebrada na falta do arquivo/key.

OBS: A estrutura do Banco de Dados MySql está dentro da pasta "db". Suas informações de conexões estão dentro do "docker-compose.yml".
