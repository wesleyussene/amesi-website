# AMESI — Website

Website institucional estático e responsivo para a Associação Moçambicana das Empresas do Sector Imobiliário.

## Publicar na Vercel

1. Extraia o ZIP e coloque o conteúdo desta pasta na raiz de um repositório GitHub.
2. Importe o repositório na Vercel.
3. Escolha **Other** como framework preset. Não é necessário build command nem output directory.
4. Publique.

O site usa HTML, CSS e JavaScript sem dependências ou processo de compilação. As fotografias de arquitectura da página inicial e da adesão são carregadas do Unsplash; as imagens locais, logótipo e paleta estão em `assets/`.

## Conteúdo a completar

- **Associados:** adicione os nomes, logótipos e dados das empresas na secção `#membros` em `index.html` quando receber a lista.
- **Adesão:** o botão da página inicial conduz à secção de contacto. Acrescente um formulário, WhatsApp ou o endereço oficial de adesão quando estiver disponível.
- **Contactos:** confirme se `info@amesi.co.mz` é o endereço a publicar e actualize-o em `index.html` se necessário.
- **Redes sociais:** podem ser acrescentadas no rodapé quando os links oficiais forem fornecidos.

## Ficheiros

- `index.html` — página inicial e secções institucionais
- `membros.html` — directório de pessoas, com fotografias, nomes e cargos dos três membros da Direcção Executiva
- `empresas-associadas.html` — directório de empresas, com três cartões placeholder para logótipo, endereço e descrição
- `styles.css` — identidade visual e layout responsivo
- `script.js` — menu móvel e ano automático no rodapé
- `assets/amesi-logo.svg` — logótipo fornecido
- `assets/color-palette.svg` — paleta fornecida
- `assets/member-benefits.jpg` — referência sobre vantagens de ser membro
- `assets/nadia-lima.png`, `assets/victor-zandamela.png` e `assets/pedro-coimbra.png` — fotografias dos membros
