# Pull Request

## 📋 Tipo de alteração

* [ ] ✨ Nova funcionalidade
* [ ] 🐛 Correção de bug
* [ ] ♻️ Refatoração
* [ ] ⚡ Melhoria de performance
* [ ] 🎨 Alteração visual / UI
* [ ] 🔒 Segurança
* [ ] 📝 Documentação
* [ ] 🧪 Testes
* [ ] 🔧 Configuração / Infraestrutura
* [ ] 📦 Dependências
* [ ] 🚨 Hotfix

---

## 🎯 Objetivo

<!--
Descreva de forma clara e objetiva:
- Qual problema está sendo resolvido?
- Por que essa alteração é necessária?
- Qual resultado esperamos após este PR?
-->

**Problema:**

> Descreva o problema que motivou esta alteração.

**Solução:**

> Explique resumidamente como este PR resolve o problema.

---

## 📝 Descrição das alterações

<!-- Liste as principais mudanças realizadas neste PR. -->

### Principais alterações

*
*
*

### Arquivos / módulos impactados

* `arquivo/modulo` — descrição da alteração
* `arquivo/modulo` — descrição da alteração

---

## 🔗 Issue / Tarefa relacionada

<!--
Vincule a issue, card ou tarefa relacionada.
Exemplo:
Closes #123
Related to #456
-->

* Issue/Tarefa: #

---

## 🧪 Testes

<!--
Descreva como a alteração foi validada.
Evite apenas escrever "testado localmente".
Informe os cenários relevantes.
-->

### Ambiente

* **Ambiente:** Desenvolvimento / Homologação / Produção
* **Sistema:**
* **Versão:**
* **Browser / Dispositivo:**

### Cenários testados

| Cenário | Resultado esperado | Resultado |
| ------- | ------------------ | --------- |
|         |                    | ✅         |
|         |                    | ✅         |
|         |                    | ✅         |

### Testes automatizados

* [ ] Testes unitários
* [ ] Testes de integração
* [ ] Testes E2E
* [ ] Testes de regressão
* [ ] Não aplicável

**Resultado:**

```text
Descreva aqui o resultado dos testes ou comandos utilizados.
```

---

## 📸 Evidências

<!--
Adicione screenshots, vídeos, GIFs, logs ou outras evidências quando necessário.
-->

### Antes

<!-- Cole a imagem aqui, se aplicável. -->

### Depois

<!-- Cole a imagem aqui, se aplicável. -->

---

## 🔄 Impacto da alteração

<!--
Avalie se a alteração pode afetar outras partes do sistema.
-->

### Áreas afetadas

* [ ] Front-end
* [ ] Back-end
* [ ] Banco de dados
* [ ] API
* [ ] Autenticação / Autorização
* [ ] Infraestrutura
* [ ] CI/CD
* [ ] Integrações externas
* [ ] Performance
* [ ] Segurança
* [ ] Nenhuma outra área identificada

### Possíveis impactos

<!-- Descreva possíveis efeitos colaterais ou áreas que precisam ser observadas. -->

>

---

## ⚠️ Riscos e pontos de atenção

<!--
Informe qualquer risco conhecido, limitação técnica ou decisão que mereça atenção do revisor.
-->

* [ ] Não foram identificados riscos relevantes
* [ ] Existe risco conhecido — descrito abaixo

**Detalhes:**

>

---

## 🗄️ Banco de dados

<!-- Marque caso o PR envolva alterações no banco. -->

* [ ] Não há alterações no banco de dados
* [ ] Nova migration
* [ ] Alteração de tabela
* [ ] Alteração de índice
* [ ] Alteração de dados
* [ ] Seed / Dados iniciais

**Detalhes / Migration:**

```text
Descreva aqui as alterações necessárias no banco.
```

---

## 🔌 API / Integrações

<!-- Marque caso o PR altere ou crie APIs/integrações. -->

* [ ] Não há alterações em APIs
* [ ] Novo endpoint
* [ ] Alteração de endpoint existente
* [ ] Alteração de payload
* [ ] Nova integração externa
* [ ] Alteração em integração existente

**Endpoints / Integrações afetados:**

```text
Exemplo:
GET /api/users
POST /api/users
```

---

## 🔐 Segurança

<!--
Avalie possíveis impactos relacionados a segurança.
-->

