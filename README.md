# AO3 VHS / CRT Skins

Dois arquivos CSS para dar ao Archive of Our Own (AO3) uma aparência de fita VHS e computador antigo. As skins têm funções diferentes e devem ser cadastradas separadamente.

| Arquivo | Tipo no AO3 | O que altera |
| --- | --- | --- |
| [`cssAo3VHS.css`](cssAo3VHS.css) | Site Skin | Interface do AO3 na sua conta: navegação, listas, formulários e páginas de obras. |
| [`workSkinVHS.css`](workSkinVHS.css) | Work Skin | Texto das obras às quais você associar a skin. |

## Instalação

### Site Skin

1. Entre na sua conta do AO3 e abra **Dashboard → Skins → Create Site Skin**.
2. Dê um nome à skin, copie todo o conteúdo de `cssAo3VHS.css` para o campo **CSS** e salve.
3. Ative a skin criada na sua conta. Ela afeta a sua visualização do site, não a visualização de outras pessoas.

### Work Skin

1. Abra **Dashboard → Skins → My Work Skins → Create Work Skin**.
2. Dê um nome à skin, copie todo o conteúdo de `workSkinVHS.css` para o campo **CSS** e salve.
3. Ao criar ou editar uma obra, selecione essa Work Skin nas configurações da obra e confira a prévia antes de publicar.

A Work Skin usa seletores `#workskin` e não precisa de classes extras no HTML da obra para aplicar o estilo básico deste arquivo. Ela não substitui a Site Skin: você pode usar as duas ao mesmo tempo. Leitores podem desativar a exibição de Work Skins nas preferências do AO3.

## Ajustes e limitações

- O AO3 aceita apenas parte das propriedades e dos valores de CSS. Se o editor rejeitar uma regra, remova ou adapte a regra indicada pela mensagem de erro antes de salvar.
- A Site Skin usa imagens externas para as texturas, as imagens da marca AO3 e o avatar padrão `icon_user.png`. A logo aparece com 72 px no computador e 60 px no celular; o avatar padrão usa 56 × 56 px em todos os tamanhos de tela. Avatares personalizados permanecem intactos. Se a imagem ficar indisponível, remova as regras de substituição para voltar às imagens originais do AO3. A marca da OTW e o ícone da aba do navegador não são alterados pela skin.
- Os ajustes para celular são locais. A navegação, os menus e os formulários seguem o comportamento responsivo do próprio AO3.
- Após qualquer alteração, confira uma página de lista, uma obra e um formulário no computador e no celular. O CSS deste repositório não é enviado automaticamente à sua conta do AO3.

Consulte a [documentação de skins do AO3](https://archive.transformativeworks.org/faq/skins-and-archive-interface?language_id=pt-BR) e o [tutorial oficial de Work Skin](https://archive.transformativeworks.org/faq/tutorial-creating-a-work-skin?language_id=pt-BR) para detalhes da interface.

## By: Luiz Roberto
