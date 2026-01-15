# BoletoOS (.NET)

**BoletoOS** (*Boleto Open Source*) é uma biblioteca open source em **.NET (C#)** para geração, validação e processamento de boletos bancários brasileiros, seguindo os padrões FEBRABAN e com foco em extensibilidade para múltiplas instituições financeiras.

O objetivo do projeto é fornecer um **core confiável e padronizado** para:
- Geração de boletos
- Cálculo de código de barras e linha digitável
- Arquivos CNAB (remessa e retorno)
- Homologação e uso em produção com bancos brasileiros

---

## Roadmap

### Bancos brasileiros

Legenda dos checklists:
- **Boleto**: geração de boleto bancário
- **Remessa**: geração de arquivo CNAB
- **Retorno**: leitura de arquivo CNAB
- **Homologado**: validado em ambiente de produção

| Código | Banco | Boleto | Boleto (Prod) | Remessa | Remessa (Prod) | Retorno | Retorno (Prod) |
|------:|-------|:------:|:-------------:|:-------:|:--------------:|:-------:|:--------------:|
| 001 | Banco do Brasil | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| 003 | Banco da Amazônia | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| 004 | Banco do Nordeste | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| 021 | Banestes | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| 033 | Santander | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| 041 | Banrisul | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| 070 | BRB | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| 077 | Banco Inter | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| 085 | Cooperativa Central Ailos | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| 104 | Caixa Econômica Federal | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| 133 | Cresol | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| 136 | Unicred | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| 237 | Bradesco | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| 246 | Banco ABC Brasil | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| 260 | NuBank | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| 290 | PagBank (PagSeguro) | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| 341 | Itaú Unibanco | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| 422 | Banco Safra | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| 637 | Banco Sofisa | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| 745 | Banco Citibank | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| 748 | Sicredi | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| 756 | Sicoob | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |

> ⚠️ A lista acima segue o padrão FEBRABAN e pode ser expandida conforme demanda da comunidade.

---

## Contribuindo

Contribuições são **muito bem-vindas**. Este projeto segue práticas abertas e colaborativas.

### Como contribuir

1. Faça um **fork** do repositório
2. Crie uma branch a partir da `main`:
   ```bash
   git checkout -b feature/nome-da-feature
Implemente sua contribuição seguindo os padrões do projeto

Garanta que:

O código compile

Os testes passem

Novas funcionalidades estejam cobertas por testes

Envie um Pull Request descrevendo claramente:

O problema resolvido

O banco afetado (se aplicável)

Se há impacto em compatibilidade