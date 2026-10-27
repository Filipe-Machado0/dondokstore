# Manual de Instruções: Catálogo Digital & Painel da Lojista
## Dondok Store (Use DK) • Moda Feminina

---

### 📖 Visão Geral do Sistema

O **Catálogo Digital de Bolso** foi desenvolvido para funcionar como uma vitrine moderna e direta de conversão via WhatsApp e Instagram para a **Dondok Store (Use DK)**.

O sistema conta com dois ambientes em um só aplicativo:
1. **Visão da Cliente:** Vitrine fluida, responsiva para celular, com filtros, stories, sacola flutuante e fechamento rápido no WhatsApp.
2. **Painel da Lojista (Admin Demo):** Área administrativa para cadastrar, editar e excluir peças em tempo real, com fotos tiradas da câmera/galeria ou links da internet, sem depender de servidor externo.

---

### 🔑 1. Como Acessar o Painel da Lojista (Admin)

Você pode abrir o painel administrativo de duas formas simples na tela:

* **Método 1 (Topo da Página):** No cabeçalho principal, clique no botão cinza com o ícone de **engrenagem / configurações (`⚙️`)**, localizado entre a logo e o ícone do Instagram.
* **Método 2 (Barra de Categorias):** Logo acima dos botões de categoria, ao lado do texto *"X peças disponíveis"*, clique no botão verde **`+ Adicionar`**.

> O painel deslizará na tela como uma janela flutuante com a etiqueta **"PERFIL ADMIN"**.

---

### 👗 2. Como Cadastrar uma Nova Peça (Passo a Passo)

Ao abrir o painel, você já estará na aba **"Cadastrar Nova Peça"**. Siga as etapas abaixo:

#### Passo 1: Informações Básicas
* **Nome da Peça:** Digite o nome comercial do look (ex: *Vestido Chemise Denim Riviera* ou *Cropped Tricot Mint DK*).
* **Categoria:** Selecione em qual aba o produto será agrupado (*Vestidos*, *Conjuntos*, *Croppeds & Blusas* ou *Calças & Shorts*).

#### Passo 2: Preço e Destaque
* **Preço (R$):** Digite o valor em reais utilizando ponto para os centavos (ex: `189.90` ou `249.00`).
  > 💡 *O sistema calcula automaticamente o parcelamento em até 3x sem juros (ex: 3x de R$ 63,30) para exibir no card.*
* **Tag / Destaque:** Digite uma etiqueta de atenção para o card (ex: `Lançamento`, `Mais Vendido`, `Provador DK`, `Edição Limitada`, `Promoção`).

#### Passo 3: Tamanhos Disponíveis
* Marque as caixinhas dos tamanhos que a loja tem em estoque no provador:
  * **[ P ] [ M ] [ G ] [ GG ] [ Único ]**
  * Você pode marcar quantos quiser. O card no catálogo permitirá que a cliente escolha entre esses tamanhos antes de enviar a mensagem no WhatsApp.

#### Passo 4: Foto da Peça (2 Opções)
O sistema aceita fotos de duas maneiras muito práticas:
* **Opção A — Foto Direta do Aparelho (Recomendado):**
  1. Clique no botão **`Subir Foto do Aparelho`**.
  2. Escolha uma foto da galeria do celular ou tire uma foto na hora com a câmera do provador.
  3. A foto será convertida instantaneamente e aparecerá no quadradinho de **Prévia**.
* **Opção B — Link da Web:**
  1. Se você já tem a foto hospedada na internet, cole o link direto no campo *(ex: link do Unsplash, Imgur, etc.)*.
  2. A prévia será carregada imediatamente.

#### Passo 5: Descrição da Peça
* Descreva o caimento, tecido, fendas, forro e detalhes que ajudam na decisão de compra (ex: *Tecido crepe encorpado, não amassa, possui forro duplo e fenda lateral sutil.*).

#### Passo 6: Publicar no Catálogo
* Clique no botão verde de destaque: **`Salvar e Publicar no Catálogo`**.
* Uma notificação preta e verde (*Toast*) confirmará o sucesso no topo da tela.

---

### ✏️ 3. Como Editar uma Peça Existente

Se você precisar mudar o preço, trocar a foto ou atualizar os tamanhos disponíveis de uma peça:

1. Abra o Painel Admin (clique na engrenagem `⚙️`).
2. Clique na aba superior: **`Gerenciar Peças (X)`**.
3. Localize a peça na lista e clique no ícone de **lápis azul (`✏️`)** à direita.
4. O formulário será preenchido automaticamente com os dados atuais daquela peça.
5. Faça as alterações desejadas.
6. Clique no botão **`Salvar Alterações da Peça`**.
7. Pronto! A alteração refletirá imediatamente em todo o catálogo.

---

### 🗑️ 4. Como Excluir ou Restaurar Peças

#### Excluir uma peça específica:
1. No Painel Admin, acesse a aba **`Gerenciar Peças`**.
2. Clique no ícone de **lixeira vermelha (`🗑️`)** ao lado da peça que deseja remover.
3. Confirme o aviso do navegador. A peça sairá da vitrine imediatamente.

#### Restaurar Catálogo de Fábrica (Botão de Segurança):
* Caso queira limpar os testes da demonstração e voltar para as 6 peças originais com fotos profissionais, basta clicar em **`Restaurar Peças Iniciais`** no topo da lista.

---

### 🛒 5. Como Testar a Experiência da Cliente (Fluxo de Venda)

Após cadastrar uma nova peça no Admin:

1. Clique em **`Ver como Cliente`** (no rodapé do painel) ou no `✕` no topo para fechar o Admin.
2. Observe que a nova peça já aparece na grade de produtos e o contador de peças aumentou.
3. Clique na categoria da peça para testar o filtro.
4. Selecione o tamanho desejado no card (ex: **G**).
5. Clique no botão verde: **`Quero este no WhatsApp`**:
   * O WhatsApp da loja abrirá automaticamente com a mensagem personalizada pronta:
     > *"Olá! Vim pelo catálogo digital e tenho interesse na peça: [Nome], Tamanho: [G], Preço: [R$ X]. Ainda tem disponível?"*
6. Clique no botão **`Adicionar à Sacola`**:
   * A peça irá para a sacola flutuante no canto superior e inferior da tela.
   * Ao abrir a sacola, a cliente pode clicar em **`Enviar Sacola pelo WhatsApp`** para fechar múltiplos pedidos de uma só vez.

---

### 💾 6. Onde e como os dados ficam salvos?

* **Tecnologia `localStorage`:** O catálogo grava os dados na memória local do próprio navegador.
* **Vantagem:** Não precisa de banco de dados pago, login burocrático ou servidor para a dona da loja testar. Funciona offline, não perde os dados ao atualizar a página (F5) e roda com extrema velocidade.
