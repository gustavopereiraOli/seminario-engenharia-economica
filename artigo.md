# Avaliação Econômica de Software em Ambientes Cloud e SaaS: Um Estudo sobre Custos, Elasticidade e Previsibilidade Orçamentária

**Pontifícia Universidade Católica de Minas Gerais**  \
**Engenharia Econômica para Software**

**André Teiichi Santos Hyodo**  \
**Gustavo Pereira de Oliveira**  \
**Luis Felipe Teixeira Dias Brescia**  \
**Victor Reis Carlota**  

**Professora:** Michelle Hanne Soares de Andrade

---

## Sumário

1. Introdução e Contextualização
2. Marco Teórico
   1. Conceitos Fundamentais de Computação em Nuvem
   2. Modelos de Custos em Cloud vs. On-Premises
   3. O Papel da Elasticidade e Escalabilidade na Economia da Nuvem
   4. Impacto na Previsibilidade Orçamentária
3. Exemplos e Aplicações
   1. Caso de Estudo: Migração de Sistema On-Premises para SaaS
   2. Aplicação de Elasticidade para Otimização de Custos
4. Conclusão
5. Referências Bibliográficas
6. Apêndices e Anexos

---

## 1. Introdução e Contextualização

A computação em nuvem (cloud computing) e os modelos de Software como Serviço (SaaS) consolidaram-se como pilares da transformação digital, redefinindo a forma como as organizações desenvolvem, implantam e consomem tecnologia. A migração de infraestruturas locais (on-premises) para ambientes de nuvem deixou de ser uma tendência para se tornar uma decisão estratégica central para empresas que buscam agilidade, escalabilidade e inovação. Contudo, essa transição transcende a mera implementação técnica; ela exige uma avaliação econômica criteriosa para garantir que os benefícios prometidos se convertam em valor tangível e sustentável para o negócio.

No âmbito da disciplina de Engenharia Econômica de Software, o estudo da economia de software em nuvem é fundamental. Ele conecta conceitos de engenharia de software, como arquitetura e ciclo de vida de desenvolvimento, com princípios econômicos, como análise de custos, otimização de recursos e retorno sobre o investimento (ROI). Compreender a estrutura de custos de modelos SaaS e a dinâmica da elasticidade em nuvem é crucial para formar profissionais capazes de tomar decisões informadas que alinhem a tecnologia aos objetivos financeiros e estratégicos da organização.

O problema central abordado neste artigo é a complexidade inerente à mensuração do verdadeiro valor econômico da migração de sistemas para a nuvem. Decisões baseadas apenas em uma comparação superficial de custos podem levar a resultados inesperados e orçamentos imprevisíveis. Portanto, os objetivos deste trabalho são: analisar os distintos modelos de custos em ambientes cloud versus on-premises, avaliar o impacto econômico da elasticidade e escalabilidade como otimizadores de recursos, e discutir as implicações para a previsibilidade orçamentária das empresas.

Para alcançar tais objetivos, é imprescindível estabelecer um embasamento conceitual robusto, que permita desmistificar os componentes econômicos da nuvem e fornecer as ferramentas para uma análise aprofundada.

---

## 2. Marco Teórico

A análise estratégica da adoção de tecnologias em nuvem depende de uma compreensão sólida de seus conceitos fundamentais e modelos econômicos. Esta seção estabelece o marco teórico que serve como fundação para o restante do artigo, detalhando os modelos de serviço, as estruturas de custos e os princípios que governam a economia da computação em nuvem. Sem esse embasamento, qualquer avaliação de custos ou benefícios se torna superficial e suscetível a equívocos.

---

### 2.1 Conceitos Fundamentais de Computação em Nuvem

A computação em nuvem é entregue por meio de diferentes modelos de serviço, cada um oferecendo um nível distinto de abstração, controle e responsabilidade compartilhada entre o provedor e o cliente.

**IaaS (Infrastructure as a Service – Infraestrutura como Serviço)**  
O provedor oferece recursos computacionais fundamentais, como servidores virtuais, armazenamento e redes. O cliente mantém controle sobre o sistema operacional e as aplicações. O maior impacto econômico é a redução de CapEx, substituindo aquisição por aluguel de capacidade computacional.

**PaaS (Platform as a Service – Plataforma como Serviço)**  
Fornece um ambiente completo de desenvolvimento, teste e implantação. Economicamente, acelera o time-to-market ao eliminar custos de gestão de plataforma.

**SaaS (Software as a Service – Software como Serviço)**  
O provedor entrega uma aplicação completa via internet. Converte CapEx em OpEx, elimina manutenção e aumenta a previsibilidade de gastos.

---

### 2.2 Modelos de Custos em Cloud vs. On-Premises

A migração para a nuvem altera profundamente o modelo financeiro de TI, deslocando investimentos de CapEx para OpEx.

