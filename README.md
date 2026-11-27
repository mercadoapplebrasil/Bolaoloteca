# Bolão Loteca

Site do bolão da Loteca: https://bolaoloteca.com.br

## Atualizar

Tudo fica no `dados.json`: `concurso`, `premio`, `especial`, `fechamento` (com `-03:00`), `prazos`, `bolao` (`formato`, `cotas`, `restam`, `valor` e, se houver, `app`) e os 14 `jogos` (`casa`, `fora`, `quando`, `b` = palpite do bolão, como "1", "1X" ou "1X2").

Depois dos jogos, preencha em cada jogo `r` ("1", "X" ou "2") e `placar` ("2 x 1"): a conferência do bolão aparece sozinha. As cotas só mudam com o print oficial da Caixa.

O `index.html` é montado por script e já traz o conteúdo escrito (melhor para o Google). Se só o `dados.json` mudar, o site continua certo: o navegador relê o arquivo ao abrir.
