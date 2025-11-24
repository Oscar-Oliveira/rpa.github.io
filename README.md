# DIGIT'ALL - ARP - Formulário de Fatura

Sistema de gestão de faturas.

## 📋 Descrição

Aplicação web para submissão e gestão de faturas, com geração automática de números de encomenda sequenciais. 

## ✨ Funcionalidades

- **Formulário de Fatura**
  - Data (preenchimento automático com data atual)
  - Conta
  - Contacto
  - Valor
  - Estado (Faturado, Pago, Não Faturado)

- **Numeração Automática**
  - Geração sequencial de números de encomenda (formato: FAT-XXXXXX)
  - Persistência em localStorage (começa em FAT-001000)
  - Incremento automático a cada submissão

- **Confirmação Visual**
  - Ícone de sucesso 
  - Exibição do número da encomenda
  - Timestamp da submissão
  - Opção para submeter nova fatura

## 🚀 Como Usar

1. Abra o ficheiro `index.html` num navegador web moderno
2. Preencha todos os campos obrigatórios:
   - Data (já preenchida automaticamente)
   - Conta
   - Contacto
   - Valor
   - Estado
3. Clique em "Submeter Fatura"
4. Visualize a confirmação com o número da encomenda
5. Clique em "Submeter Outra Fatura" para novo registo

## 📝 Notas

- Os dados são armazenados apenas no localStorage do navegador
- O número da encomenda é persistente entre sessões
- Limpar o cache do navegador irá resetar o contador de encomendas
- Sem dependências externas ou conexão à internet necessária

## 📄 Licença

Projeto desenvolvido para DIGIT'ALL - ARP

---

**Versão:** 1.0  
**Última atualização:** Novembro 2025
