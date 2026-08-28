# Corpelle Espaço Fit — Landing Page

Landing page institucional da Corpelle Espaço Fit (estética avançada e emagrecimento — Maceió/AL).

**Status: PRÉVIA.** A página está publicada com faixa de aviso no topo e `noindex`.
Não divulgar a URL antes da aprovação da cliente.

## Stack

HTML estático em arquivo único. Sem build, sem dependência, sem framework.
`index.html` contém toda a marcação, o CSS e o JS.

Única dependência externa: Google Fonts (Cormorant Garamond + Inter).

## Deploy

Hospedado na Vercel — projeto `corpelle-espaco-fit` (time WZA CONSULTORIA).

- Produção: https://corpelle-espaco-fit.vercel.app

Ao conectar este repositório em **Vercel → Settings → Git**, todo push na branch
`main` passa a gerar deploy automático, mantendo a mesma URL.

## Pendências antes de tirar do modo prévia

- [ ] **Confirmar o endereço** — Rua Maria Ramos de Lima, 153b, Antares. Dado
      extraído de um story do Instagram de ~5,5 anos atrás. Não publicar sem confirmar.
- [ ] Credenciais da Marina: formação, registro no conselho, tempo de atuação
      (seção `#sobre`, lista `.creds`)
- [ ] 3 depoimentos reais, com autorização das clientes (seção `.testi`)
- [ ] Foto da Marina ou do espaço (bloco `.about-photo`)
- [ ] Preço ou faixa de preço (FAQ "Quanto custa?")
- [ ] Horário de atendimento (seção `#local`)
- [ ] Remover a `<div class="draft">` do topo
- [ ] Remover `<meta name="robots" content="noindex, nofollow">`
- [ ] Apontar um domínio próprio

## Restrições de conteúdo (não reverter)

Estas escolhas são deliberadas — reverter cria risco jurídico e de reprovação de anúncio.

- **Sem promessa de resultado em prazo fixo.** "Método Fit com resultado em 4 semanas"
  foi reescrito como "Programa Fit — 4 semanas", descrevendo a duração do
  acompanhamento, não o resultado. Promessa de resultado em emagrecimento é
  publicidade enganosa (CDC art. 37) e é o principal motivo de reprovação de
  criativo na política de saúde e bem-estar da Meta.
- **Sem antes/depois** e sem foco em imagem corporal, pelo mesmo motivo.
- **Disclaimer no rodapé** informando que são procedimentos estéticos, que não
  substituem avaliação médica e que resultados variam. Manter.

## Rodando localmente

```bash
python3 -m http.server 8000
# http://localhost:8000
```
