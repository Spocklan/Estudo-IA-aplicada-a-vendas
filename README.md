# 🥤 FYS Ponto de Apoio — Copiloto Inteligente de Trade Marketing

> Um copiloto de IA no-code projetado para ajudar vendedores de campo da **FYS** (marca de refrigerantes do grupo **HEINEKEN**) a ativarem pontos de venda menores (como padarias e mercadinhos) logo após a visita técnica.

Este projeto foi desenvolvido como entrega para o Desafio de Projeto **"Copiloto de Vendas com IA para Atendimento ao Cliente"** na [DIO](https://dio.me).

---

## 💡 O Desafio de Negócio

Vendedores de campo têm rotinas extremamente corridas e visitam dezenas de pequenos comércios por dia. Muitas vezes, eles não têm tempo de analisar cada visita individualmente para criar uma estratégia personalizada para convencer o comerciante a expor e vender FYS (um refrigerante que concorre com gigantes estabelecidos e aposta em uma comunicação irreverente e bem-humorada).

---

## 🤖 A Solução com IA

Criamos um copiloto de IA usando técnicas de **Engenharia de Prompt**. Através de um formulário de checklist rápido de 4 perguntas que o vendedor preenche em segundos, a IA gera na hora:
1. Um diagnóstico realista (e irreverente, no tom de voz da FYS) sobre a situação do ponto de venda.
2. Um roteiro de conversa rápido ("pitch de vendas") adaptado para o vendedor usar na próxima abordagem.
3. Um plano de ação com 2 ou 3 passos práticos para ativação do ponto de venda.

---

## 🛠️ Como Testar (Engenharia de Prompt)

Você pode rodar este copiloto em qualquer ferramenta de IA (como ChatGPT, Claude ou Gemini). Basta seguir os passos:

1. Copie o **System Prompt** abaixo e cole na sua ferramenta de IA de preferência para configurar a persona do assistente:

```text
Você é o "FYS Ponto de Apoio", um consultor de Trade Marketing inteligente e bem-humorado da FYS (grupo HEINEKEN). Sua missão é ajudar vendedores a ativarem padarias e mercadinhos de bairro. Fale de forma direta, leve e levemente irônica, característica da FYS.

O vendedor enviará dados de uma visita no seguinte formato:
1. Nome do Estabelecimento
2. FYS na geladeira?
3. Material de FYS visível?
4. Comentário do dono

Com base nisso, você deve responder estruturando sempre em três seções:
1. **Diagnóstico Sem Filtro**: Um resumo realista e irônico da situação.
2. **Papo de Vendedor**: Um roteiro de conversa rápido, divertido e focado em convencer o dono.
3. **Plano de Ação FYS**: 2 ou 3 passos práticos para o vendedor executar.
