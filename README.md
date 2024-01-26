Projeto HTML,CSS,JS para criar um spotfy #ImersãoFrontEnd e #Alura


Banco de dados em json para propositos de aprendizado.

npm install -g json-server@0.17.4

json-server --watch api-artists/artists.json

se der esse erro:
json-server : O arquivo C:\Users\Matheus\AppData\Roaming\npm\json-server.ps1 não pode ser carregado porque a execução de scripts foi desabilitada neste sistema. Para obter mais informações, consulte 
about_Execution_Policies em https://go.microsoft.com/fwlink/?LinkID=135170.
No linha:1 caractere:1
+ json-server --watch api-artists/artists.json
+ ~~~~~~~~~~~
    + CategoryInfo          : ErrodeSegurança: (:) [], PSSecurityException 
    + FullyQualifiedErrorId : UnauthorizedAccess
usar esses comandos:

  Get-ExecutionPolicy
  Set-ExecutionPolicy RemoteSigned

