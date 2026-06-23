# StudyVibes — Tributação & Rotinas Financeiras

## Documentos Arquivados

| Documento | Status | Validade |
|---|---|---|
| W-8BEN (Amazon Associates) | ✅ Assinado 05-14-2026 | Até 31/12/2029 |
| Tax Interview Amazon | ✅ Concluído | — |

> **Lembrete:** O W-8BEN vence em 31/12/2029. A Amazon notifica para renovar — mas coloque um lembrete em outubro/2029.

---

## Fontes de Receita do Produto

| Canal | Moeda | Plataforma |
|---|---|---|
| Amazon Afiliados | USD | Amazon Associates (`studyvibes02-20`) |
| AdSense | USD | Google AdSense (`ca-pub-4669020251082320`) |
| Premium Mensal | USD | Stripe ($4.99/mês) |
| Premium Vitalício | USD | Stripe ($19.99 one-time) |

---

## Como Declarar no Brasil

### Regra geral
Toda receita em dólar recebida do exterior é **renda tributável no Brasil**.  
Você converte pelo câmbio **PTAX de venda** do Banco Central na data do recebimento.

PTAX: [bcb.gov.br/estabilidadefinanceira/historicotaxasjuros](https://www.bcb.gov.br) → Câmbio → PTAX

---

## Rotina Mensal (até dia 30 de cada mês)

### 1. Coletar receitas do mês anterior
- [ ] Amazon Associates → *Reports → Earnings Report* → exportar CSV do mês
- [ ] Google AdSense → *Pagamentos → Histórico de transações*
- [ ] Stripe → *Dashboard → Pagamentos* → filtrar por mês

### 2. Converter para BRL
- Pegar a PTAX de venda do **último dia útil do mês** em que o valor foi creditado
- Fórmula: `Valor USD × PTAX = Valor BRL`

### 3. Carnê-leão (se receita BRL > R$ 2.824/mês)
- Acessar: **app.gov.br → Carnê-leão Web** (ou programa Receita Federal)
- Lançar como: *Rendimentos Recebidos do Exterior — Pessoa Física*
- Pagar o DARF até o **último dia útil do mês seguinte**

> Se ficar abaixo de R$ 2.824/mês, não precisa de carnê-leão — mas guarda os registros para o IRPF anual.

---

## Rotina Anual (IRPF — entrega até 30/04)

Na declaração anual incluir:

| Ficha | O que lançar |
|---|---|
| Rendimentos Tributáveis Recebidos de PF/Exterior | Soma anual das receitas convertidas em BRL |
| Bens e Direitos | Saldo de contas estrangeiras (Stripe, se mantiver saldo) |
| Imposto Pago/Retido | DARFs pagos no carnê-leão ao longo do ano |

---

## Alíquotas IRPF 2026 (pessoa física)

| Base de cálculo mensal | Alíquota |
|---|---|
| Até R$ 2.824,00 | Isento |
| R$ 2.824,01 a R$ 3.751,05 | 7,5% |
| R$ 3.751,06 a R$ 4.664,68 | 15% |
| R$ 4.664,69 a R$ 6.101,06 | 22,5% |
| Acima de R$ 6.101,06 | 27,5% |

---

## Estratégias para Maximizar o Ganho Líquido

### Curto prazo (agora)
- **Dedução de despesas:** hosting, domínio, ferramentas pagas para o produto são dedutíveis como despesa da atividade — guarda todas as notas fiscais
- **Nenhuma dupla tributação:** o W-8BEN garante que você não paga imposto nos EUA E no Brasil ao mesmo tempo (para comissões de afiliado)

### Médio prazo (quando receita > R$ 3k/mês consistente)
- Avaliar abertura de **MEI de Serviços** ou **ME no Simples Nacional** — pode reduzir alíquota efetiva vs. IRPF pessoa física
- Consultar contador especializado em renda digital/exterior antes de migrar

### Nunca fazer
- Não declarar receita do exterior → crime de evasão fiscal
- Deixar saldo em conta estrangeira sem declarar em "Bens e Direitos"

---

## Calendário de Alertas

| Mês | Ação |
|---|---|
| Todo mês (até dia 30) | Coletar receitas + carnê-leão se necessário |
| Janeiro | Consolidar todas as receitas do ano anterior |
| Março | Preparar documentos para IRPF |
| Abril (até dia 30) | Entregar IRPF |
| Outubro/2029 | Renovar W-8BEN |

---

## Registros de Receita (template mensal)

| Mês | Amazon USD | AdSense USD | Stripe USD | Total USD | PTAX | Total BRL | Carnê-leão pago |
|---|---|---|---|---|---|---|---|
| Mai/2026 | | | | | | | |
| Jun/2026 | | | | | | | |
| Jul/2026 | | | | | | | |
