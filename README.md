Avaliação da Sprint 1 - PB Compasso UOL
Nome: Maria Idalina da Silva e Pinto


Tema: Segurança de redes: Conheça as vulnerabilidades de servidores e clientes 
1. O que é um ataque DDoS e como posso me proteger?
   É um tipo de ataque malicioso, que tem por objetivo sobrecarregar ou bombardear com um grande número de requisições a capacidade da aplicação, do servidor ou da rede, tornando o alvo indisponível para os seus usuários reais. Algumas medidas podem evitar os ataquen DDoS, entre eles: monitorar o tráfego de dos servidores, utilizar ferramentas anti DDoS, configurar corretamente o servidor, aumentar a largura de banda quando for viável, bloquear IPs de determinado país quando verificada invasão estrangeira.

2. Por que o firewall é uma ferramenta muito importante de proteção?
   Porque é uma ferramenta que monitora e previne a saída de dados confidenciais ou pessoais pela rede, bloqueando ataques. Ele funciona como um filtro entre o equipamento e sua conexão com a internet.


Tema: Git e GitHub 
3. Explique de forma sucinta, o fluxo e envio de um arquivo novo para o 
repositório do projeto.
   Com o repositório já existente no GitHub, inicializamos o mesmo no repositório local, abrindo a pasta do projeto e em seguida o Git Bash. Posteriormente, utiliza-se o comando -git init, e temos a confirmação de que foram conectados os dois repositórios. Em seguida, utilizamos o comando git commit -m  e  git add (nome do arquivo). Verificamos com git status , Adicionamos o arquivo à Branch através de git branch -M main e finalmente conectar com o GitHub usando o comando git remote add origin link. Finalizamos com git push -u origin main.

4. Descreva sobre os ganhos de se utilizar a funcionalidade da branch do git.
   Possibilita que múltiplos desenvolvedores atuem em um projeto, sem que um interfira no trabalho do outro; outra vantagem é a manutenção de pequenas partes do código, ao invés de comprometer o cíkdigo inteiro e assim otimizar o fluxo de trabalho.

5. Explique a diferença entre criar o repositório na nuvem e iniciar o repositório a 
partir de um código existente local.
   O repositório local é algo mais pessoal e mais simples, criado em nossa máquina. Já o repositório em nuvem, permite o compartilhamento entre vários desenvolvedores, em projetos mais complexos, onde é possível compartilhamento e versionamento de código.

6. Qual a diferença entre Git e GitHub
   Git é um Software livre criado para controle de versão de arquivos, onde diversas pessoas podem contribuir simultaneamente. Já o GitHub, é uma espécie de rede social, é uma plataforma de armazenamento de projetos, onde os desenvolvedores disponibilizam para que outras pessoas os vejam.


Tema: Fundamentos de Agilidade: seus primeiros passos para a transformação ágil 
7. Quais as principais diferenças entre o modelo ágil e o waterfall (modelo em 
   cascata)?
   Waterfall- metodologia mais tradicional, com escopo rígido, linear e pré-definido, uma etapa só funciona quando a anterior termina.  Foco no projeto.
   Modelo ágil- metodologia flexível,adaptável conforme as necessidades do projeto em questão, escopo dividido em módulos de curta duração, agregando mais valor a cada entrega, possibilitando ajustes ou correções sempre que necessário. O foco é o cliente.
   
8. Quais são as 3 perguntas que devem ser respondidas na Daily?

9. Qual o intuito das seguintes cerimônias?
• Daily : identificar o que já foi feito, o que se pode fazer e os possíveis gargalos encontrados.
• Planning: é fazer com que o time planeje o que será feito na próxima Sprint.
• Refinamento: é o processo contínuo, com participação dos desenvolvedores e o Product Owner, onde os itens são dispostos em uma lista de prioridades com estimativas de complexidade e esforço necessários para sua execução.
• Review: é o momento de validação da entrega, é o momento de feedbacks, onde verfificamos se os critérios foram todos executados conforme o escopo do projeto.
• Retrospectiva: é a reunião onde o objetivo é realizar a melhoria contínua. É quando se avalia, ao final da Sprint, o que não deu certo, o que deu certo e o que precisa ser melhorado no projeto.

10. O que é a estimativa na metodologia ágil?
    É uma forma estimar as histórias através de um sitema de pontuação (Fibonacci), possibilitando mensurar valor, esforço e risco a cada Sprint.

Tema: Fundamentos HTTP
11. O que é o protocolo HTTP? Qual a diferença entre HTTP e HTTPS?
    HTTP é um protocolo Cliente-Servidor, é a base de trocas de dados na Web, baseado em requisições enviadas a um servidor, fornecendo uma resposta através da inserção da URL no navegador.
    O protocolo HTTPS tem algumas diferebças do HTTP no que diz respeito à Segurança. Ele utiliza uma camada adicional (SSL/TLS) que é baseado em ciptografia, onde é possível verificar a 
    credibilidade do servidor por meio dos certificados digitais.

12. Cite 4 métodos HTTP
    GET- solicita a representação de um recurso que retorna dados.
    POST - submete uma entidade a um recurso que causa mudança de estado no recurso ou no servidor. 
    DELETE - remove um recurso específico.
    PATCH - aplica modificações parciais em um recurso.