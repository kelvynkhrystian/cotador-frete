# 🚚 Cotador de Frete

Sistema web para simulação de cotações de frete com base em dados de origem, destino e peso. Permite o armazenamento de cada cotação, visualização por meio de painel administrativo e exportação do histórico.

---

## 🔗 Integração com API Externa

O sistema pode ser facilmente integrado com APIs reais de cálculo de frete, como a **API do MelhorEnvio** (atual), **Jadlog** ou **ViaCEP**. Atualmente, utiliza dados mockados para simulação, mas a estrutura já está preparada para:

- Enviar requisições com origem, destino e peso
- Tratar respostas com valor estimado e prazo de entrega
- Exibir os dados de forma limpa ao usuário
- Armazenar cada consulta feita

---

## 🎯 Objetivo

Simular o processo real de cotação de frete em operações logísticas, com foco em boas práticas de frontend, backend e automação de deploy.

---

## 🛠️ Tecnologias utilizadas

### Frontend:
- HTML5
- CSS3
- JavaScript (puro)

### Backend:
- PHP
- MySQL

### Extras:
- GitHub Actions (deploy automático via FTP)
- Painel Administrativo com autenticação via sessão PHP
- Exportação de cotações para CSV
- Subdomínio ativo: **cotador-frete.kelvynk.com.br**
- Hospedagem na Hostinger

---

## 🔐 Painel Administrativo

Área restrita acessível por login com usuário e senha. Possibilita:
- Listar todas as cotações feitas
- Excluir ou editar entradas
- Exportar histórico completo em CSV

---

## 📂 Estrutura de Pastas
