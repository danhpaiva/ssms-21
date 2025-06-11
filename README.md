# ssms-21

Após baixar o bootstrapper, você pode criar um pacote de instalação offline completo. Para fazer isso, abra o Prompt de Comando como Administrador, navegue até o diretório onde você salvou o bootstrapper (por exemplo, C:\Downloads), e execute o seguinte comando:

~~~
vs_SSMS.exe --layout c:\localSSMSlayout --add Microsoft.Component.HelpViewer
~~~

~~~
.\vs_SSMS.exe --layout D:\SSMSlayout --add Microsoft.Component.HelpViewer
~~~

### vs_SSMS.exe: 

Este é o nome do bootstrapper do SSMS que você baixou.

### --layout c:\localSSMSlayout: 

Este parâmetro especifica que você deseja criar um layout local e c:\localSSMSlayout é o diretório onde os arquivos de instalação serão baixados. Você pode alterar c:\localSSMSlayout para o caminho de sua preferência.

### --add Microsoft.Component.HelpViewer: 

Este parâmetro inclui o componente HelpViewer no seu pacote de instalação offline.
Observação: Este passo também requer uma conexão com a internet, pois o bootstrapper baixará todos os arquivos necessários para o diretório especificado. Certifique-se de que o caminho completo da instalação tenha menos de 80 caracteres e que você tenha no mínimo 4 GB de espaço em disco disponível.
