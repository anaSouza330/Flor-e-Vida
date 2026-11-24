# Planejamento de Wireframes — Floricultura Flor e Vida

## 1. Objetivo

Este documento apresenta o planejamento de wireframes de baixa fidelidade para o site institucional da **Floricultura Flor e Vida**. O foco é definir estrutura, hierarquia da informação, posicionamento dos elementos e comportamento responsivo, sem especificar cores ou tipografias.

> **Nota sobre a arquitetura:** o campo `[ARQUITETURA]` enviado na solicitação estava vazio. Para elaborar este planejamento, foi utilizada a estrutura de páginas definida no levantamento anterior: Início, Buquês, Plantas, Presentes, Sobre, Contato e Página 404. A estrutura deverá ser ajustada caso a arquitetura definitiva seja diferente.

## 2. Diretrizes gerais

- Manter cabeçalho e rodapé consistentes em todas as páginas.
- Priorizar navegação simples e rótulos objetivos.
- Utilizar blocos, retângulos e marcadores de imagem como representação de baixa fidelidade.
- Organizar os produtos em cards padronizados.
- Dar destaque às ações principais sem competir com o conteúdo.
- Projetar primeiro a experiência desktop e prever adaptação para telas menores.
- Usar textos e imagens reais somente quando forem fornecidos e validados pela empresa.

## 3. Mapa de páginas

| Página | Objetivo |
|---|---|
| Início | Apresentar a floricultura e direcionar para as categorias |
| Buquês | Exibir os buquês e suas categorias |
| Plantas | Apresentar as plantas disponíveis |
| Presentes | Mostrar opções para presentear |
| Sobre | Apresentar a história e os diferenciais da empresa |
| Contato | Facilitar comunicação e localização |
| Página 404 | Orientar o visitante quando uma página não for encontrada |

## 4. Componentes compartilhados

### 4.1 Cabeçalho

**Desktop**
- Logotipo no lado esquerdo.
- Menu de navegação no lado direito ou centralizado.
- Links: Início, Buquês, Plantas, Presentes, Sobre e Contato.
- Ícone de menu ou busca somente se houver funcionalidade prevista.
- O cabeçalho deve permanecer visualmente consistente entre as páginas.

**Mobile**
- Logotipo alinhado à esquerda.
- Botão de menu tipo hambúrguer à direita.
- Ao tocar no botão, abrir menu vertical com os links de navegação.
- Garantir área de toque confortável e identificação clara do menu aberto/fechado.

### 4.2 Rodapé

- Logotipo e breve identificação da floricultura.
- Links rápidos para as páginas principais.
- Informações de contato oficiais.
- Links para redes sociais oficiais.
- Endereço e horário de funcionamento, somente após confirmação pela empresa.
- Em dispositivos móveis, organizar os blocos verticalmente.

### 4.3 Cards de produtos

Cada card poderá conter:
- Área de imagem do produto.
- Nome do produto.
- Preço, caso a empresa decida divulgá-lo e mantenha a informação atualizada.
- Botão ou link “Ver detalhes” ou “Consultar”.
- Não apresentar disponibilidade ou preço sem confirmação da floricultura.

---

# 5. Wireframes por página

## 5.1 Página inicial

**Objetivo:** apresentar a empresa, destacar categorias e encaminhar o visitante para os produtos ou contato.

### Estrutura do cabeçalho
- Logotipo à esquerda.
- Menu principal com links para Início, Buquês, Plantas, Presentes, Sobre e Contato.
- No mobile, menu recolhido em botão hambúrguer.

### Organização do conteúdo e seções

1. **Banner principal (hero)**
   - Título institucional e slogan.
   - Texto curto de apresentação.
   - Imagem floral de destaque.
   - Botão principal “Conheça nossas flores” ou equivalente.

2. **Categorias**
   - Cards para Buquês, Flores, Plantas e Presentes, conforme o catálogo real.
   - Cada card possui imagem ou ícone, nome e link para a respectiva página.

3. **Produtos em destaque**
   - Grade de cards com imagem, nome e chamada para detalhes/consulta.
   - Quantidade de cards definida conforme o conteúdo disponível.

4. **Apresentação da empresa**
   - Imagem institucional.
   - Texto breve sobre a Floricultura Flor e Vida.
   - Link “Saiba mais” direcionando à página Sobre.

