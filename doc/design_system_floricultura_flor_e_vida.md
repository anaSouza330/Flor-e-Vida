# Design System — Floricultura Flor e Vida

## 1. Apresentação

Este documento define um Design System para o site institucional da **Floricultura Flor e Vida**, organizado para orientar a criação das interfaces e facilitar a implementação posterior em CSS ou Tailwind CSS.

### Premissas

Os dados de identidade visual enviados no pedido continham placeholders (`[COR]`, `[FONTE]` etc.). Para elaborar este documento, foram utilizadas as referências visuais e a proposta de identidade já discutidas anteriormente:

- Conceito: **Botanical Elegance**.
- Cor primária: verde-floresta `#183D2B`.
- Cor secundária: verde botânico `#52734A`.
- Cores complementares: verde-sálvia, marfim, pêssego e rosa floral.
- Títulos: Playfair Display.
- Textos e interface: Montserrat.

**Importante:** esta é a sistematização da proposta anterior, não a confirmação de um manual oficial da marca. Caso a empresa possua um guia de identidade visual aprovado, ele deve prevalecer.

## 2. Princípios do Design System

1. **Consistência:** componentes equivalentes devem ter a mesma aparência e comportamento em todas as páginas.
2. **Clareza:** hierarquia visual e textos objetivos devem facilitar a navegação.
3. **Elegância:** utilizar elementos visuais com moderação, sem excesso de ornamentos.
4. **Natureza:** dar destaque às fotografias de flores, plantas e arranjos.
5. **Acessibilidade:** garantir contraste, navegação por teclado, textos alternativos e áreas de toque adequadas.
6. **Responsividade:** adaptar o conteúdo a desktop, tablet e celular.

---

## 3. Paleta de cores

### 3.1 Cores principais

| Token | Nome | HEX | Uso |
|---|---|---|---|
| `color-primary` | Verde-floresta | `#183D2B` | Botões principais, links destacados e elementos de marca |
| `color-secondary` | Verde botânico | `#52734A` | Botões secundários, ícones e destaques |
| `color-sage` | Verde-sálvia | `#A8B59A` | Fundos de apoio e áreas suaves |

### 3.2 Cores complementares e neutras

| Token | Nome | HEX | Uso |
|---|---|---|---|
| `color-ivory` | Marfim | `#F7F2EB` | Fundo principal |
| `color-peach` | Pêssego | `#F2C5AA` | Detalhes decorativos e destaques pontuais |
| `color-floral-pink` | Rosa floral | `#D96F83` | Pequenos destaques florais |
| `color-text` | Texto principal | `#26352B` | Títulos e textos |
| `color-muted` | Texto secundário | `#687368` | Legendas e descrições auxiliares |
| `color-border` | Borda | `#E6E0D6` | Bordas e divisores |
| `color-white` | Branco | `#FFFFFF` | Cards e superfícies |

### 3.3 Regras de aplicação

- O verde-floresta deve ser a principal referência visual da interface.
- O verde botânico deve apoiar a navegação e os estados interativos.
- Marfim e branco devem manter áreas de leitura claras.
- Pêssego e rosa floral devem ser usados com moderação.
- Não utilizar as cores complementares em grandes áreas sem necessidade.
- Verificar contraste entre texto e fundo, especialmente em botões, links e textos pequenos.

---

## 4. Tipografia

### 4.1 Famílias tipográficas

| Aplicação | Fonte | Pesos recomendados |
|---|---|---|
| Títulos e chamadas | Playfair Display | 600, 700 |
| Parágrafos e interface | Montserrat | 400, 500, 600, 700 |

### 4.2 Hierarquia tipográfica — desktop

