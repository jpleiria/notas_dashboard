# Site de Notas Partilhadas

Este é o único ficheiro a publicar no GitHub Pages. O dashboard permanece onde está e apresenta este site num iframe.

## Preparação

1. Crie um projeto em [Firebase](https://console.firebase.google.com/) e ative **Firestore Database**.
2. Registe uma aplicação Web e copie a configuração para o objeto `firebaseConfig` em `index.html`.
3. Para um teste inicial, crie a base de dados em *test mode*. Antes de usar em produção, configure regras de acesso adequadas à equipa.
4. Crie um repositório GitHub, envie o conteúdo desta pasta para a raiz e ative **Settings → Pages → Deploy from a branch → main / root**.
5. Copie o URL publicado, por exemplo `https://utilizador.github.io/cbsl-notas/`, e substitua o endereço do `iframe` em `../index_notas_sincronizadas.html`.

O dashboard não é publicado neste repositório. Só o site de notas fica disponível fora da central.