* [ ] Não há impacto de segurança
* [ ] Autenticação
* [ ] Autorização / Permissões
* [ ] Dados sensíveis
* [ ] Validação de entrada
* [ ] Upload de arquivos
* [ ] Tokens / Credenciais
* [ ] LGPD / Privacidade

**Observações:**

>

---

## ⚡ Performance

* [ ] Não há impacto relevante de performance
* [ ] Melhora de performance
* [ ] Pode aumentar consumo de CPU
* [ ] Pode aumentar consumo de memória
* [ ] Alteração em queries
* [ ] Alteração em chamadas de API
* [ ] Alteração em processamento

**Observações:**

>

---

## 📦 Dependências

<!--
Informe novas dependências ou atualizações importantes.
-->

* [ ] Nenhuma dependência alterada
* [ ] Nova dependência adicionada
* [ ] Dependência atualizada
* [ ] Dependência removida

**Dependências afetadas:**

```text
Nome da dependência:
Versão anterior:
Nova versão:
Motivo:
```

---

## 🚀 Deploy

<!--
Descreva qualquer procedimento necessário para realizar o deploy.
-->

* [ ] Nenhuma ação adicional necessária
* [ ] Requer migration
* [ ] Requer alteração de variável de ambiente
* [ ] Requer configuração adicional
* [ ] Requer atualização de infraestrutura
* [ ] Requer alteração manual após deploy

**Instruções:**

```text
Descreva aqui os passos necessários.
```

---

## 🔙 Rollback

<!--
Como desfazer esta alteração caso ocorra algum problema em produção?
-->

**Procedimento de rollback:**

```text
Descreva o procedimento ou informe "Reverter o PR".
```

---

## 📚 Documentação

* [ ] Documentação não foi afetada
* [ ] Documentação atualizada
* [ ] Nova documentação adicionada
* [ ] Documentação precisa ser atualizada posteriormente

**Referências:**

>

---

## 👀 Orientações para o revisor

<!--
Ajude o reviewer a saber onde concentrar a atenção.
-->

**Pontos que merecem atenção especial:**

*
*

**Decisões técnicas que gostaria de validar:**

*
*

---

## ✅ Checklist do autor

### Código

* [ ] O código segue os padrões e convenções do projeto
* [ ] O código foi revisado por mim antes de abrir o PR
* [ ] Removi código morto ou desnecessário
* [ ] Removi logs/debugs desnecessários
* [ ] Não incluí credenciais ou informações sensíveis
* [ ] Não incluí arquivos desnecessários

### Qualidade

* [ ] Tratei os principais casos de erro
* [ ] Validei entradas quando necessário
* [ ] Considerei casos extremos
* [ ] Mantive a alteração focada no objetivo do PR
* [ ] Evitei alterações não relacionadas

### Testes

* [ ] Executei os testes existentes
* [ ] Adicionei/atualizei testes quando necessário
* [ ] Validei manualmente os principais fluxos
* [ ] Verifiquei possíveis regressões

### Git

* [ ] Commits estão organizados
* [ ] Não existem arquivos temporários no PR
* [ ] Branch está atualizada com a branch de destino
* [ ] Não há conflitos
* [ ] O título do PR é claro e objetivo

### Documentação

* [ ] Atualizei a documentação quando necessário
* [ ] Adicionei comentários apenas onde realmente necessários
* [ ] Atualizei changelog/release notes quando aplicável

---

## 🤝 Checklist do revisor

* [ ] O objetivo do PR está claro
* [ ] A implementação resolve o problema proposto
* [ ] O código está adequado aos padrões do projeto
* [ ] Os casos de erro foram considerados
* [ ] Os testes são suficientes
* [ ] Não foram identificados impactos inesperados
* [ ] Não foram identificados problemas de segurança
* [ ] Não foram identificados problemas de performance
* [ ] Documentação está adequada
* [ ] PR está pronto para aprovação

---

## 💬 Observações adicionais

<!--
Use este espaço para qualquer informação adicional relevante para o PR.
-->

>

---

## 📌 Resumo para aprovação

**O que mudou?**

>

**Por que mudou?**

>

**Como foi validado?**

>

**Existe algum risco conhecido?**

>

**Pronto para merge?**

* [ ] ✅ Sim
* [ ] ⚠️ Sim, mas requer atenção em:
* [ ] ❌ Não
