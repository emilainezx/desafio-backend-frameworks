# Desafio back-end frameworks

Repositório criado para a atividade da disciplina Back-end Frameworks. O objetivo é criar e mostrar o conhecimento sobre Arquitetura em Camadas e a Classificação por Linguagens através de dois frameworks diferentes.

# Node.js/Express VS Java/Spring Boot

O Node.js tem maior facilidade de configuração inicial, utiliza JavaScript e segue um modelo single-threaded que consome pouca memória. Já o Spring Boot é mais completo e voltado para aplicações corporativas, porém com maior verbosidade do código e configuração mais elaborada. Na gestão de dependências, o Node usa o npm com o package.json, enquanto o Spring Boot usa o Maven com o pom.xml de forma automática. No geral, o Express é mais simples para começar, enquanto o Spring Boot entrega mais recursos prontos, porém com maior complexidade.

# Explicação da Arquitetura em camadas

No desenvolvimento back-end, a aplicação é organizada em três camadas principais: Model, Controller e Routes. O Model cuida dos dados e das regras de negócios, armazenando e recuperando informações. O Controller recebe pedidos do usuário e comunica-se com o Model, enquanto as Routes direcionam as solicitações para o Controller certo. Essa separação ajuda na hora de dar manutenção e reaproveitar código em outras partes do projeto, onde o cliente faz uma requisição HTTP, as Routes identificam qual Controller deve tratar aquela requisição, o Controller consulta o Model para buscar ou salvar os dados e devolve a resposta ao cliente.