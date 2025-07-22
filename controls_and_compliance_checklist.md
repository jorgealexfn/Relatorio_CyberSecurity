# Botium Toys: Relatório de avaliação de riscos

### Jorge Alex Freitas do Nascimento - Analista de Cyebrsegrança

## Ativos circulantes

Os ativos gerenciados pelo Departamento de TI incluem:
* Equipamentos no local para necessidades comerciais no escritório
* Equipamentos para funcionários: dispositivos de usuário final (desktops/laptops, smartphones), estações de trabalho remotas, fones de ouvido, cabos, teclados, mouses, estações de acoplamento, câmeras de vigilância, etc.
* Produtos de vitrine disponíveis para venda no varejo no local e online; armazenados no depósito adjacente da empresa
* Gestão de sistemas, software e serviços: contabilidade, telecomunicações, banco de dados, segurança, comércio eletrônico e gestão de estoque
* Acesso à Internet
* Rede interna
* Retenção e armazenamento de dados
* Manutenção de sistemas legados: sistemas em fim de vida útil que exigem monitoramento humano

## Avaliação de risco

### Descrição do risco
Atualmente, a gestão de ativos é inadequada. Além disso, a Botium Toys não possui todos os controles adequados e pode não estar em total conformidade com as regulamentações e padrões dos EUA e internacionais.

### Melhores práticas de controle
A primeira das cinco funções do NIST CSF é Identificar. A Botium Toys precisará dedicar recursos para identificar ativos para que possam gerenciá-los adequadamente. Além disso, precisará classificar os ativos existentes e determinar o impacto da perda de ativos existentes, incluindo sistemas, na continuidade dos negócios.

### Pontuação de risco
Em uma escala de 1 a 10, **a pontuação de risco é 8**, o que é bastante alto. Isso se deve à falta de controles e de adesão às melhores práticas de conformidade.

### Comentários adicionais
O impacto potencial da perda de um ativo é classificado como médio, pois o departamento de TI não sabe quais ativos estariam em risco. O risco de perda de ativos ou multas por parte de órgãos reguladores é alto, pois a Botium Toys não possui todos os controles necessários e não adere integralmente às melhores práticas relacionadas às normas de conformidade que mantêm dados críticos privados/seguros.

* Atualmente, todos os funcionários da Botium Toys têm acesso a dados armazenados internamente e podem acessar dados do titular do cartão e PII/SPII dos clientes.
* A criptografia não é usada atualmente para garantir a confidencialidade das informações de cartão de crédito dos clientes que são aceitas, processadas, transmitidas e armazenadas localmente no banco de dados interno da empresa.
* Controles de acesso referentes a privilégios mínimos e separação de funções não foram implementados.
* O departamento de TI garantiu disponibilidade e controles integrados para garantir a integridade dos dados.
* O departamento de TI tem um firewall que bloqueia o tráfego com base em um conjunto apropriadamente definido de regras de segurança.
* O software antivírus é instalado e monitorado regularmente pelo departamento de TI.
* O departamento de TI não instalou um sistema de detecção de intrusão (IDS).
* Não há planos de recuperação de desastres em vigor atualmente, e a empresa não possui backups de dados críticos.
* O departamento de TI estabeleceu um plano para notificar os clientes da UE em até 72 horas em caso de violação de segurança. Além disso, políticas, procedimentos e processos de privacidade foram desenvolvidos e aplicados entre os membros do departamento de TI/outros funcionários, para documentar e manter os dados adequadamente.
* Embora exista uma política de senhas, seus requisitos são nominais e não estão de acordo com os requisitos atuais de complexidade mínima de senhas (por exemplo, pelo menos oito caracteres, uma combinação de letras e pelo menos um número; caracteres especiais).
* Não há um sistema centralizado de gerenciamento de senhas que imponha os requisitos mínimos da política de senhas, o que às vezes afeta a produtividade quando funcionários/fornecedores enviam um tíquete ao departamento de TI para recuperar ou redefinir uma senha.
* Embora os sistemas legados sejam monitorados e mantidos, não há um cronograma regular para essas tarefas e os métodos de intervenção não são claros.
* A localização física da loja, que inclui os escritórios principais da Botium Toys, a fachada da loja e o depósito de produtos, conta com fechaduras suficientes, sistema de vigilância por circuito fechado de televisão (CFTV) atualizado, além de sistemas de detecção e prevenção de incêndio em funcionamento.


