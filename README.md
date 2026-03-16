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

## 2) Definição de usuários:

| Tipo de Usuário | Descrição | Objetivos | Experiência Técnica |
|---|---|---|---|
| Hóspede | Pessoa viajante que busca um lugar para dormir e relaxar. | Pesquisar e comparar preços, visualizar quartos e seus diferenciais em fotos, gerenciar sua reserva e avaliar a mesma. | Baixa |
| Administrador do Estabelecimento | Dono ou gerente que busca cadastrar e gerenciar seu estabelecimento. | Cadastrar e gerenciar seu estabelecimento e suas dependências como quartos, definir disponibilidade e preços, responder avaliações. | Média |
| Administrador do Sistema | Responsável pela gestão do sistema (StayHub). | Garantir o funcionamento da plataforma e monitorá-la, gerenciar usuários e estabelecimentos. | Baixa |

## Restrições de projeto:

- Deve focar apenas em viagens, ou seja, o objetivo não é focar em pontos
turísticos por exemplo, mas sim nas estadias

## Riscos de projeto:

Como é uma aplicação que possui um público-alvo grande, devemos evitar:
- **Baixa disponibilidade:** Caso a aplicação fique fora do ar, temos o risco
de potencial prejuízo financeiro, além da reputação cair com os clientes.
- **Latência alta nas requisições:** É importante que a performance da aplicação
não seja comprometida, uma vez que caso a aplicação da concorrência seja mais
responsiva, podemos perder clientes.
- **Regras de negócio mau definidas:** Caso as regras de negócio estejam mau
definidas, não ficará claro o que é prioritário ou não na aplicação. Além disso,
o objetivo principal corre o risco de ficar ofuscado ou incerto.
- **Risco legal:** Não podemos pegar qualquer estadia sem a permissão das empresas
que a fornecem, portanto, é necessário acordar com as empresas como podemos
disponibilizar as suas estadias.
