---
name: new product
about: Desenvolvimento de um novo produto
title: '[Produto] - descrição'
labels: New Feature
assignees: ''
---

## 📋 Dados Principais

### Meio de Requisição
- [ ] RH400
- [ ] API

### Banco
- [ ] PAN
- [ ] Safra
- [ ] C6
- [ ] BMG
- [ ] Mercantil do Brasil
- [ ] iCred
- [ ] Outro: ___________

### Produto
- [ ] FGTS
- [ ] Novo (Margem)
- [ ] Saque Complementar
- [ ] Cartão
- [ ] Refinanciamento
- [ ] Outro: ___________

---

## 📝 Resumo Executivo

Uma descrição clara e concisa do novo produto que está sendo implementado.

---

## 🎯 Objetivo e Escopo

Descreva os objetivos específicos desta implementação e o escopo de trabalho esperado.

---

## 📊 Dependências Externas

- Documentação do banco: [link]
- Requisitos específicos: [descrever]
- Pré-requisitos técnicos: [descrever]
- Outras dependências: [descrever]

---

## 🔗 JSON Proposta

Objeto de inserção de proposta a ser enviado ao banco (requisitos mínimos):

\`\`\`json
{
  "client": {
    "cpf": "99999999999",
    "name": "João da Silva",
    "address": {
      "zipcode": "195564",
      "state": "SP"
    }
  }
}
\`\`\`

---

## 🔗 JSON Simulação [Opcional]

Objeto de simulação retornada pelo banco:

\`\`\`json
{
  "simulation": {
    "amount": 10000,
    "rate": 0.05,
    "installments": 24
  }
}
\`\`\`

---

## 🔗 JSON Integração

Objeto de integração da proposta com auto-contratação, organizando os steps e campos:

\`\`\`json
{
  "informacaoInicial": {
    "cpf": "",
    "nome": ""
  },
  "endereco": {
    "cep": "",
    "estado": ""
  }
}
\`\`\`

---

## 🎨 Design e Referências

- **Figma**: [link-do-design]
- **Screenshots de referência**: [adicionar imagens]

---

## ✅ Critérios de Aceição

- [ ] API integrada com o banco
- [ ] Fluxo de simulação funcionando
- [ ] Fluxo de contratação funcionando
- [ ] Testes unitários implementados
- [ ] Testes de integração implementados
- [ ] Documentação atualizada
- [ ] Homologado com o banco

---

## 📅 Estimativa e Prazo

**Sprint estimada**: 

**Prazo desejado**: 

---

## 📌 Observações Adicionais

[Adicionar informações relevantes]