| Elemento | Tamanho | Peso | Uso |
|---|---:|---:|---|
| H1 | 48 px | 700 | Título principal da página |
| H2 | 36 px | 700 | Títulos de seção |
| H3 | 28 px | 600 | Subtítulos |
| H4 | 22 px | 600 | Títulos de cards e blocos |
| H5 | 18 px | 600 | Títulos menores |
| Corpo | 16 px | 400 | Parágrafos |
| Corpo pequeno | 14 px | 400 | Informações auxiliares |
| Legenda | 12 px | 400 | Legendas e metadados |
| Botão | 14–16 px | 600 | Rótulos de ações |

### 4.3 Hierarquia tipográfica — mobile

| Elemento | Tamanho |
|---|---:|
| H1 | 34 px |
| H2 | 28 px |
| H3 | 24 px |
| H4 | 20 px |
| H5 | 18 px |
| Corpo | 16 px |
| Corpo pequeno | 14 px |
| Legenda | 12 px |

### 4.4 Regras tipográficas

- Utilizar Playfair Display em títulos e chamadas de destaque.
- Utilizar Montserrat em parágrafos, menus, botões, formulários e informações de produtos.
- Manter altura de linha entre 1.4 e 1.7 para textos corridos.
- Evitar parágrafos extensos sem subtítulos.
- Não utilizar muitos pesos tipográficos no mesmo bloco.
- Carregar as fontes com alternativas de segurança caso o serviço de fontes não esteja disponível.

---

## 5. Botões

### 5.1 Botão primário

Uso: ação principal de uma página, como “Conheça nossas flores” ou “Enviar mensagem”.

- Fundo: `#183D2B`.
- Texto: `#FFFFFF`.
- Borda: nenhuma ou `#183D2B`.
- Raio: 8 px.
- Altura mínima: 44 px.
- Padding sugerido: 12 px 24 px.
- Fonte: Montserrat, 600, 14–16 px.

### 5.2 Botão secundário

Uso: ações de apoio, como “Saiba mais”.

- Fundo: transparente.
- Texto: `#52734A`.
- Borda: 1 px solid `#52734A`.
- Raio: 8 px.
- Altura mínima: 44 px.
- Padding sugerido: 12 px 24 px.

### 5.3 Botão terciário ou link

Uso: ações de menor destaque, como “Ver detalhes”.

- Fundo: transparente.
- Sem borda obrigatória.
- Texto: `#52734A`.
- Fonte: Montserrat, 600.
- Deve possuir estado de foco visível.

### 5.4 Estados dos botões

| Estado | Aparência sugerida |
|---|---|
| Normal | Fundo e texto conforme a variante |
| Hover | Alterar o fundo para uma tonalidade de interação, mantendo contraste |
| Focus-visible | Contorno externo visível, por exemplo 2 px, com afastamento de 2 px |
| Active | Escurecer levemente o fundo ou aplicar feedback visual |
| Disabled | Reduzir destaque visual e impedir interação |
| Loading | Exibir indicador de carregamento e evitar envio repetido |

Para o botão primário, pode-se usar `#52734A` no hover. O estado disabled pode usar `#A8B59A` com texto branco, desde que a legibilidade seja verificada.

---

## 6. Formulários

### 6.1 Campos padrão

Os campos devem apresentar:

- Rótulo visível acima do campo.
- Área de entrada com altura mínima de 44 px.
- Borda de 1 px na cor `#E6E0D6`.
- Fundo branco.
- Texto em `#26352B`.
- Texto de orientação em `#687368`.
- Raio de 6 a 8 px.
- Espaçamento consistente entre campos.

### 6.2 Exemplo de campos

| Campo | Tipo | Observação |
|---|---|---|
| Nome | Texto | Obrigatório quando necessário para responder |
| E-mail | E-mail | Validar formato |
| Assunto | Texto ou seleção | Opcional conforme necessidade |
| Mensagem | Área de texto | Permitir texto em várias linhas |

### 6.3 Estados dos campos

| Estado | Aparência |
|---|---|
| Normal | Borda `#E6E0D6` |
| Hover | Borda com maior destaque |
| Focus | Borda verde e contorno de foco visível |
| Erro | Borda de erro e mensagem textual explicativa |
| Sucesso | Mensagem de confirmação após envio |
| Disabled | Fundo e texto atenuados |

