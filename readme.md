# Download de cursos de basicamente todas as plataformas existentes (conforme o acesso for obtido de forma legal)

## Este projeto está sendo refatorado do zero e em breve o código aqui será atualizado.
Atualmente funciona parcialmente para a Hotmart, em breve ele será melhorado muito, estou para liberar em questão de tempo.  
E da legalidade, leia o arquivo citado abaixo, aviso.html.

### Patrocinadores do projeto
***Financeiros recebem suporte prioritário e pessoal do desenvolvedor responsável, também aproveitam de descontos para projetos próprios e possuem outros benefícios**  
Github [![Sponsors](https://img.shields.io/github/sponsors/katomaro)](https://github.com/sponsors/katomaro)  
Demais contribuidores (financeiros e de dados) podem ser encontrados no arquivo [CONTRIBUTIONS.json](https://github.com/katomaro/katomart/blob/master/CONTRIBUTIONS.json) localizado na raiz do repositório.

## AVISO IMPORTANTE / DISCLAIMER

NENHUMA MARCA aqui citada tem relação direta com os contribuintes, e/ou código. Este trecho de código é extra-oficial a qualquer serviço, e tem como alvo o uso pelos clientes interessados dado seus próprios motivos. A pirataria não é apoiada e será denunciada quando identificada. Nenhuma medida será aplicada para burlar sistemas identificatórios que as plataformas implementem.

AOS USUÁRIOS: Fica o aviso, **fazer o uso deste programa pode violar o seu CONTRATO com a plataforma alvo**, porém, saiba que **desde que você tenha o direito de consumo de caráter permanente, você está dentro do seu direito de fazer tal consumo da forma que bem entender (isso inclui o download/cópias DESDE QUE não seja redistribuído)**. Deixo anotado que nos últimos anos, acompanhei várias pessoas usando códigos antigos de autoria minha sobre o meu nome de usuário (@Katomaro) dentro dos termos citados acima, e os únicos casos de suspenção que presenciei foi quando resolveram abusar das requisições para acelerar o download, o que fez parecer um ataque de Denial Of Service, afinal, qualquer um que entender o mínimo de Stream de vídeos sabe que é anormal ocorrer a requisição de N segmentos de forma simultânea. Ou pessoas que realizaram o compartilhamento dos arquivos sem ter direito para tal, configurando o violação de direitos autorais (crime).

Em resumo... **Este repositório não é oficial de nenhuma marca** e apenas o projeto de um estudante que quis baixar um curso que tem a licença, de consumo, pediu autorização para o autor do curso para fazer a ferramenta inicial e publicar, um monte de gente achou útil e assim seguiu fazendo para demais plataformas. E novamente, se você tem o direito de consumo, você pode *enfiar onde quiser e quantas vezes você quiser* que nenhuma plataforma pode fazer nada contra você, eles podem optar em não te prestar mais serviços posteriormente, a menos que você compartilhe o conteúdo (que como citado configuraria crime), nada vai acontecer com você.

# SEMPRE QUE EXECUTAR O APLICATIVO LEIA O AVISO NA PÁGINA PRINCIPAL (/home)
Você pode o ler de uma forma crua diretamente [acessando este arquivo do repositório (AVISO.HTML)](https://github.com/katomaro/katomart/blob/master/AVISO.html)

## Motivo?

Atualmente existe uma moda de publicarem cursos no formato EAD, e está tudo bem. Porém, estas mesmas plataformas tentam bloquear o ato de download do conteúdo. Oras, se eu tenho o conteúdo vitalício e permanente, qual o dano que eu estou causando ao proprietário?  
Além disso, se eu tenho o direito de consumo, eu não posso ser obrigado a consumir tal material por um meio específico, se o mesmo é acessível a partir de um navegador. **Os aplicativos aqui encontrados apenas replicam a lógica de acesso aos materiais e salvam para o disco local sem fazer o uso de exploits nem nada do tipo**. Pense bem, é inviável acessar mídias em 4k/8k a partir de dados móveis, e aplicativos móveis **coletam dados adicionais sobre você, que eles podem vender ou usar em campanhas de marketing para te fazer gastar**, é um descaso com a LGPD.  
E eu como desenvolvedor te garanto, é extremamente fácil criar uma API REST e um tema da THEME FOREST e criar uma plataforma de cursos, custa menos de 300 reais fazer isso. Muitas sequer tem sede.

## Como instalar e executar
### STATUS DO DESENVOLVIMENTO: Testando contra a plataforma onde tudo começou... :fire:
Este guia não cobre usuários Linux, se você usa linux, você deve ter uma noção do que está fazendo.  
Para que o programa funcione, será necessário instalar o interpretador do Python, e opcionalmente, o FFMPEG. Vamos para a instalação do Python (tutorial em vídeo de tudo quando o projeto for "finalizado", mas lembre-se do grupo de suporte lá em baixo).  

Passo 1: Download do Python

1. Acesse o site oficial do Python em [python.org](https://www.python.org/).
2. Navegue até a seção **Downloads** e selecione **Windows**.
3. Clique em **Download Python** seguido pela versão que você deseja instalar, que seja superior à 3.10. [Versão recomendada 3.12.2 64-bits](https://www.python.org/ftp/python/3.12.2/python-3.12.2-amd64.exe).  

Passo 2: Instalação do Python

1. Localize o arquivo de instalação que você baixou e dê um duplo clique nele.
2. Marque a opção **"Add Python x.x to PATH"** na parte inferior da janela de instalação para adicionar Python ao PATH do sistema. Se você não fizer isso, você não conseguirá executar o programa, e a solução mais fácil é você **reinstalar** o Python.
3. Clique em **Install Now** para começar a instalação.
4. Após a conclusão da instalação, clique em **Close** para finalizar o assistente de instalação.  

Para verificar se o Python foi instalado corretamente:

1. Abra o Prompt de Comando (cmd).
2. Digite `python --version` e pressione **Enter**. Se o Python estiver instalado corretamente, você verá a versão do Python exibida no terminal.  

Agora que o Python está instalado, você pode baixar e executar projetos Python. Aqui está como fazer isso:

1. Baixe o arquivo zip do repositório do projeto clicando no botão verde lá em cima e em [baixar zip, aqui está um atalho](https://github.com/katomaro/katomart/archive/refs/heads/master.zip).
2. Extraia o arquivo zip em uma pasta de sua escolha, preferencialmente, em um caminho curto (como C:\Katomart).
3. Abra o Prompt de Comando e navegue até a pasta extraída usando o comando `cd caminho\para\a\sua\pasta`.
4. Execute o comando `pip install -r requirements.txt` para instalar as dependências do projeto.
5. Finalmente, execute o projeto com `python katomart.py`.
6. Siga as instruções da tela, que é ultimamente abrir o seu navegador e ir até o endereço: `http://localhost:6102/`. Após dar o aceite nos termos anti-pirataria (que não são enviados para nenhum local, apenas ficam em registro na sua máquina, pode verificar o código), você irá ver a interface do Katomart e poderá interagir com o aplicativo.

## Contribuindo
### Código
Peço que tente seguir o padrão de mensagens de commits apresentado. Se possível, cada commit **deve alterar apenas um arquivo**, e o código deve se auto-documentar da melhor forma possível, mas não precisa ser rigoroso. **Não inclua um card de desenvolvedor se for apenas uma PR de bugfix não crítico, ou erros de grafia e coisas do gênero**, as próprias commits mostram o que cada um fez, aquela seção é destinada para pessoas que contribuem com código para o projeto desde **Julho de 2021**.
### Relatando problemas
Se encontrar um problema, utilize a aba [ISSUES](https://github.com/katomaro/katomart/issues) para reportar (antes de reportar, verifique que não existe outra issue parecida com a sua, obrigado).
### Custeando o desenvolvimento
Para que este aplicativo seja feito, é necessário que a pessoa produzindo o código tenha o acesso à plataforma alvo em seu nome (se não configuraria violação de direitos autorais). Existe uma brecha nisso onde você pode isentar o desenvolvedor e ainda assim passar informações da plataforma para o mesmo, abra uma issue solicitando assistência para editar o arquivo HAR que você deve gerar como descrito neste [artigo da Wiki]() e aguarde o [@katomaro](https://github.com/sponsors/katomaro) responder. Desenvolver esta aplicação leva inúmeras horas de suporte à usuário, correção de bugs, estudo de tecnologias especializadas e implementações. Caso queira ajudar a custear isto tudo e se tornar um patrocinador, você pode utilizar o próprio [Github Sponsors](https://github.com/sponsors/katomaro) para o meu perfil porém eu acredito que ele cobre em dólar, à direita deste texto existem outras formas de contribuir também em reais (tais como pix e etc), todo valor faz diferença. Ao rodar a aplicação, você também pode ver os desenvolvedores relevantes para o aplicativo e suas responsabilidades, e como você pode contribuir para eles, basta ir até a página de [Suporte](http://127.0.0.1:6102/support) e identificar os cards de cada desenvolvedor. E ah, caso decida patrocinar financeiramente, por favor, siga as instruções de enviar um e-mail informando se tem alguma mensagem para compartilhar (pode ser propaganda, desde que legal), e como você quer que seu nome apareça na lista de contribuidores. O mesmo vale para quem contribuir com informações de plataforma, exceto que estes não recebem suporte prioritário nem podem incluir mensagens.

### Suporte
**Patrocinadores tem suporte prioritário  e pessoal comigo para qualquer finalidade dentro da lei**: Tornou-se um patrocinador? Entre em contato em [sponsors@katomaro.com](mailto:sponsors@katomaro.com).  

Você pode obter ajuda comunitária no [Grupo do Telegram **(AVISO: O Grupo não é moderado e nem voltado para um assunto específico)**](https://t.me/katomart). Caso você necessite de ajuda com algo que **trate com dados sensíveis**, entre em contato comigo através do meu email: [github@katomaro.com](mailto:github@katomaro.com), ou diretamente em minhas contas pessoais do Telegram e Discord através do usuário **@katomaro**. Solicitações de ajuda pessoal de não-patrocinadores não são prioritárias, e existe toda uma documentação para ser lida, provavelmente a sua pergunta está respondida em algum lugar.


### Tiers de Suporte

1) Nível 0: Não contribuiu com nada, mas está usufruindo do projeto, assim como todos que contribuíram. NADA ficará atrás de um muro de pagamento, isto não é venda de serviço!  

2) Nível 1: Contribuiu com pelo menos de 35,00 Reais, ou fez uma contribuição pequena de código, ou ajuda as vezes no grupo da comunidade. Recebem: Suporte prioritário 1:1 comigo. Pode parecer pouco ou bobo, mas dependendo da época eu recebo mais de 100 chats por dia. É importante ressaltar que o Katomart é feito para funcionar e tem uma documentação sendo elaborada e um grupo comunitário para se ajudarem, você apenas me dá um motivo para eu dedicar parte do meu tempo exclusivamente para você, dentro do possível, ao invés de eu encaminhar para documentação, é muita gente para eu lidar (não coleto dados, mas estimo entre 60 mil a 150 mil usuários do software historicamente, com base no que vejo comentarem nos grupos e os causos de plágio e vendas não autorizadas documentados).  

3) Nível 2: Contribuiu com pelo menos 150,00 Reais, ou fez uma contribuição considerável de código, ou ajuda frequentemente no grupo da comunidade. Recebem: Acesso à um gitlab privativo meu que possui o código cru de cada plataforma explorada por mim, ideal para quem tem seus projetos pessoais e querem ver o que plataformas aleatórias praticam no mercado, de uma forma digerida. ESTE REPOSITÓRIO CONTÉM APENAS CÓDIGO E COMENTÁRIOS PONTUAIS.  

4) Nível 3: Contribuiu com pelo menos 250,00 Reais. Recebem: Acesso à um gitlab privativo meu que possui o código cru de cada plataforma explorada por mim, DIFERENÇA DO NÍVEL ANTERIOR: Aqui você encontrará toda a documentação e explicação verbosa de cada trecho de código elaborado por mim e retornos de plataforma. Também neste repositório PODEM existir endpoints vulneráveis e documentadas que podem ser exploradas que eu descobri. IMPORTANTE: Eu sempre denuncio essas falhas para as plataformas, e publicaria essas falhas 1 mês após realizar minha denúncia, com uma print validando que eu tentei contato com eles expondo a falha, se eles não corrigiram, bem, qualquer um poderia encontrar, peço que não a utilize para fins maliciosos. Um exemplo prático: Nos meus tempos primordiais eu sabia que podia baixar todo o conteúdo da :fire: simplesmente enviando a ID do vídeo para a endpoint de anexo deles, você baixava o arquivo original inclusive, nem era o processado para HLS, eles demoraram 3 meses para corrigir essa falha. Esse Tier é ideal para quem quer o equivalente de aula comigo mas já tem alguma experiência com programação.  

5) Nível 4: Contribuiu com pelo menos 300,00 Reais. Recebem: O mesmo do Tier 3, além de ter o direito de 1 encontro mensal comigo para eu te auxiliar em um projeto seu. Além disso, em diversos casos, irá incluir um vídeo privado de eu explorando a plataforma ao vivo para acompanhar o processo lógico   

6) Nível 5: Contribuiu com pelo menos 350,00 Reais. Recebem: Desconto fixo de 30% em qualquer projeto que a pessoa quiser pegar comigo como desenvolvedor (não incluso contratos com a minha empresa), e inclui "favorzinhos" (assistência técnica/código que eu vejo que não me toma mais que 30 minutos, ou seja, a maioria)  
