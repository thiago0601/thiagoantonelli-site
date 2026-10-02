# Lucas a toda velocidade — 3 anos

Convite responsivo e estático, sem instalação ou dependências. Data: 19/12/2026. Local: restaurante Dona Ju, Águas Claras. O horário fica “A confirmar” até ser editado. A contagem usa o fuso de Brasília e, sem horário definido, conta até o início do dia 19.

## Publicar no GitHub Pages

1. Extraia o ZIP no computador.
2. No GitHub, crie um repositório público chamado `lucas-3-anos`.
3. Abra o repositório e clique em **Add file → Upload files**. Em repositório vazio, clique em **uploading an existing file**.
4. Arraste o arquivo `index.html`, a pasta `assets`, o `README.md` e `.nojekyll` para a área de upload. O `index.html` deve ficar na raiz, sem uma pasta externa `lucas-aniversario`.
5. Clique em **Commit changes**.
6. Vá em **Settings → Pages**. Em **Source**, selecione **Deploy from a branch**.
7. Selecione **main** e **/(root)** e clique em **Save**.
8. Aguarde a publicação. O endereço será `https://SEU-USUARIO.github.io/lucas-3-anos/`. Se usar `thiago0601`, será `https://thiago0601.github.io/lucas-3-anos/`.

Não é necessário configurar domínio próprio. O link github.io já usa HTTPS.

## Informar o horário

No `index.html`, procure `const FESTA`. Troque `horario: null` por `horario: '12:00'`, usando o horário real. O texto e a contagem serão atualizados automaticamente.

## Editar o conteúdo

Os textos estão no `index.html`. A foto ilustrativa está em `assets/decoracao.jpg`; pode ser substituída por outra foto mantendo esse nome. O botão do mapa abre uma busca pelo restaurante, pois o endereço exato ainda não foi informado. Para usar a localização verificada, substitua o endereço do link por um link compartilhado do Google Maps.

## Visualizar no computador

Abra `index.html` com um navegador. Mantenha a pasta `assets` ao lado dele.

## Observações

O site não coleta dados e não possui formulário de confirmação de presença. A imagem é uma proposta ilustrativa e não uma foto do restaurante. O ano 2026 foi considerado pela data desta conversa. Se mudar o ano, atualize também os textos, o dia da semana e o rodapé.