Mensagens de erro não devem depender somente da cor: devem explicar o que precisa ser corrigido. O formulário deve informar quando um campo é obrigatório e apresentar retorno após o envio.

---

## 7. Cards e elementos reutilizáveis

### 7.1 Card de produto

Estrutura:
1. Imagem do produto.
2. Nome do produto.
3. Preço, somente se a empresa optar por divulgar e mantiver o dado atualizado.
4. Botão ou link “Ver detalhes” ou “Consultar”.

Regras:
- Fundo branco.
- Borda opcional `#E6E0D6`.
- Raio sugerido: 10 px.
- Imagem com proporção consistente dentro de uma mesma grade.
- Espaçamento interno: 16 px.
- Não exibir disponibilidade ou preço sem confirmação da floricultura.

### 7.2 Card de categoria

Estrutura:
- Imagem ou ilustração.
- Nome da categoria.
- Link para a página correspondente.

Uso: categorias como Buquês, Plantas e Presentes, conforme o catálogo real.

### 7.3 Card institucional

Estrutura:
- Ícone ou imagem opcional.
- Título curto.
- Texto descritivo.

Uso: apresentação de valores, diferenciais ou informações institucionais confirmadas.

### 7.4 Outros componentes reutilizáveis

- Cabeçalho e menu de navegação.
- Menu mobile.
- Rodapé.
- Banner principal (hero).
- Breadcrumbs, caso a navegação tenha níveis.
- Grade de produtos.
- Filtros e paginação.
- Galeria de imagens.
- Bloco de chamada para contato.
- Formulário de contato.
- Bloco de endereço e informações.
- Mapa ou bloco de localização.
- Mensagens de erro, sucesso e vazio.

---

## 8. Bordas, sombras e espaçamentos

### 8.1 Bordas

| Token | Valor | Uso |
|---|---|---|
| `radius-sm` | 4 px | Elementos pequenos |
| `radius-md` | 8 px | Botões e campos |
| `radius-lg` | 10 px | Cards |
| `radius-xl` | 16 px | Blocos de destaque |
| `border-default` | 1 px solid `#E6E0D6` | Cards, campos e divisores |

### 8.2 Sombras

Usar sombras discretas, sem exagerar no relevo.

| Token | Valor CSS sugerido | Uso |
|---|---|---|
| `shadow-sm` | `0 1px 3px rgba(38, 53, 43, 0.08)` | Cards |
| `shadow-md` | `0 4px 12px rgba(38, 53, 43, 0.10)` | Menus e elementos elevados |
| `shadow-lg` | `0 8px 24px rgba(38, 53, 43, 0.12)` | Modal ou sobreposição |

### 8.3 Escala de espaçamento

Adotar uma escala baseada em múltiplos de 4 px.

| Token | Valor |
|---|---:|
| `space-1` | 4 px |
| `space-2` | 8 px |
| `space-3` | 12 px |
| `space-4` | 16 px |
| `space-5` | 20 px |
| `space-6` | 24 px |
| `space-8` | 32 px |
| `space-10` | 40 px |
| `space-12` | 48 px |
| `space-16` | 64 px |
| `space-20` | 80 px |

Recomendação:
- Espaçamento entre campos: 16 px.
- Padding interno de cards: 16–24 px.
- Espaçamento entre seções: 48–80 px no desktop e 32–48 px no mobile.
- Largura máxima de conteúdo: aproximadamente 1200 px, ajustável ao layout.

---

## 9. Responsividade

### 9.1 Breakpoints sugeridos

| Nome | Largura | Comportamento |
|---|---:|---|
| Mobile | até 639 px | Uma coluna ou duas colunas compactas |
| Tablet | 640–1023 px | Grades intermediárias |
| Desktop | 1024–1279 px | Layout amplo |
| Large desktop | 1280 px ou mais | Conteúdo centralizado com largura máxima |

### 9.2 Regras por componente

