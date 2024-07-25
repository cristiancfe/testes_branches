se aparecer esta mensagem 
<pre>
SyntaxError: Unexpected token '?'
    at Loader.moduleStrategy (internal/modules/esm/translators.js:140:18)
    at async link (internal/modules/esm/module_job.js:42:21)
PS C:\Users\Cristian\Desktop\Testes branches> json-server --watch api-fake.json --port3001
file:///C:/Users/Cristian/AppData/Roaming/npm/node_modules/json-server/lib/bin.js:32
                    default: process.env['PORT'] ?? '3000',
                                                  ^

SyntaxError: Unexpected token '?'
    at Loader.moduleStrategy (internal/modules/esm/translators.js:140:18)
    at async link (internal/modules/esm/module_job.js:42:21)
PS C:\Users\Cristian\Desktop\Testes branches>
</pre>
deve ser atualizado o node para a versão 14 ou mais recente
