# Métricas em teste sautomatizados

Este texto foi produzido pelo ChatGPT com co-autoria de Walmyr Lima e Silva Filho.

___

## Métricas de Automação de Testes de Software: Entendendo o que medir e por quê

A automação de testes de software é uma prática essencial para garantir a qualidade de software e reduzir o tempo e o custo necessários para testar um sistema. No entanto, uma vez que a automação de testes é apenas um meio para um fim, é fundamental medir seu impacto em relação aos objetivos do projeto. Isso significa que é importante saber quais métricas de automação de testes de software são relevantes para avaliar o desempenho dos testes automatizados. Neste artigo, discutiremos algumas das métricas mais comuns que as equipes de teste usam para medir a eficácia de seus testes automatizados.

### Cobertura de Testes e de Código

A cobertura de testes mede o quanto do código fonte é coberto pelos testes. Isso é importante porque testes mais abrangentes tendem a encontrar mais bugs e ajudam a garantir que o software esteja funcionando corretamente. A cobertura de código, por outro lado, mede a porcentagem de linhas de código que são executadas pelo conjunto de testes automatizados. Isso é importante porque a falta de cobertura de código pode significar que partes críticas do software não estão sendo testadas.

### Duração da Execução da(s) Suite(s) de Teste

O tempo necessário para executar a suíte de testes é uma métrica importante porque o tempo é um recurso valioso. Testes que demoram muito tempo para serem executados podem desacelerar o processo de desenvolvimento e, por sua vez, aumentar os custos de desenvolvimento. A duração dos testes é influenciada pelo tamanho da suíte de testes, pela qualidade do código, pelo hardware em que os testes são executados e pela complexidade dos testes.

### Percentual de Testes Flaky

Os testes flaky são aqueles que às vezes passam e às vezes falham, sem que haja alteração no código sendo testado. Os testes flaky podem ser causados por uma variedade de fatores, incluindo concorrência de threads, timing, ou interação com outros sistemas. O percentual de testes flaky é uma métrica importante porque esses testes podem ser imprevisíveis e difíceis de depurar, o que pode levar a perda de confiança nos testes automatizados.

### Percentual de Bugs Encontrados Depois de um Certo Período de Tempo (ex.: uma nova release)

O percentual de bugs encontrados depois de um certo período de tempo é uma métrica importante porque ela ajuda a avaliar a eficácia dos testes automatizados ao longo do tempo. Se o percentual de bugs encontrados depois de uma nova release for alto, isso pode indicar que o processo de desenvolvimento não é tão bom quanto poderia ser.

### Percentual de Regressões Depois de um Certo Período de Tempo (ex.: uma nova release)

A regressão ocorre quando uma nova versão do software é lançada e introduz um bug em uma funcionalidade anteriormente funcionando corretamente. O percentual de regressões depois de um certo período de tempo é uma métrica importante porque ajuda a avaliar a capacidade dos testes automatizados de identificar problemas em versões subsequentes do software. Se o percentual de regressões for alto, isso pode indicar que o processo de desenvolvimento não está atendendo às necessidades de qualidade do software.

### Quais Testes São Mais Lentos e Podem Ser Otimizados?

Os testes mais lentos podem ser um gargalo no processo de teste automatizado. A identificação desses testes é uma métrica importante porque permite que a equipe de teste priorize os testes que devem ser otimizados para melhorar a eficiência geral do processo de teste. É importante lembrar que a otimização de testes não deve ser feita apenas com base no tempo de execução, mas também na importância dos testes em relação aos objetivos de teste.

### Quais São as Falhas e Erros Mais Comuns?

A identificação das falhas e erros mais comuns em um conjunto de testes é uma métrica importante para melhorar a qualidade do software. Essas falhas e erros podem ser usados para direcionar a atenção da equipe de teste para áreas críticas do software que precisam de mais testes ou para identificar a necessidade de refatoração de código.

### Qual o Tamanho da Suíte de Testes e Quais Testes Sempre Passaram?

A suíte de testes é composta por um conjunto de testes automatizados que garantem que o software esteja funcionando corretamente. O tamanho da suíte de testes é uma métrica importante porque afeta o tempo necessário para executar todos os testes. Identificar os testes que sempre passaram é outra métrica importante, pois esses testes podem ser considerados para serem retirados da suíte de testes para reduzir a duração da execução, desde que não sejam críticos para garantir a qualidade do software.

### Atributos Não-Funcionais de Qualidade do Software

Além das métricas de automação de testes de software para garantir a qualidade funcional do software, também existem métricas para avaliar os atributos de qualidade não funcionais do software. Essas métricas podem incluir:

- **Desempenho:** Mede a capacidade do software de processar uma grande quantidade de dados em um curto período de tempo. As métricas de desempenho podem incluir tempo de resposta, tempo de carregamento, tempo de processamento e outras.

- **Carga:** Mede a capacidade do software de lidar com um grande número de usuários simultâneos. As métricas de carga podem incluir o número máximo de usuários que o software pode lidar, o tempo de resposta sob carga e outros.

- **Estresse:** Mede a capacidade do software de lidar com situações extremas ou inesperadas, como falhas no hardware, interrupções de rede, etc. As métricas de estresse podem incluir o tempo de recuperação do software após uma falha, a capacidade de restaurar o estado anterior do software e outras.

- **Segurança:** Mede a capacidade do software de proteger os dados do usuário e prevenir ataques maliciosos. As métricas de segurança podem incluir a taxa de vulnerabilidades encontradas, o tempo necessário para corrigir as vulnerabilidades e outras.

- **Acessibilidade:** Mede a capacidade do software de ser acessível para usuários com deficiências físicas ou sensoriais. As métricas de acessibilidade podem incluir a conformidade com as diretrizes de acessibilidade, o tempo necessário para corrigir as não conformidades e outras.

Ao medir essas métricas, a equipe de teste pode avaliar a qualidade do software em relação aos requisitos de qualidade não funcionais e usá-las para identificar áreas críticas do software que precisam de mais atenção e melhorias.

### Conclusão

As métricas de automação de testes de software podem ajudar a equipe de teste a medir o desempenho dos testes automatizados e melhorar a qualidade do software. É importante lembrar que a escolha das métricas deve ser orientada pelos objetivos do projeto e que essas métricas devem ser interpretadas com cuidado, levando em consideração a complexidade do software e do processo de desenvolvimento. Ao escolher as métricas apropriadas e interpretá-las de forma adequada, a equipe de teste pode melhorar a eficácia dos testes automatizados e garantir que o software atenda aos requisitos de qualidade esperados.