5. **Chamada para contato**
   - Texto curto convidando o visitante a entrar em contato.
   - Botão para a página Contato ou canal oficial confirmado.

### Posicionamento dos botões
- Botão principal no banner, próximo ao texto.
- Links de categoria dentro de cada card.
- Botões “Ver detalhes” nos cards de produtos.
- Botão “Saiba mais” na apresentação institucional.
- Chamada de contato antes do rodapé, se necessária.

### Organização das imagens
- Uma imagem principal ampla no banner.
- Imagens menores e consistentes nas categorias.
- Fotos dos produtos nos cards.
- Imagem institucional na seção Sobre.

### Rodapé
Utilizar o rodapé compartilhado: logotipo, links rápidos, contatos oficiais, redes sociais e endereço/horários confirmados.

### Comportamento mobile
- Banner com texto e imagem empilhados.
- Categorias em duas colunas ou lista horizontal deslizável.
- Produtos em uma ou duas colunas, conforme a largura da tela.
- Seção Sobre empilhada, com imagem antes ou depois do texto.
- Botões ocupando largura adequada para toque.

### Esboço textual
```text
┌────────────────────────────────────────────┐
│ LOGO                 MENU ☰                │
├────────────────────────────────────────────┤
│ TÍTULO + TEXTO       IMAGEM PRINCIPAL      │
│ [AÇÃO PRINCIPAL]                           │
├────────────────────────────────────────────┤
│             NOSSAS CATEGORIAS              │
│ [Buquês] [Flores] [Plantas] [Presentes]    │
├────────────────────────────────────────────┤
│             PRODUTOS EM DESTAQUE           │
│ [Card]       [Card]       [Card]           │
├────────────────────────────────────────────┤
│ IMAGEM SOBRE       TEXTO + [SAIBA MAIS]    │
├────────────────────────────────────────────┤
│ CHAMADA PARA CONTATO                       │
├────────────────────────────────────────────┤
│ RODAPÉ: LOGO | LINKS | CONTATO | REDES     │
└────────────────────────────────────────────┘
```

## 5.2 Página de Buquês

**Objetivo:** apresentar os buquês comercializados e facilitar a consulta dos produtos.

### Estrutura do cabeçalho
- Cabeçalho compartilhado, com destaque visual para o link “Buquês” como página atual.

### Organização do conteúdo e seções

1. **Banner/título da categoria**
   - Título “Buquês”.
   - Texto introdutório breve.
   - Imagem temática de apoio.

2. **Área de catálogo**
   - Título ou indicação “Todos os buquês”.
   - Filtros ou categorias, caso existam no catálogo real, como românticos, aniversário ou ocasiões especiais.
   - Grade de produtos.

3. **Paginação ou carregamento**
   - Controles para navegar por mais produtos, caso o catálogo tenha várias páginas.

4. **Chamada para contato**
   - Link para consultar opções e disponibilidade pelos canais oficiais.

### Posicionamento dos botões
- Filtros na lateral esquerda em desktop ou acima da grade.
- “Ver detalhes” em cada card.
- Paginação abaixo da grade.
- Ação de contato após o catálogo.

### Organização das imagens
- Imagem de destaque no banner.
- Uma fotografia por card, com proporção consistente.
- Evitar imagens de tamanhos muito diferentes na mesma grade.

### Rodapé
Rodapé compartilhado.

### Comportamento mobile
- Banner empilhado.
- Filtros em seletor ou painel expansível.
- Cards em duas colunas ou uma coluna em telas estreitas.
- Paginação com controles fáceis de tocar.
- Imagens dimensionadas para não causar rolagem horizontal.

### Esboço textual
```text
┌────────────────────────────────────────────┐
│ LOGO                         MENU ☰        │
├────────────────────────────────────────────┤
│ TÍTULO: BUQUÊS       IMAGEM DE DESTAQUE    │
│ Texto introdutório                         │
├────────────────────────────────────────────┤
│ FILTROS       │ [CARD] [CARD] [CARD]       │
│ - Todos       │ [CARD] [CARD] [CARD]       │
│ - Categoria   │                            │
├────────────────────────────────────────────┤
│              [PAGINAÇÃO]                   │
│        CHAMADA PARA CONSULTA                │
├────────────────────────────────────────────┤
│                  RODAPÉ                    │
└────────────────────────────────────────────┘
```

## 5.3 Página de Plantas

**Objetivo:** apresentar as plantas disponíveis e permitir que o visitante explore o catálogo.