| Componente | Desktop | Mobile |
|---|---|---|
| Cabeçalho | Menu horizontal | Menu hambúrguer |
| Hero | Texto e imagem lado a lado | Conteúdo empilhado |
| Categorias | 3–4 colunas | 2 colunas ou rolagem horizontal |
| Produtos | 3–4 colunas | 1–2 colunas |
| Filtros | Lateral ou acima da grade | Painel expansível |
| Formulário | Pode ficar ao lado das informações | Coluna única |
| Rodapé | Blocos lado a lado | Blocos empilhados |
| Botões | Largura conforme conteúdo | Largura total quando necessário |

### 9.3 Regras gerais

- Evitar rolagem horizontal.
- Redimensionar imagens sem distorção.
- Manter áreas de toque confortáveis, preferencialmente com pelo menos 44 × 44 px.
- Adaptar tamanhos de títulos para telas menores.
- Preservar ordem lógica de leitura.
- Não esconder informações essenciais exclusivamente no hover.

---

## 10. Componentes por página

| Página | Componentes previstos |
|---|---|
| Início | Cabeçalho, hero, cards de categoria, cards de produto, seção institucional, chamada para contato, rodapé |
| Buquês | Cabeçalho, título/banner, filtros, grade de produtos, paginação, chamada para contato, rodapé |
| Plantas | Cabeçalho, título/banner, categorias, filtros, grade de produtos, chamada para contato, rodapé |
| Presentes | Cabeçalho, título/banner, cards de categoria, grade de produtos, chamada para contato, rodapé |
| Sobre | Cabeçalho, título, imagem institucional, texto, blocos de valores/diferenciais, chamada para contato, rodapé |
| Contato | Cabeçalho, informações de contato, formulário, mapa/localização, rodapé |
| 404 | Cabeçalho simplificado, mensagem de erro, botão para início, rodapé simplificado |

---

## 11. Tokens para CSS

Os tokens abaixo podem ser utilizados como base no arquivo global de estilos.

```css
:root {
  /* Cores */
  --color-primary: #183D2B;
  --color-secondary: #52734A;
  --color-sage: #A8B59A;
  --color-ivory: #F7F2EB;
  --color-peach: #F2C5AA;
  --color-floral-pink: #D96F83;
  --color-text: #26352B;
  --color-muted: #687368;
  --color-border: #E6E0D6;
  --color-white: #FFFFFF;

  /* Tipografia */
  --font-heading: "Playfair Display", Georgia, serif;
  --font-body: "Montserrat", Arial, sans-serif;

  /* Tamanhos */
  --text-xs: 0.75rem;
  --text-sm: 0.875rem;
  --text-base: 1rem;
  --text-lg: 1.125rem;
  --text-xl: 1.375rem;
  --text-2xl: 1.75rem;
  --text-3xl: 2.25rem;
  --text-4xl: 3rem;

  /* Espaçamentos */
  --space-1: 0.25rem;
  --space-2: 0.5rem;
  --space-3: 0.75rem;
  --space-4: 1rem;
  --space-5: 1.25rem;
  --space-6: 1.5rem;
  --space-8: 2rem;
  --space-10: 2.5rem;
  --space-12: 3rem;
  --space-16: 4rem;
  --space-20: 5rem;

  /* Bordas e sombras */
  --radius-sm: 4px;
  --radius-md: 8px;
  --radius-lg: 10px;
  --radius-xl: 16px;
  --border-default: 1px solid var(--color-border);
  --shadow-sm: 0 1px 3px rgba(38, 53, 43, 0.08);
  --shadow-md: 0 4px 12px rgba(38, 53, 43, 0.10);
  --shadow-lg: 0 8px 24px rgba(38, 53, 43, 0.12);

  /* Layout */
  --container-max: 1200px;
  --content-gutter: 24px;
}

body {
  color: var(--color-text);
  background: var(--color-ivory);
  font-family: var(--font-body);
  font-size: var(--text-base);
  line-height: 1.6;
}

h1, h2, h3, h4, h5, h6 {
  font-family: var(--font-heading);
  line-height: 1.2;
}

.container {
  width: min(100% - 2 * var(--content-gutter), var(--container-max));
  margin-inline: auto;
}

.button {
  min-height: 44px;
  padding: 12px 24px;
  border-radius: var(--radius-md);
  font-family: var(--font-body);
  font-weight: 600;
  cursor: pointer;
}

.button--primary {
  color: var(--color-white);
  background: var(--color-primary);
  border: 1px solid var(--color-primary);
}

.button--primary:hover {
  background: var(--color-secondary);
  border-color: var(--color-secondary);
}

.button:focus-visible {
  outline: 2px solid var(--color-secondary);
  outline-offset: 2px;
}

.card {
  background: var(--color-white);
  border: var(--border-default);
  border-radius: var(--radius-lg);
  box-shadow: var(--shadow-sm);
  padding: var(--space-4);
}

.form-field {
  width: 100%;
  min-height: 44px;
  padding: 12px;
  color: var(--color-text);
  background: var(--color-white);
  border: var(--border-default);
  border-radius: var(--radius-md);
  font: inherit;
}

.form-field:focus {
  border-color: var(--color-secondary);
  outline: 2px solid rgba(82, 115, 74, 0.2);
  outline-offset: 1px;
}

@media (max-width: 639px) {
  :root {
    --content-gutter: 16px;
  }

  h1 { font-size: 2.125rem; }
  h2 { font-size: 1.75rem; }
  h3 { font-size: 1.5rem; }
  h4 { font-size: 1.25rem; }
}
```

