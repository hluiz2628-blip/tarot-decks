# Como publicar a DLC no GitHub — passo a passo

1. Crie o repositório **público** `hluiz2628-blip/arcana-decks`. O nome precisa ser exatamente esse, porque a versão 6.2.42 já usa essa URL.
2. Se desejar, extraia este kit e adicione `README.md`, `CREDITOS_E_LICENCA.md` e `.gitignore` pela opção **Add file → Upload files**. Faça **Commit changes**.
3. No repositório `arcana-decks`, clique em **Releases → Draft a new release** (ou **Create a new release**).
4. Em **Choose a tag**, digite exatamente `clown-tarot-v1` e selecione **Create new tag**.
5. Em **Release title**, coloque `Clown Town Tarot — DLC v1.0`.
6. Faça o upload do arquivo **Clown_Tarot_DLC.zip** que acompanha a entrega em separado. É esse arquivo ZIP, sem renomear, que deve ser enviado como *asset*.
7. Pode usar uma Release normal; o repositório das DLCs está separado e não interfere nas atualizações principais. Clique em **Publish release**.
8. Confira o endereço https://github.com/hluiz2628-blip/arcana-decks/releases/download/clown-tarot-v1/Clown_Tarot_DLC.zip . Deve baixar diretamente o ZIP.
9. Instale a versão 6.2.42 do Arcana II substituindo a pasta `tarot.koplugin` inteira e, em **Explorar Cartas**, toque em **Baixar**.

## Cuidados

- Não coloque a DLC nas Releases de `tarot.koplugin` (repositório do aplicativo).
- Não envie o ZIP de instalação do plugin `Arcana_II_6.2.42...zip` para `arcana-decks`.
- Não renomeie o asset ou a tag: o endereço usado pelo plugin é fixo.
- A Release precisa ser **pública**; repositórios privados requerem autenticação que o KOReader não realiza.
- Se você criar outro nome de repositório, a URL no arquivo `tarot_clown_dlc.lua` deverá ser alterada e o plugin recompilado/redistribuído.
- As imagens e sua adaptação permanecem licenciadas em **CC BY-SA 4.0** com atribuição.
- Antes de anunciar a DLC, teste o download em um KOReader com conexão disponível.

## Atualizações futuras

- Novas versões do *aplicativo*: Releases em `hluiz2628-blip/tarot.koplugin`.
- Novas DLCs: Releases em `hluiz2628-blip/arcana-decks` com tag e asset próprios.