# Lista de Verificação de Controles e Conformidade

## Lista de Verificação de Avaliação de Controles

| Sim/Não | Controle | Explicação |
| :--- | :--- | :--- |
| **Não** | **Menor Privilégio** | Atualmente, todos os funcionários têm acesso aos dados dos clientes; os privilégios precisam ser limitados para reduzir o risco de uma violação. |
| **Não** | **Planos de recuperação de desastres** | Não há planos de recuperação de desastres em vigor. Estes precisam ser implementados para garantir a continuidade dos negócios. |
| **Não** | **Políticas de senha** | Os requisitos de senha dos funcionários são mínimos, o que pode permitir que um agente de ameaças acesse mais facilmente dados seguros/outros ativos por meio do equipamento de trabalho do funcionário/rede interna. |
| **Não** | **Separação de funções** | Precisa ser implementado para reduzir a possibilidade de fraude/acesso a dados críticos, já que o CEO da empresa atualmente executa as operações diárias e gerencia a folha de pagamento. |
| **Sim** | **Firewall** | O firewall existente bloqueia o tráfego com base em um conjunto apropriadamente definido de regras de segurança. |
| **Não** | **Sistema de detecção de intrusão (IDS)** | O departamento de TI precisa de um IDS para ajudar a identificar possíveis intrusões de agentes de ameaças. |
| **Não** | **Backups** | O departamento de TI precisa ter backups de dados críticos, no caso de uma violação, para garantir a continuidade dos negócios. |
| **Sim** | **Software antivírus** | O software antivírus é instalado e monitorado regularmente pelo departamento de TI. |
| **Não** | **Monitoramento manual, manutenção e intervenção para sistemas legados** | A lista de ativos observa o uso de sistemas legados. A avaliação de risco indica que esses sistemas são monitorados e mantidos, mas não há um cronograma regular para essa tarefa e os procedimentos/políticas relacionados à intervenção não são claros, o que pode colocar esses sistemas em risco de violação. |
| **Não** | **Criptografia** | A criptografia não é usada atualmente; implementá-la proporcionaria maior confidencialidade de informações sensíveis. |
| **Não** | **Sistema de gerenciamento de senhas** | Não há nenhum sistema de gerenciamento de senhas em vigor atualmente; implementar esse controle melhoraria a produtividade do departamento de TI/outros funcionários em caso de problemas com senhas. |
| **Sim** | **Fechaduras (escritórios, vitrines, armazéns)** | A localização física da loja, que inclui os escritórios principais da empresa, a fachada da loja e o depósito de produtos, tem fechaduras suficientes. |
| **Sim** | **Vigilância por circuito fechado de televisão (CFTV)** | O CFTV está instalado/funcionando no local físico da loja. |
| **Sim** | **Detecção/prevenção de incêndio** | O local físico da Botium Toys conta com um sistema de detecção e prevenção de incêndio em funcionamento. |

---

## Lista de Verificação de Conformidade

### Padrão de Segurança de Dados da Indústria de Cartões de Pagamento (PCI DSS)

| Sim/Não | Melhores Práticas | Explicação |
| :--- | :--- | :--- |
| **Não** | **Somente usuários autorizados têm acesso às informações do cartão de crédito dos clientes.** | Atualmente, todos os funcionários têm acesso aos dados internos da empresa. |
| **Não** | **As informações do cartão de crédito são aceitas, processadas, transmitidas e armazenadas internamente, em um ambiente seguro.** | As informações do cartão de crédito não são criptografadas e todos os funcionários atualmente têm acesso aos dados internos, incluindo as informações do cartão de crédito dos clientes. |
| **Não** | **Implemente procedimentos de criptografia de dados para proteger melhor os pontos de contato e os dados das transações com cartão de crédito.** | Atualmente, a empresa não usa criptografia para garantir melhor a confidencialidade das informações financeiras dos clientes. |
| **Não** | **Adote políticas seguras de gerenciamento de senhas.** | As políticas de senha são nominais e não há nenhum sistema de gerenciamento de senhas em vigor no momento. |

### Regulamento Geral de Proteção de Dados (RGPD)

