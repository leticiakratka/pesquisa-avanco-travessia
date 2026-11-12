# Pesquisa de Avanço — Método Travessia

Formulário que mede o avanço real do aluno dentro do método: o que já ficou pronto,
onde emperrou, o que ainda falta e o resultado percebido até aqui.

- Página: `index.html` (publicada na Cloudflare Pages a partir deste repositório)
- Respostas: planilha do Diagnóstico Financeiro, aba **Pesquisa de Avanço v2**
  (a v1, de set/2026, continua na aba **Pesquisa de Avanço**; está no histórico do git)
- Endpoint: mesma implantação do Apps Script usada pelo formulário de trilha.
  O campo `form: 'avanco2'` no POST é o que direciona pra aba certa.
- Apps Script: a cópia de referência vive em
  https://github.com/leticiakratka/obrigado-diagnostico-travessia (`Code.gs`),
  e o script publicado está vinculado à planilha.
- Quem responde "sim, pode me chamar" vira tarefa no ClickUp, na lista (So) Turma Piloto Travessia
  (espaço Projetos), atribuída à Letícia e à Soraya, com vencimento no mesmo dia.
- Presente de fim de formulário: https://simulador-objetivos.leticiakratka.com.br/
- GTM server-side: container GTM-N9GCCZSW via api.leticiakratka.com.br

## v2 (nov/2026)

Mais curta (14 telas no caminho mais curto, 21 no mais longo). O bloco de resultado
depende do tempo de acesso: "sobra comparada" só a partir de 1 mês, patrimônio só a
partir de 3 meses. Saíram motivo/objetivo da compra (já vêm do diagnóstico de trilha,
cruzar pelo e-mail) e as 5 perguntas abertas repetidas, que viraram "o que você mudaria"
+ dúvida opcional. Entraram: tempo por semana, parcelas, nome da aula/planilha onde
travou, horário que funciona pra mentoria e temas de mentoria em lista (até 3).
