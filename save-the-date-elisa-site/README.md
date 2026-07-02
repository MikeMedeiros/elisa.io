# Save the Date · Elisa 1 aninho

Site estático pronto para o GitHub Pages.

## Estrutura
```
index.html
assets/
  ganso-andando.mp4   → vídeo do ganso em loop no topo
  ganso.png           → ilustração usada na tela de confirmação
  musica.mp3           → você precisa adicionar este arquivo (veja abaixo)
```

## Sobre a música de fundo
Não incluí o arquivo de áudio de "Married Life" (Michael Giacchino, trilha de *Up – Altas
Aventuras*) porque é uma música protegida por direitos autorais e eu não posso
reproduzir, baixar ou distribuir gravações comerciais.

Para usar essa música (ou qualquer outra) no site:
1. Consiga o arquivo em uma fonte que você tenha o direito de usar (uma cópia que você
   já possui, ou uma licença adequada para uso do jeito que pretende publicar o site).
2. Renomeie o arquivo para `musica.mp3`.
3. Coloque-o dentro da pasta `assets/`.

O player (botão 🔈 no canto superior direito) já está pronto: ele tenta tocar a música
automaticamente ao abrir a página e permite pausar/retomar a qualquer momento. Alguns
navegadores bloqueiam a reprodução automática com som — se isso acontecer, a música só
começa quando a pessoa clicar no botão, o que é normal.

Se preferir não lidar com direitos autorais, qualquer música instrumental romântica e
livre de royalties (bancos como Pixabay Music, YouTube Audio Library, etc.) funciona do
mesmo jeito, bastando salvar como `assets/musica.mp3`.

## Publicando no GitHub Pages
1. Crie um repositório novo no GitHub (ex: `save-the-date-elisa`).
2. Faça upload de `index.html` e da pasta `assets/` (com o `musica.mp3` já dentro) para
   a raiz do repositório.
3. Vá em **Settings → Pages**.
4. Em "Branch", selecione `main` (ou a branch que você usou) e a pasta `/root`.
5. Salve. Em alguns minutos o GitHub mostra o link público do site
   (algo como `https://seuusuario.github.io/save-the-date-elisa/`).

## Formulário de presença
O formulário já está conectado ao Google Forms/planilha configurado anteriormente —
não precisa mexer em nada.
