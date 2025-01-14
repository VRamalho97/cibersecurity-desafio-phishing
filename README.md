
#Phishing para capturar senha de uma pagina da internet

Usaremos o site do Instagram como exemplo.
#Ferramentas utilizadas:
  Kali Linux (https://www.kali.org/)
 Setoolkit (Ferramenta pré-instalada no Kali Linux)

Pontos Importantes:

  Caso esteja usando uma VM, certifique-se que a configuração da rede esteja no modo: Bridged Adapter(Inglês) ou Placa de modo Bridge(Português).
  Funcionará para os dispositivos na mesma rede.
  Ao clonar a pagina deve ser clonado a pagina onde digita o login e senha.

Resumo (Passo-a-passo): Configuração da ferramenta setoolkit para construção do Phishing no Kali Linux:

  Acesso root: sudo su
   Iniciando o setoolkit: setoolkit
   Tipo de ataque: Social-Engineering Attacks
   Vetor de ataque: Web Site Attack Vectors
   Método de ataque: Credential Harvester Attack Method
   Método de ataque: Site Cloner
   Obtendo o endereço da máquina: ifconfig
   URL para clone: http://www.instagram.com
   Enviar o IP da maquina para alguém

Detalhamento (Passo-a-passo): Configuração da ferramenta setoolkit para construção do Phishing no Kali Linux: 

01 - Acesso root no modo administrador: aplicar o comando sudo su, em seguida vai pedir para digitar a senha do administrador.
![1](https://github.com/user-attachments/assets/0864a756-70fa-4aa4-94d0-e01467fb9389)



02 - Em seguida, iniciar a ferramenta setoolkit com o comando: setoolkit. Ao acessar pela primeira vez, vai solicitar para aceitar os termos da ferremanta. Então, digite YES.
![4](https://github.com/user-attachments/assets/620ffa2a-d402-464e-8adc-f7dc6324a18c)



03 - Vai abrir a ferramenta com as opção, portanto, selecione a opção: 01) Social-Engineering Attacks.
![2](https://github.com/user-attachments/assets/36beeb9c-74d1-445b-b3a8-1226b5f521a3)



04 - Seguindo com as configurações, selecione: 2) Web Site Attack Vectors.
![11](https://github.com/user-attachments/assets/dd709e34-bf8f-4316-8818-ff732d293758)



05 - Agora, selecione a opção: 3) Credential Harvester Attack Method .
![5](https://github.com/user-attachments/assets/a201a586-47cd-436c-a26b-5be14f5a5cb5)


06 - Mais uma configuração, selecionar a opção: 2) Site Cloner.
![6](https://github.com/user-attachments/assets/a5c090e6-1d25-4fec-91c2-5eb6a334ced9)


07 - Para seguir com a configuração, neste passo, a ferramenta identifica o IP que está rodando. O Setoolkit, vai usar essa maquina como um servidor receber o login e senha rackeada. Então, mantém como está é apenas clicar no botão Entrer. Você vão perceber que vai apresentar o o IP da maquina na tela.

![7](https://github.com/user-attachments/assets/7ddb7219-904f-46c5-81f3-89812f90f4c2)

08 - Nesta opção, digitar a URL que irá clonar, no nosso exemplo é o: http://www.Instagram.com.

![8](https://github.com/user-attachments/assets/2f4cf78e-95fd-4421-8a3b-5838f0b20c1b)

09 - Após clicar no entrer, a configuração está pronta e aguardando alguém clicar e tentar logar no Facebook. Na tela, fica desta forma, aguardando.

![9](https://github.com/user-attachments/assets/46ec860f-9465-4efd-a155-47a84166d35e)

10 - Enviar para alguém o IP que aparece no setimo passo, que é o IP da maquina.
Resultados
Após alguém realizar o login e senha, a tela de comando apresentará alguns textos. Mas em alguma linha dessas vai mostrar conforme a imagem abaixo, com a captura.
![3](https://github.com/user-attachments/assets/cc41d1b6-5c55-4b7c-a5cb-d8d0d26eaa1a)

