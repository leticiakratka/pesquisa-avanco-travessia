# Pesquisa de Avanço — Método Travessia

Formulário que mede o avanço real do aluno dentro do método: o que já ficou pronto,
onde emperrou, o que ainda falta e o resultado percebido até aqui.

- Página: `index.html` (publicada na Cloudflare Pages a partir deste repositório)
- Respostas: planilha do Diagnóstico Financeiro, aba **Pesquisa de Avanço**
- Endpoint: mesma implantação do Apps Script usada pelo formulário de trilha.
  O campo `form: 'avanco'` no POST é o que direciona pra aba certa.
- Apps Script: a cópia de referência vive em
  https://github.com/leticiakratka/obrigado-diagnostico-travessia (`Code.gs`),
  e o script publicado está vinculado à planilha.
- Quem responde "sim, pode me chamar" vira tarefa no ClickUp, na lista Letícia
  (espaço Gestão), com vencimento no mesmo dia.
- Presente de fim de formulário: https://simulador-objetivos.leticiakratka.com.br/
- GTM server-side: container GTM-N9GCCZSW via api.leticiakratka.com.br
