# Arquitetura Hexagonal
Conceitos, vantagens e desvantagens

A arquitetura hexagonal (portas e adaptadores) tem com essência a separação das regras de negócio via "core", camadas de "portas" (normalmente interfaces) e "adaptadores" (normalmente classes). Permitindo invocações partindo do CORE (conhecidas como internas - inbunds) ou externas/outbounds (originando de browsers, APIs etc).

- Vantagens:
1) Forte desacoplamento;
2) Divisão de responsabilidades;
3) Maior percepção da organização da regra de negócio;
4) Mais fácil manter, alterar e testar;
5) Grande potencial de aderência à projetos modernos, por exemplo microsserviços.

- Desvantagens:
1) Maior verbosidade;
2) Menor reaproveitamento de código (boilerplate);

- Portas: interfaces --> Notificações, persistência, administração, eventos diversos do negócio etc).
  
- Adaptadores: classes --> SMS, E-mail, banco de dados, configurações diversas, arquivos, logins testes, interface do usuário etc.

Fonte: curso Microsserviços (Michelli Brito).

*Quer conversar sobre o assunto? Envia um chat no linkedin =D. 
