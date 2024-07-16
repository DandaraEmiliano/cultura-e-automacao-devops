# **Implementação de Práticas DevOps em um Ambiente Empresarial Fictício**

## Introdução

Neste desafio, simulei a implementação de práticas DevOps na empresa fictícia **Tech**. Utilizei os conceitos de CALMS e as Três Maneiras do DevOps para identificar oportunidades de aprimoramento dos processos atuais e propor soluções que promovam uma cultura de colaboração, automação e aprendizado contínuo.

## 1. Diagnóstico Cultural (C de CALMS)

### Processo Escolhido

**Deploy Manual**

### Descrição do Processo Atual

1. **Entrega de Código**: Após a conclusão do desenvolvimento de um novo recurso, os desenvolvedores preparam um pacote de implantação e o encaminham à equipe de operações.
2. **Deploy**: O deploy é realizado manualmente no ambiente de produção, sem seguir um procedimento padronizado ou utilizar automação.
3. **Testes**: A equipe de operações conduz testes manuais no ambiente para verificar a funcionalidade e a integridade do código após o deploy em produção.
4. **Monitoramento**: Após o deploy, a equipe de operações monitora manualmente o sistema de logs do servidor para identificar problemas ou falhas.

### Pontos de Atrito e Oportunidades de Melhoria

- **Tempo Consumido**: O deploy manual é demorado e propenso a erros humanos.
- **Falta de Padronização**: A ausência de um procedimento padronizado resulta em inconsistências.
- **Detecção Lenta de Problemas**: Monitoramento manual não detecta problemas rapidamente.

## 2. Automação (A de CALMS)

### Proposta de Solução

**Automatização do Deploy e Testes**

### Plano de Implementação

1. **Ferramentas de Automação**:
    - **Jenkins** para CI/CD.
    - **Selenium** para testes automatizados.
2. **Configuração do Jenkins**:
    - Configurar pipelines de CI/CD que automatizam a integração e o deploy contínuos.
    - Configurar testes automatizados com Selenium para execução após cada build.
3. **Treinamento**:
    - Realizar sessões de treinamento para desenvolvedores e equipe de operações sobre o uso das novas ferramentas.
4. **Documentação**:
    - Documentar o novo processo automatizado para referência futura.

## 3. Mensuração e Compartilhamento de Conhecimento (M e S de CALMS)

### Métricas Relevantes

- **Tempo de Deploy**: Tempo médio entre a entrega do código e a implantação.
- **Taxa de Sucesso dos Deploys**: Percentual de deploys bem-sucedidos.
- **Número de Incidentes Pós-Deploy**: Incidentes registrados após cada deploy.
- **Tempo Médio de Recuperação (MTTR)**: Tempo médio para resolver incidentes.

### Plano de Disseminação de Conhecimento

1. **Workshops**:
    - Realizar workshops para apresentar as novas ferramentas e processos.
2. **Documentação**:
    - Criar e distribuir guias detalhados e documentação sobre o processo automatizado.
3. **Reuniões Regulares**:
    - Estabelecer reuniões regulares para discutir melhorias contínuas e compartilhar feedback.

## 4. Três Maneiras do DevOps

### Primeira Maneira (Acelerar o Fluxo)

- **Simplificação do Processo**:
    - Implementar pipelines de CI/CD para acelerar a entrega de valor.
    - Automatizar deploys e testes para reduzir o tempo e os erros humanos.

### Segunda Maneira (Ampliar o Feedback)

- **Mecanismos de Feedback**:
    - Utilizar ferramentas de monitoramento contínuo como **Prometheus** e **Grafana**.
    - Coletar feedback de usuários e integrá-lo ao ciclo de desenvolvimento.

### Terceira Maneira (Experimentar e Aprender)

- **Cultura de Experimentação**:
    - Promover uma cultura onde falhas são vistas como oportunidades de aprendizado.
    - Realizar testes de resiliência e incentivar experimentos controlados.

## Descrição da Empresa

### Equipe

- **Desenvolvimento**: 14 desenvolvedores com experiência em Java, C# e JavaScript. Apenas um profissional tem conhecimento em Delphi, a linguagem do sistema legado.
- **Operações**: 4 profissionais enfrentam desafios para manter a infraestrutura de TI e os sistemas em funcionamento eficiente, frequentemente lidando com problemas de escalabilidade e desempenho.

### Projetos em Andamento

1. **Sistema de Gestão de Vendas (LEGADO)**: Um aplicativo para gerenciamento de vendas que inclui controle de estoque, emissão de notas fiscais e relatórios de vendas.
2. **Plataforma de E-commerce**: Uma plataforma de e-commerce escalável para clientes do setor varejista.

### Descrição dos Processos Atuais da Empresa

1. **Entrega de Código**: Após a conclusão do desenvolvimento de um novo recurso, os desenvolvedores preparam um pacote de implantação e o encaminham à equipe de operações.
2. **Deploy**: O deploy é realizado manualmente no ambiente de produção, sem seguir um procedimento padronizado ou utilizar automação.
3. **Testes**: A equipe de operações conduz testes manuais no ambiente para verificar a funcionalidade e a integridade do código após o deploy em produção.
4. **Monitoramento**: Após o deploy, a equipe de operações monitora manualmente o sistema de logs do servidor para identificar problemas ou falhas.

### Dados de Desempenho

- **Tempo médio entre a entrega do código e o deploy**: 2 dias.
- **Taxa de sucesso dos deploys manuais**: 80%.
- **Número de incidentes após o deploy**: Média de 2 por semana.
- **Tempo médio de recuperação (MTTR) de incidentes**: 4 horas.

## Resultados Esperados

- **Redução no Tempo de Deploy**: Espera-se reduzir significativamente o tempo de deploy com a automação.
- **Aumento na Taxa de Sucesso dos Deploys**: A padronização e automação devem aumentar a taxa de sucesso.
- **Diminuição de Incidentes**: Com testes automatizados e monitoramento contínuo, espera-se uma redução no número de incidentes.
- **Maior Colaboração e Aprendizado**: A cultura de colaboração e aprendizado contínuo será fortalecida.