| Sim/Não | Melhores Práticas | Explicação |
| :--- | :--- | :--- |
| **Não** | **Os dados dos clientes da U.E. são mantidos privados/seguros.** | Atualmente, a empresa não usa criptografia para garantir melhor a confidencialidade das informações financeiras dos clientes. |
| **Sim** | **Existe um plano para notificar os clientes da U.E. dentro de 72 horas se seus dados forem comprometidos/houver uma violação.** | Há um plano para notificar os clientes da U.E. dentro de 72 horas sobre uma violação de dados. |
| **Não** | **Garanta que os dados sejam classificados e inventariados adequadamente.** | Os ativos atuais foram inventariados/listados, mas não classificados. |
| **Sim** | **Aplique políticas, procedimentos e processos de privacidade para documentar e manter dados adequadamente.** | Políticas, procedimentos e processos de privacidade foram desenvolvidos e aplicados entre os membros da equipe de TI e outros funcionários, conforme necessário. |

### Controles de Sistemas e Organizações (SOC tipo 1, SOC tipo 2)

| Sim/Não | Melhores Práticas | Explicação |
| :--- | :--- | :--- |
| **Não** | **Políticas de acesso do usuário são estabelecidas.** | Controles de privilégio mínimo e separação de tarefas não estão em vigor atualmente; todos os funcionários têm acesso aos dados armazenados internamente. |
| **Não** | **Dados sensíveis (PII/SPII) são confidenciais/privados.** | A criptografia não é usada atualmente para garantir melhor a confidencialidade de PII/SPII. |
| **Sim** | **A integridade dos dados garante que os dados sejam consistentes, completos, precisos e tenham sido validados.** | A integridade dos dados está em vigor. |
| **Não** | **Os dados estão disponíveis para indivíduos autorizados a acessá-los.** | Embora os dados estejam disponíveis para todos os funcionários, a autorização precisa ser limitada apenas aos indivíduos que precisam acessá-los para realizar seu trabalho. |

### **Conclusão Técnica**

A análise dos controles da Botium Toys revela uma postura de segurança imatura, caracterizada por deficiências críticas em pilares fundamentais da segurança da informação. Do ponto de vista técnico, a arquitetura atual é insustentável e expõe a organização a riscos operacionais e de conformidade inaceitáveis.

Os principais vetores de risco identificados são:

1.  **Controle de Acesso Ineficaz:** A ausência de um modelo de segregação de acesso, como o Controle de Acesso Baseado em Função (RBAC), viola o princípio do menor privilégio. Na prática, isso cria um vetor de ataque de alto impacto, onde o comprometimento de qualquer credencial pode levar a uma violação de dados em larga escala.

2.  **Ausência de Criptografia:** Dados sensíveis, incluindo informações de cartão de crédito (escopo do PCI DSS) e dados pessoais de clientes (escopo do GDPR), são mantidos em texto claro, tanto em repouso quanto em trânsito. Essa falha de implementação não apenas viola regulamentações mandatórias, mas também elimina a principal camada de defesa para a confidencialidade dos dados em caso de acesso não autorizado.

3.  **Falta de Resiliência Operacional:** A inexistência de um Plano de Recuperação de Desastres (PRD) e de uma rotina de backups sistemática e testada significa que a empresa não possui capacidade técnica para se recuperar de um incidente grave, seja ele um ataque de ransomware, uma falha de hardware ou um erro humano, resultando em alto risco de perda de dados permanente e interrupção prolongada dos negócios.

Estas falhas técnicas resultam diretamente na não conformidade com os frameworks PCI DSS e GDPR, expondo a empresa a penalidades severas e danos à reputação.

Portanto, minha recomendação técnica formal e urgente é a execução prioritária das seguintes ações corretivas:

* **Implementação imediata de um modelo de controle de acesso (RBAC)** para segmentar e restringir o acesso aos dados com base na necessidade funcional.
* **Implantação de criptografia de ponta a ponta** para todos os dados sensíveis em repouso e em trânsito, utilizando algoritmos e protocolos padrão de mercado (e.g., AES-256 e TLS 1.2+).
* **Desenvolvimento e teste de um Plano de Recuperação de Desastres**, suportado por uma política de backup automatizada que garanta a integridade e a disponibilidade dos dados críticos.

A execução destas medidas não deve ser tratada como uma melhoria opcional, mas como um requisito fundamental e imediato para mitigar riscos críticos e garantir a sustentabilidade técnica e operacional da Botium Toys.