### Estrutura do cabeçalho
- Cabeçalho compartilhado, com “Plantas” identificado como página atual.

### Organização do conteúdo e seções

1. **Banner/título**
   - Título “Plantas”.
   - Texto introdutório.
   - Imagem de plantas.

2. **Categorias de plantas**
   - Categorias conforme o catálogo confirmado, por exemplo: ornamentais, suculentas, folhagens ou plantas para vasos.
   - Não exibir categorias sem produtos correspondentes.

3. **Catálogo**
   - Cards com imagem, nome e ação para detalhes ou consulta.
   - Filtros opcionais se houver variedade suficiente.

4. **Chamada para contato**
   - Orientação para consultar disponibilidade e cuidados, se a empresa oferecer esse atendimento.

### Posicionamento dos botões
- Filtros antes ou ao lado do catálogo.
- “Ver detalhes” em cada card.
- Botão de contato ao final da listagem.

### Organização das imagens
- Imagem de destaque no banner.
- Fotos individuais das plantas.
- Manter enquadramento e proporções semelhantes nos cards.

### Rodapé
Rodapé compartilhado.

### Comportamento mobile
- Categorias em grade adaptável.
- Filtros em painel expansível.
- Produtos em duas colunas ou lista vertical.
- Texto e imagem do banner empilhados.

### Esboço textual
```text
┌────────────────────────────────────────────┐
│ LOGO                         MENU ☰        │
├────────────────────────────────────────────┤
│ TÍTULO: PLANTAS      IMAGEM DE DESTAQUE    │
├────────────────────────────────────────────┤
│ CATEGORIAS                                 │
│ [Categoria] [Categoria] [Categoria]       │
├────────────────────────────────────────────┤
│ FILTROS       │ [CARD] [CARD] [CARD]       │
│               │ [CARD] [CARD] [CARD]       │
├────────────────────────────────────────────┤
│       [CONSULTAR DISPONIBILIDADE]          │
├────────────────────────────────────────────┤
│                  RODAPÉ                    │
└────────────────────────────────────────────┘
```

## 5.4 Página de Presentes

**Objetivo:** apresentar opções de presentes e facilitar a consulta pelo visitante.

### Estrutura do cabeçalho
- Cabeçalho compartilhado, com “Presentes” identificado como página atual.

### Organização do conteúdo e seções

1. **Banner/título**
   - Título “Presentes”.
   - Texto breve de apresentação.
   - Imagem ilustrativa de uma composição para presente.

2. **Categorias**
   - Opções existentes no catálogo, como buquês, arranjos, cestas ou kits especiais.
   - As categorias devem refletir os produtos realmente oferecidos.

3. **Produtos**
   - Grade de cards com imagens, nomes e links para detalhes/consulta.

4. **Chamada para contato**
   - Convite para consultar opções, personalizações ou disponibilidade, apenas se esses serviços forem oferecidos.

### Posicionamento dos botões
- Links nas categorias.
- “Ver detalhes” em cada produto.
- Botão de contato após os produtos.

### Organização das imagens
- Imagem principal no banner.
- Fotos dos produtos em cards.
- Imagens devem representar fielmente os itens oferecidos.

### Rodapé
Rodapé compartilhado.

### Comportamento mobile
- Banner empilhado.
- Categorias em duas colunas.
- Produtos em grade adaptável.
- Botões com largura confortável para toque.

### Esboço textual
```text
┌────────────────────────────────────────────┐
│ LOGO                         MENU ☰        │
├────────────────────────────────────────────┤
│ TÍTULO: PRESENTES   IMAGEM DE DESTAQUE    │
├────────────────────────────────────────────┤
│ CATEGORIAS                                 │
│ [Buquês] [Arranjos] [Cestas] [Kits]        │
├────────────────────────────────────────────┤
│             OPÇÕES DE PRESENTES            │
│ [CARD]       [CARD]       [CARD]           │
│ [CARD]       [CARD]       [CARD]           │
├────────────────────────────────────────────┤
│             [ENTRAR EM CONTATO]            │
├────────────────────────────────────────────┤
│                  RODAPÉ                    │
└────────────────────────────────────────────┘
```

## 5.5 Página Sobre

**Objetivo:** apresentar a floricultura, sua história e informações institucionais.

### Estrutura do cabeçalho
- Cabeçalho compartilhado, com “Sobre” identificado como página atual.

