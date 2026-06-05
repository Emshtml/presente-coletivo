# presente-coletivo
Página web simples e responsiva para arrecadação de fundos (vaquinha) entre amigos, com sistema de cópia rápida da chave Pix.
# 🚀 Vaquinha dos Amigos (Arrecadação via Pix)

Uma página web simples, elegante e totalmente responsiva desenvolvida para organizar arrecadações financeiras coletivas entre amigos (como presentes de aniversário, festas ou eventos). 

A página conta com uma barra de progresso visual para a meta e um botão funcional de "Clique e Copie" para facilitar o envio do Pix.

## ✨ Funcionalidades

*   📱 **Design Responsivo:** Funciona perfeitamente em computadores, tablets e celulares.
*   📋 **Pix Copia e Cola:** Botão integrado que copia a chave Pix automaticamente para a área de transferência do usuário.
*   📊 **Barra de Progresso:** Feedback visual sobre a meta de arrecadação.
*   🎨 **Interface Moderna:** Estilização limpa utilizando as cores oficiais do Pix.

## 🛠️ Como usar e personalizar

Para usar este projeto com os dados da sua vaquinha, basta clonar o repositório ou baixar o arquivo `index.html` e alterar os seguintes pontos no código:

1. **Título e Descrição (Linhas 121 a 124):** Altere o nome do evento/presente e o texto explicativo.
2. **Meta Financeira (Linhas 127 a 132):** Atualize o valor já arrecadado, a meta total e a porcentagem da barra de progresso (na propriedade `width` na linha 49 do CSS).
3. **Chave Pix (Linhas 137 e 149):** Substitua a chave aleatória de exemplo pela sua chave Pix real.

```javascript
// Linha 149 - Altere para a sua chave Pix ou código Copia e Cola:
const codigoPix = "SUA-CHAVE-PIX-AQUI";
