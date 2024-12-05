# facebook-login-phishing
O projeto a seguir trata-se de uma ataque phising utilizando a ferramenta setoolkit para clonar a página de login do site, permitindo que o usuário possa obter acesso as credenciais da vitima.

**Como Realizar?** 
1. no terminal do Kali Linux (ou outro SO de sua preferencia que tenha o software instalado) use o comando `sudo su` para entrar em modo root.
2. Use `setoolkit` para acessar a ferramenta, você verá um painel com algumas possibilidades de escolhas.
3. Clique na tecla "1" para selecionar a opção "Enhenharia Social".
4. Clique em "2" para criar um site falso como vetor de ataque.
5. Para criar um ataque ataque de coleta de credenciais, selecione a opção 3.
6. Para nosso objetivo, iremos usar a segunda opção para clonar o site do facebook.
7. Após isso um pequeno servidor será criado em sua máquina, o endereço de IP da sua máquina será sugerido, caso prefira, escolha outro endereço de IP para ser o host, caso contrario, apenas pressione enter. (Importante: Caso esteja usando uma VM, certifique que sua rede pode receber conexões externas).
8. Adicione a URL `http://facebook.com` para criar o site clone.
9. Em um cenário ficticio, você poderia mandar o endereço IP do servidor, para que o vatima acessasse. Dica para camuflar a URL: Dm vez de simplesmente enviar o endereço IP, mande da seguinte forma, `http://facebook.com@[endereço IP] `, o conteúdo a esquerda do "@" será ignorado e o navegador irá redirecionar a vitima ao seu site.
10. Depois que a vitima inserir suas credenciais, o atacante deve observar que o login e senha serão refletidos em seu terminal.

**Lembrando que este conteúdo é meramente informativo e não deve ser utilizado para fins maliciosos**