### Organização do conteúdo e seções

1. **Título e introdução**
   - Título “Sobre a Flor e Vida”.
   - Frase de apresentação.

2. **História da empresa**
   - Texto institucional.
   - Fotografia da loja, equipe ou atividade, caso fornecida e autorizada.

3. **Valores ou diferenciais**
   - Blocos curtos com ícones e textos.
   - Utilizar somente características confirmadas pela empresa.

4. **Missão ou compromisso**
   - Texto institucional, se a empresa possuir uma declaração aprovada.

5. **Chamada para contato**
   - Link para a página Contato.

### Posicionamento dos botões
- Botão “Entre em contato” ao final da apresentação.
- Links para outras páginas podem aparecer em áreas contextuais, sem competir com o texto.

### Organização das imagens
- Uma imagem institucional principal ao lado do texto em desktop.
- Imagens complementares em galeria somente se houver material suficiente.
- No mobile, imagem e texto em sequência vertical.

### Rodapé
Rodapé compartilhado.

### Comportamento mobile
- Conteúdo em uma única coluna.
- Imagem em largura adaptável.
- Textos divididos em parágrafos e subtítulos curtos.
- Blocos de valores empilhados.

### Esboço textual
```text
┌────────────────────────────────────────────┐
│ LOGO                         MENU ☰        │
├────────────────────────────────────────────┤
│ SOBRE A FLOR E VIDA                        │
│ Frase de apresentação                      │
├────────────────────────────────────────────┤
│ IMAGEM INSTITUCIONAL │ HISTÓRIA DA EMPRESA │
├────────────────────────────────────────────┤
│ VALORES / DIFERENCIAIS                     │
│ [Ícone + texto] [Ícone + texto] [Ícone]    │
├────────────────────────────────────────────┤
│ NOSSA MISSÃO / COMPROMISSO                 │
│ Texto institucional                        │
│ [ENTRE EM CONTATO]                         │
├────────────────────────────────────────────┤
│                  RODAPÉ                    │
└────────────────────────────────────────────┘
```

## 5.6 Página Contato

**Objetivo:** facilitar a comunicação entre visitantes e a floricultura.

### Estrutura do cabeçalho
- Cabeçalho compartilhado, com “Contato” identificado como página atual.

### Organização do conteúdo e seções

1. **Título**
   - “Fale Conosco”.
   - Texto breve convidando o visitante a entrar em contato.

2. **Informações de contato**
   - Endereço.
   - Telefone.
   - WhatsApp, se utilizado oficialmente.
   - Horário de funcionamento.
   - Redes sociais oficiais.

3. **Formulário**
   - Campo Nome.
   - Campo E-mail.
   - Campo Assunto, se necessário.
   - Campo Mensagem.
   - Botão “Enviar mensagem”.
   - Mensagem de confirmação ou erro após o envio.

4. **Localização**
   - Mapa incorporado ou imagem/indicação de localização, caso o endereço esteja confirmado.
   - Endereço textual acessível, não apenas o mapa.

### Posicionamento dos botões
- Botões ou links de telefone e WhatsApp junto às informações de contato.
- Botão “Enviar mensagem” abaixo dos campos do formulário.
- Link para abrir rota/localização próximo ao mapa, se disponível.

### Organização das imagens
- Mapa na parte inferior ou ao lado das informações.
- Não utilizar imagem decorativa que prejudique a leitura do formulário.

### Rodapé
Rodapé compartilhado.

### Comportamento mobile
- Informações de contato antes do formulário.
- Formulário em coluna única.
- Campos e botão ocupando a largura disponível.
- Mapa responsivo, sem ultrapassar a largura da tela.
- Links de telefone e WhatsApp acionáveis por toque.

### Esboço textual
```text
┌────────────────────────────────────────────┐
│ LOGO                         MENU ☰        │
├────────────────────────────────────────────┤
│                 FALE CONOSCO               │
│            Texto de apresentação           │
├────────────────────────────────────────────┤
│ INFORMAÇÕES             FORMULÁRIO         │
│ Endereço                [Nome]             │
│ Telefone                [E-mail]           │
│ WhatsApp                [Assunto]          │
│ Redes sociais           [Mensagem]         │
│                         [ENVIAR]           │
├────────────────────────────────────────────┤
│              MAPA / LOCALIZAÇÃO            │
├────────────────────────────────────────────┤
│                  RODAPÉ                    │
└────────────────────────────────────────────┘
```

