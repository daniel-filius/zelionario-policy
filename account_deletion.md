---
title: Exclusão de Conta — Zé-lionário
---

# Exclusão de Conta — Zé-lionário

**App:** Zé-lionário (`br.com.zelionario.game`)
**Desenvolvedor:** Daniel Filho
**Última atualização:** 5 de maio de 2026

Este documento descreve como solicitar a exclusão da sua conta e dados associados ao aplicativo **Zé-lionário**.

---

## Como solicitar a exclusão da sua conta

Envie um e-mail para **danielfilho8@gmail.com** com:

- **Assunto:** `[Zé-lionário] Solicitação de exclusão de conta`
- **Corpo:** o e-mail vinculado à sua conta Google no app (se você conectou). Se você jogou apenas no modo anônimo, mencione isso e descreva a data aproximada do último acesso.

Confirmaremos o recebimento em até **48 horas úteis** e processaremos a exclusão em até **15 dias corridos**, conforme exigido pela Lei Geral de Proteção de Dados (LGPD).

---

## Quais dados são excluídos

Quando você solicita exclusão, removemos **permanentemente**:

- Seu **identificador único anônimo (UID)** do Firebase Authentication.
- Seu **save de progresso** armazenado no Firestore (`users/{uid}`).
- A **vinculação com sua conta Google**, se houver.
- **Eventos de Analytics** vinculados ao seu UID (no Firebase, esses dados ficam disponíveis para nossa visualização agregada por até 14 meses, mas perdem qualquer vínculo com o seu UID após a exclusão).

---

## Quais dados são mantidos

Por obrigação legal ou operacional, **mantemos** após a exclusão:

- **Logs de transações de compra** (IAPs feitos via Google Play Billing) — pelo prazo legal de 5 anos para fins fiscais. Esses logs contêm apenas o ID da transação e o produto comprado, sem dados pessoais.
- **Dados de Analytics agregados e anonimizados** que não permitem identificação individual (ex: "X jogadores chegaram ao Tier 12 em maio/2026").

---

## Dados locais no seu dispositivo

Os dados armazenados **localmente no seu celular** (banco de dados Hive, configurações de volume, modo noturno) são apagados automaticamente quando você **desinstala o app**. Não precisamos de uma solicitação para isso — basta desinstalar.

---

## Período adicional de armazenamento

Após a confirmação da exclusão:

- Os dados são removidos imediatamente da nossa base ativa.
- Ficam por até **30 dias adicionais em backups internos** automáticos do Google Firebase, depois dos quais são apagados de forma irreversível.

---

## Contato

Dúvidas sobre o processo:

**Daniel Filho**
E-mail: **danielfilho8@gmail.com**

Você também tem direito de contatar a **Autoridade Nacional de Proteção de Dados (ANPD)** caso entenda que seus direitos não foram respeitados:
<https://www.gov.br/anpd/pt-br>
