# 🕵️ Trabalho 03 — Agência Horn: Investigações Lógicas (Prolog)

Agentes, temos um caso para vocês! Neste trabalho você vai resolver um mistério usando o paradigma lógico: transformar o dossiê do caso em uma base de conhecimento em Prolog e deixar o motor de inferência apontar o culpado.

## Como funciona

1. Abra o jogo pelo link: https://juniorbsn-ui.github.io/lpp-t3/agencia-horn-t3.html (ou baixe o arquivo `agencia-horn-t3.html` deste repositório e abra no navegador).
2. Digite a sua matrícula. Cada aluno recebe um caso diferente.
3. Baixe o modelo `caso_SUAMATRICULA.pl`, escreva o código no VS Code e teste no SWI-Prolog.
4. Cole ou carregue o arquivo no jogo e clique em **▶ Enviar à perícia**. São 7 missões (fatos, consultas, regras, aritmética, recursão, base dinâmica e acusação).
5. Em cada missão, responda o interrogatório: você executa consultas no SWI-Prolog (inclusive com `trace`) e digita o que o Prolog respondeu. As respostas são diferentes para cada matrícula.
6. Ao final, gere o Relatório de validação na aba **🏁 Relatório**.

**Pontuação:** 100 XP (72 XP de código + 28 XP de interrogatórios).

## O que entregar na atividade (até [DATA])

- `caso_SUAMATRICULA.pl`: o código-fonte completo, com os comentários `% Por quê:` explicando suas regras;
- `validacao_SUAMATRICULA.txt`: o relatório gerado pelo jogo;
- **prints do SWI-Prolog:**
  - (a) `consult`, `?- culpado(X).`, `?- atualizar_investigacao.` e `?- culpado(X).` de novo;
  - (b) o `trace` de `teve_chave` pedido na missão 5.

## ⚠️ Atenção

- Use a sua matrícula correta, porque o caso de cada colega é diferente.
- Suas regras também são testadas com outro conjunto de dados, então regras com nomes ou valores fixos do caso não passam.
- Gere o relatório só depois de terminar o código. Se alterar o `.pl` depois, gere o relatório de novo.
- O progresso fica salvo no navegador, mas guarde sempre o seu arquivo `.pl`.

Bom trabalho, agentes! Dúvidas, aqui nos comentários ou na aula.