## 5.7 Página 404 — Página não encontrada

**Objetivo:** informar que o endereço acessado não existe ou não está disponível e oferecer um caminho de retorno.

### Estrutura do cabeçalho
- Cabeçalho simplificado, com logotipo e acesso à página inicial.
- Manter o menu completo apenas se não prejudicar a clareza da página.

### Organização do conteúdo e seções
1. Código “404” em destaque.
2. Mensagem “Página não encontrada”.
3. Texto breve explicando que o conteúdo pode ter sido removido ou o endereço digitado incorretamente.
4. Link ou botão para retornar à página inicial.
5. Opcionalmente, links para as principais categorias.

### Posicionamento dos botões
- Botão “Voltar para a página inicial” centralizado abaixo da mensagem.
- Links secundários para categorias, se forem úteis.

### Organização das imagens
- Ilustração floral simples como elemento de apoio.
- A imagem não deve competir com o código 404 e a ação principal.

### Rodapé
- Rodapé simplificado com logotipo, contato e links principais.

### Comportamento mobile
- Conteúdo centralizado em uma coluna.
- Código e mensagem com leitura clara.
- Botão principal largo e fácil de tocar.
- Ilustração ajustada à largura da tela.

### Esboço textual
```text
┌────────────────────────────────────────────┐
│ LOGO                              INÍCIO   │
├────────────────────────────────────────────┤
│                                            │
│                  404                       │
│          PÁGINA NÃO ENCONTRADA             │
│       Texto breve de orientação            │
│       [VOLTAR PARA A PÁGINA INICIAL]       │
│                                            │
├────────────────────────────────────────────┤
│ RODAPÉ SIMPLIFICADO                        │
└────────────────────────────────────────────┘
```

---

# 6. Diretrizes de responsividade

| Elemento | Desktop | Mobile |
|---|---|---|
| Cabeçalho | Logo e menu horizontal | Logo e menu hambúrguer |
| Banner | Texto e imagem lado a lado | Elementos empilhados |
| Categorias | Grade com várias colunas | Duas colunas ou rolagem horizontal |
| Produtos | Grade de três ou quatro colunas | Uma ou duas colunas |
| Filtros | Lateral ou acima do catálogo | Painel expansível |
| Formulário | Pode ficar ao lado das informações | Uma coluna |
| Mapa | Largura da seção | Largura total disponível |
| Rodapé | Blocos lado a lado | Blocos empilhados |

## 7. Hierarquia e usabilidade

- Cada página deve ter um título principal claro.
- Ações principais devem estar próximas do conteúdo relacionado.
- Links e botões devem ter rótulos que indiquem seu destino ou ação.
- A navegação deve permitir retornar facilmente à página inicial e às categorias.
- Imagens devem possuir textos alternativos descritivos na implementação.
- Formulários devem identificar campos obrigatórios e apresentar retorno após o envio.
- A página não deve depender exclusivamente de imagens para transmitir informações.
- Evitar excesso de elementos simultâneos e manter espaçamento consistente.

## 8. Inventário de elementos para desenhar no Figma ou no papel

- [ ] Cabeçalho desktop.
- [ ] Cabeçalho mobile e menu aberto.
- [ ] Rodapé desktop e mobile.
- [ ] Card de categoria.
- [ ] Card de produto.
- [ ] Banner principal.
- [ ] Área de filtros.
- [ ] Paginação.
- [ ] Formulário de contato.
- [ ] Bloco de informações de contato.
- [ ] Bloco de mapa.
- [ ] Estado de página 404.

## 9. Entrega e validação

Os wireframes devem ser desenhados em escala de cinza ou apenas com contornos e blocos neutros, sem definir a identidade cromática ou tipográfica nesta etapa. Recomenda-se criar, no mínimo, uma versão desktop e uma versão mobile para cada página.

Antes de avançar para o protótipo visual, validar:
1. Se todas as páginas previstas na arquitetura estão contempladas.
2. Se os caminhos entre páginas estão claros.
3. Se as ações principais estão visíveis e bem posicionadas.
4. Se o conteúdo cabe adequadamente em telas menores.
5. Se os dados comerciais, endereço, contatos, catálogo e horários foram confirmados pela empresa.

**Resultado esperado:** um conjunto de wireframes de baixa fidelidade que sirva como base para a prototipação e, posteriormente, para o desenvolvimento do site institucional.