| Modelo On-Premises (CapEx-Intensivo) | Modelo Cloud (OpEx-Intensivo) |
|--------------------------------------|--------------------------------|
| Aquisição de Hardware (servidores, storage, rede) | Assinaturas Mensais/Anuais (IaaS, PaaS, SaaS) |
| Licenças Perpétuas | Pagamento por Uso (pay-as-you-go) |
| Infraestrutura Física (energia, refrigeração, segurança) | Custos de Transferência de Dados |
| Pessoal de Manutenção | Serviços Adicionais (monitoramento, suporte, segurança) |

Segundo Miller & Smith (2019), a mudança CapEx → OpEx melhora fluxo de caixa e reduz barreiras de entrada, mas exige governança financeira contínua. Surge então o **FinOps**, uma prática estruturada para monitorar e otimizar custos em nuvem.

---

### 2.3 O Papel da Elasticidade e Escalabilidade na Economia da Nuvem

**Escalabilidade**  
Capacidade de crescer de forma planejada. No modelo on-premises, implica novos investimentos em hardware.

**Elasticidade**  
Capacidade de provisionar e desprovisionar recursos automaticamente em função da demanda real.

O principal benefício econômico é eliminar o **superprovisionamento**, reduzindo o desperdício financeiro. Entretanto, configurações inadequadas de autoscaling podem gerar flapping e aumento inesperado de custos.

---

### 2.4 Impacto na Previsibilidade Orçamentária

A nuvem apresenta um paradoxo:

- **aumenta a previsibilidade** quando baseada em assinaturas fixas (SaaS);
- **reduz a previsibilidade** quando depende de consumo variável (IaaS/PaaS).

A previsibilidade depende de governança ativa:

- tagging de recursos;
- alertas de orçamento;
- instâncias reservadas / savings plans;
- revisão contínua de consumo.

---

## 3. Exemplos e Aplicações

### 3.1 Caso de Estudo: Migração de Sistema On-Premises para SaaS

**TCO On-Premises (3 anos):**

- Aquisição de servidores: R$ 50.000
- Licença de software: R$ 30.000
- Pessoal de TI (0,5 FTE – R$ 90.000/ano): R$ 135.000
- Energia/Refrigeração (@ R$ 10.000/ano): R$ 30.000
- **Total:** R$ 245.000

**TCO SaaS (3 anos):**

- Assinatura (100 usuários @ R$ 150/mês): R$ 18.000/mês
- **Total:** R$ 648.000

Embora o SaaS pareça mais caro, ele reduz carga operacional, aumenta produtividade e remove custos ocultos como downtime e lentidão para atualizações estratégicas.

---

### 3.2 Aplicação de Elasticidade para Otimização de Custos

Em um e-commerce com picos na Black Friday:

- Em picos: autoscaling adiciona instâncias.
- Em baixa demanda: instâncias são reduzidas automaticamente.

O custo se alinha à demanda real, mas exige governança para evitar flutuações e surpresas financeiras.

---

## 4. Conclusão

A adoção da nuvem é uma decisão estratégica, não meramente técnica. O valor econômico vai além da redução de custos diretos, abrangendo agilidade organizacional, inovação e eficiência operacional. O modelo OpEx melhora o fluxo de caixa, mas exige práticas de FinOps para controlar a variabilidade. A elasticidade elimina desperdícios e aumenta a performance, ao mesmo tempo em que introduz desafios de previsibilidade orçamentária.

A gestão contínua — não um esforço pontual — é fundamental para assegurar ROI e garantir que a nuvem permaneça um motor de competitividade e inovação.

---

## 5. Referências Bibliográficas

Armbrust, M., Fox, A., Griffith, R., Joseph, A. D., Katz, R., Konwinski, A., Lee, G., Patterson, D. A., Rabkin, A., Stoica, I., & Zaharia, M. (2010). *A view of cloud computing*. Communications of the ACM, 53(4), 50–58.

Garrison, G., Kim, S., & Wakefield, R. L. (2012). *Success factors for deploying cloud computing*. Information Systems and eBusiness Management, 13(4), 621–645.

Miller, H. G., & Smith, J. L. (2019). *The economic shift from CapEx to OpEx in enterprise software*. Information Economics and Policy, 48, 34–49.

Schmidt, R., & Williams, P. A. (2018). *An empirical study of cost variability in pay-as-you-go cloud services*. IEEE Transactions on Software Engineering, 44(11), 1059–1075.

Weinman, J. (2012). *Cloudonomics: The business value of cloud computing*. John Wiley & Sons.

Zhang, Q., Cheng, L., & Boutaba, R. (2010). *Cloud computing: State-of-the-art and research challenges*. ACM Transactions on Software Engineering and Methodology, 19(4), Article 39.

---

## 6. Apêndices e Anexos

Nenhum apêndice foi utilizado neste trabalho. Caso necessário, esta seção pode incluir tabelas adicionais, cálculos detalhados de TCO, gráficos ou dados brutos utilizados nas análises.
