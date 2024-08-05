Aluno: Guilherme Caetano Gêa Martins  
Integrado: Grupo 1
# Projeto do Grupo 1 - Relatorio Individual
## Teste de Features _extras_ do Markdown:
O código a seguir renderiza um diagrama Mermaid:

```mermaid
flowchart LR
  A --> B
```

Nota: Com a extenção de plugin nativo do Github a Mermaid, é possivel criar diagramas de nivel simples a detalhado dependendo do nivel de uso.  
Será usado para visualização base do programa.

## Sobre o Programa C.A.A.E.:
Ao descorrer das aulas e discuções em grupo chegou-se a conclusão que nosso projeto final seria sobre um programa de Compra-Analise de Automações Economicas tanto para fins agricolas quanto para fins residenciais, mas só a base mesmo.  
O idealizado do projeto é algo proximo da Uber um programa que conecta/intermedia empresas de automação e o cliente/interessado, porém com mais proximidade da EasyEDA que se trata de um programa na qual é permitido criar um circuito eletrônico qualquer com peças do mercado, além de poder encomendar o circuito criado com a plataforma que repassa as peças requeridas a montadora e trasporta para o usuario que encomendou. Este seria o objetivo final do programa que está foram de ser possivel para o nosso nivél de conhecimento pois requer que saibamos muitas técnicas como um prorpio simulador de residencia ou então uma gerencia logica capaz de criar um link entre empresas e etc.
- Digrama da relação Pessoa x Empresa:
```mermaid
sequenceDiagram
    actor Usuário
    participant Empresa X
    Usuário->>Empresa X: Plano/Desejo
    Empresa X->>Usuário: Tempo/ValorReal
```
- Digrama da relação Pessoa x  Programa x Empresa (Idealizado):
```mermaid
sequenceDiagram
    actor U as Usuário
    participant C as CAAR
    participant E as Empresa X
    U->>C: Plano e Desejos
    C->>E: Plano do Cliente
    E->>C: Valores e Estimativas
    C->>U: Sistetiza Estimativas e Valores
```
## Programando (Back-End):