---

## 12. Exemplo de configuração para Tailwind CSS

Exemplo conceitual de extensão do tema. A sintaxe exata pode variar conforme a versão e a configuração do projeto.

```js
// tailwind.config.js
module.exports = {
  theme: {
    extend: {
      colors: {
        primary: "#183D2B",
        secondary: "#52734A",
        sage: "#A8B59A",
        ivory: "#F7F2EB",
        peach: "#F2C5AA",
        floralPink: "#D96F83",
        text: "#26352B",
        muted: "#687368",
        border: "#E6E0D6",
      },
      fontFamily: {
        heading: ['"Playfair Display"', "Georgia", "serif"],
        body: ['"Montserrat"', "Arial", "sans-serif"],
      },
      borderRadius: {
        sm: "4px",
        md: "8px",
        lg: "10px",
        xl: "16px",
      },
      maxWidth: {
        container: "1200px",
      },
      boxShadow: {
        soft: "0 1px 3px rgba(38, 53, 43, 0.08)",
        card: "0 4px 12px rgba(38, 53, 43, 0.10)",
      },
    },
  },
};
```

---

## 13. Checklist de implementação

- [ ] Confirmar a paleta e as fontes com a identidade visual oficial.
- [ ] Carregar Playfair Display e Montserrat no projeto.
- [ ] Criar tokens globais de cores, tipografia, espaçamento, bordas e sombras.
- [ ] Implementar botões com todos os estados.
- [ ] Implementar campos e mensagens de validação.
- [ ] Criar componentes reutilizáveis de cards.
- [ ] Criar cabeçalho desktop e menu mobile.
- [ ] Criar rodapé compartilhado.
- [ ] Aplicar breakpoints responsivos.
- [ ] Verificar contraste e foco por teclado.
- [ ] Testar os componentes nas páginas Início, Buquês, Plantas, Presentes, Sobre e Contato.

## 14. Resultado esperado

O Design System deve funcionar como referência única para a construção das interfaces da Floricultura Flor e Vida. A utilização de tokens e componentes reutilizáveis reduz inconsistências, facilita ajustes futuros e permite implementar o site com CSS ou Tailwind CSS.

A identidade visual deve ser validada com os arquivos oficiais da empresa antes da publicação. Não devem ser inventados dados comerciais, produtos, preços, contatos ou informações institucionais.
