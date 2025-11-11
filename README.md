# 🚀 FACILITA

**Autores:**  
Cauã Xavier Rocha e João Gabriel Biesdorf  

---
| Etapa DT | Status |
|----------|------------|
| **Empatia/Imersão** | ✅ |
| **Definição** | ✅ |
| **Ideação** | ✅ |
| **Prototipação** | ✅ |

## 🧭 1) IMERSÃO & EMPATIA

### 🎯 Stakeholders
- **Cliente:** Pessoa física e jurídica  
- **Usuário:** Prestador de serviços autônomos (foco em pessoas com baixa escolaridade e trabalhos do cotidiano)  
- **Ambiente interno:** Desenvolvedores, suporte, marketing e financeiro  
- **Ambiente externo:** Sindicatos, plataformas parceiras e imprensa  
- **Macro-ambiente:** Legislação trabalhista, economia local e empregabilidade  

### 💥 Necessidades e Dores
- Dificuldade de encontrar profissionais confiáveis rapidamente  
- Falta de padronização na apresentação de serviços e preços  
- Risco de fraudes ou má prestação do serviço  
- Limitações de orçamento e dependência de internet  
- Desconfiança inicial em contratar desconhecidos  

### 🌟 Expectativas e Soluções Propostas
- Garantir segurança e confiabilidade nas contratações  
- Sistema simples, rápido e intuitivo para busca e agendamento de serviços  
- Comunicação direta entre contratante e prestador via chat interno  
- Cadastro com verificação de identidade para ambos os lados  
- Cumprimento da legislação trabalhista e da LGPD  
- Avaliação por estrelas e comentários para cada prestador  
- Sistema multilíngue e adaptável por região  

### 🌍 Fatores Macro (STEEPL)
| Fator | Descrição |
|-------|------------|
| **Social** | Geração de renda e formalização do trabalho autônomo |
| **Tecnológico** | Acesso via desktop e mobile, interface responsiva |
| **Ecológico** | Sustentabilidade em transações digitais |
| **Político/Legal** | Conformidade com LGPD e normas fiscais |

### 💞 Empatia
- **Clientes:** Buscam rapidez, praticidade e segurança; sentem curiosidade e desconfiança.  
- **Prestadores:** Desejam renda estável, liberdade e boa reputação; sentem orgulho e cautela.  
- **Equipe:** Motivação, ansiedade e orgulho; busca ser referência e gerar impacto positivo.  

### 🗣️ Entrevistas e Insights
- Prestadores levam de 5 a 7 dias para conseguir novos clientes, dependendo de indicações.  
- Taxas justas: entre **10% e 15% por serviço**.  
- Programa de indicação aumenta engajamento.  
- Confiabilidade depende de avaliações reais, fotos e garantias de pagamento.  
- Clientes querem suporte rápido em casos de cancelamento e reembolso.  

---

## 🧩 2) DEFINIÇÃO & SÍNTESE

### ❗ Problemas Identificados
- Desconfiança inicial na contratação  
- Cancelamentos e risco de não pagamento  
- Dificuldade em encontrar prestadores disponíveis rapidamente  
- Experiências ruins no primeiro uso levam ao abandono da plataforma  
- Baixa adesão inicial por falta de reputação  

### 💡 Oportunidades
- Sistema de avaliação com comentários e fotos  
- Selo de verificação para prestadores  
- Programa de indicação e fidelidade  
- Garantia de pagamento e políticas claras de cancelamento  
- Parcerias com sindicatos e empresas locais  

### ❓ Questões de Pesquisa (“Como podemos...”)
- Como evitar cancelamentos de última hora?  
- Como estruturar suporte rápido e eficiente em casos de conflito?  
- Como incentivar adesão inicial de usuários?  
- Como proteger juridicamente ambas as partes?  
- Como equilibrar taxa e sustentabilidade financeira?  

### 🧠 Problema Central
> “Como podemos conectar contratantes e prestadores autônomos de forma rápida, segura e confiável, garantindo qualidade e confiança mútua?”

---

## 💭 3) IDEAÇÃO

### ✨ Ideias Propostas
- Sistema de avaliações e comentários com fotos  
- Verificação de identidade com selo confiável  
- Programa de indicação com recompensas  
- Garantia de pagamento e mediação de disputas  
- Sistema multilíngue e categorização regional  

### 💎 Ideias com Maior Impacto
- App **mobile-first** com geolocalização e chat interno  
- Cadastro simples e rápido com verificação  
- Pagamento seguro com proteção contra fraudes  
- Reputação baseada em histórico e feedback  

### 📊 Matriz de Priorização
| Ideia | Impacto | Viabilidade | Inovação | **Score** |
|-------|----------|-------------|-----------|------------|
| Avaliações e fotos | 5 | 5 | 3 | **13** |
| Programa de indicação | 4 | 4 | 4 | **12** |
| Garantia de pagamento | 5 | 4 | 3 | **12** |
| Selo de verificação | 4 | 4 | 3 | **11** |

---

## ⚙️ 4) PROTOTIPAÇÃO

### 🔁 Modelos e Fluxos
- **Fluxo do Cliente:** Buscar → Selecionar → Contratar → Pagar → Avaliar  
- **Fluxo do Prestador:** Cadastrar → Receber propostas → Aceitar → Executar → Receber → Avaliar  
- **Fluxo de Suporte:** Receber disputa → Analisar → Resolver → Notificar partes  

### 🧱 Protótipos Sugeridos
- Wireframes das telas principais: **Login, Busca, Perfil, Chat e Avaliação**  
- Diagramas UML: **Casos de uso, sequência de contratação e pagamento**  
- **Modelo lógico do banco de dados:**

```sql
users(id, nome, tipo, telefone, localização, avaliação)
services(id, user_id, título, descrição, preço)
jobs(id, service_id, cliente_id, status, valor, data)
reviews(id, job_id, nota, comentário)
payments(id, job_id, valor, status, método)
