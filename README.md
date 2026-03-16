# Plataforma de Reserva de Hotéis (StayHub)

## 1) Visão Geral do Produto:

### 1.1) Oportunidade de Negócio e Declaração do Problema

- **Problema principal**: Viajantes tem dificuldade de encontrar e comparar 
hospedagens, hotéis e pousadas, e por conta disso, precisam de meios para 
pesquisar quartos e gerenciar reservas.
- **Causas do problema**: Vasta quantidade de opções, preços variáveis,
informações espalhadas por diferentes sites. Isso causa um desgaste mental
ao pesquisar por hospedagens para viagens evitando o maior custo.
- **Oportunidade de negócio**: A plataforma StayHub conecta viajantes a 
hospedagens, com o principal objetivo de permitir ao viajante encontrar 
acomodações, comparar opções, fazer reservas e gerenciar estadias de 
uma maneira simples.
- **Impacto potencial**: A plataforma pode impactar positivamente os usuários,
pois ao centralizar todas as opções de preços e estadias, evita-se a 
necessidade de navegar entre vários sites para procurar uma hospedagem ideal 
em um lugar. Além disso, a aplicação tem potencial de ser uma ferramenta de
gerenciamento, ou seja, não seria necessário o usuário anotar as opções mais
interessantes para ele.

### 1.2) **Perspectiva do produto**:

- **Contextualizar o produto no ambiente atual**: o StayHub se encaixa no ecossistema tecnológico como uma alternativa a clientes que não querem ter que procurar extensivamente a hospedagem ideal através de diversas plataformas diferentes.
- **Público-alvo:** A plataforma tem como público alvo qualquer pessoa que
deseja viajar. A ideia é atender estadias tanto para lazer quanto para 
negócios.
- **Proposta de valor**: O principal benefício do StayHub aos usuários e sua diferenciação dele em relação a outras soluções existentes é a centralização  de opções de preços e estadias, evitando ter que navegar por diversas plataformas e sites diferentes para encontrar uma hospedagem ideal.

### 1.3) **Capacidades do Produto**
- **Principais funcionalidades:** 
  - **Busca de hospedagens:** busca hospedagens por destino, datas e número de hóspedes, contribuindo para atender as necessidades específicas de cada usuário.
  - **Comparação:** compara preços, fotos, comodisades e avaliações, evitando comparações manuais pelo usuário em diferentes plataformas.
  - **Reserva online:**: faz a seleção de quarto e pagamento.
  - **Avaliações:** mostrar comentários de hóspedes prévios, ajudando na decisão de hospedagem de clientes futuros.
- **Wireframes baixíssima resolução: Fazer esboços de fluxos principais dos usuários**:
- **Características de qualidade:** Usabilidade simples que seja compreensível por usuários de diferentes perfis, segurança principalmente em transições financeiras e código facilmemente compreensível com alta manutenibilidade

### 2) **Definição de usuários:**

| Tipo de Usuário | Descrição | Objetivos | Experiência Técnica |
|---|---|---|---|
| Hóspede | Viajante que busca um lugar para dormir e relaxar. | Pesquisar e comparar preços, visualizar quartos e seus diferenciais em fotos, gerenciar sua reserva e avaliar a mesma. | Baixa |
| Administrador do Estabelecimento | Dono ou gerente de um estabelecimento. | Cadastrar e gerenciar seu estabelecimento e suas dependências como quartos, definir disponibilidade e preços, responder avaliações. | Média |
| Administrador do Sistema | Responsável pela gestão do sistema (StayHub). | Garantir o funcionamento da plataforma e monitorá-la, gerenciar usuários e estabelecimentos. | Baixa |

### 3) **Restrições de projeto:**
| Restrição   | Descrição |
| ----------- | ----------- |
| Tecnológica | Desenvolver a plataforma como uma aplicação web que seja capaz de se integrar com serviços de pagamento externos, envio de e-mails e localização de estabelecimentos|
| Segurança   | Garantir a segurança de dados sensíveis dos usuários, como informações de login e dados de pagamento. Também garantir que os usuários não possam acessar dados de outros hóspedes |
| Controle de reservas |Deve-se garantir que um mesmo quarto não seja reservado por mais de um hóspede durante o mesmo perídio |
| Política de Cancelamento| Cada estabelecimento possuem suas próprias regras de cancelamento que devem ser aplicadas pelo sistema corretamente
| Avaliações | Apenas hóspedes reais podem registrar avaliações em estabelecimentos

### 4) **Riscos de projeto:**
| Risco     | Descrição |
| ----------- | ----------- |
| Título | Reserva duplicada|
| Impacto   | Alto |
| Ação de Mitigação  | Garantir que o banco de dados não registre mais de um cliente em uma hospedagem |
| Plano de Contingência| Remover o registro do segundo cliente da hospedagem e oferecer um desconto para o mesmo|

| Risco     | Descrição |
| ----------- | ----------- |
| Título | Preços variáveis|
| Impacto   | Alto |
| Ação de Mitigação  | Verificar o valor do preço constantemente para verificar se ele está de acordo com a época do ano e demanda |
| Plano de Contingência| Caso o preço da hospedagem fosse mais caro que o exibido, não cobrar o cliente. Senão, deixar o cliente permanecer na hospedagem pelo custo que pagou inicialmente |

| Risco     | Descrição |
| ----------- | ----------- |
| Título | Política de cancelmaneto|
| Impacto   | Alto |
| Ação de Mitigação  | Deixar claro na plataforma as políticas de cancelamento para o usuário antes do confirmar sua hospedagem|
| Plano de Contingência| Caso as políticas de cancelamento não sejam seguidas, cobrar o valor de pagamento do cliente|

| Risco     | Descrição |
| ----------- | ----------- |
| Título | Avaliações falsas|
| Impacto   | Alto |
| Ação de Mitigação  |Incoporar métodos de verificação na plataforma que verificam se o usuário realmente permaneceu na hospedagem|
| Plano de Contingência| Remover as avaliações de usuários falsos|