# 🎨 Design System - Gamebox
Neste projeto, utilizamos um framework UI e aplicamos customizações pontuais para refletir a identidade visual.

### 1. Framework Base

- **Framework escolhido:** MaterializeCSS
- **Motivação:** Oferece componentes baseados no Material Design, permitindo uma prototipagem rápida e um visual corporativo, limpo e confiável.

### 2. Paleta de Cores (Customização)

As variáveis de cor do framework foram escolhidas para induzir o usuário ao erro ou alertá-lo (tarde demais) sobre as taxas:

- **Cor Primária:** `#B026FF` - CTAs, estados ativos, barras de progresso brilhantes

- **Fundo:** `#09090E` - Fundo do aplicativo, vácuo profundo

- **Superfície:** `#151520` - Cartões, modais (bottom sheets), campos de entrada

- **Texto:** `#F8F8F8` - Texto principal de leitura

- **Suave:** `#828291` - Marcações de tempo, rótulos secundários, bordas

- **Destaque:** `#00FF66` - Marcas de seleção de conclusão, altas pontuações de análise, notificações de sucesso!").

### 3. Tipografia

Importada via Google Fonts para substituir a fonte padrão do navegador e dar um ar mais moderno:

-Títulos: Space Grotesk, 700, 24-32px
Corpo: Outfit, 400, 16px
Texto pequeno: Outfit, 400, 14px
Estatísticas/Números: Chakra Petch, 600, 18px

### 4. Diretrizes de Uso de Componentes

Regras para a aplicação dos componentes do MaterializeCSS dentro da lógica predatória do Roubank:

- **Botões de Ação (`.btn`):** Ações que resultam em cobrança de taxas devem usar o modificador `.btn-large` e a cor primária (vermelho), para chamar atenção e induzir o clique. Ações de cancelamento ou fuga usam botões sem preenchimento (`.btn-flat`) para passarem despercebidos.
- **Cards (`.card`):** Usados obrigatoriamente para exibir o Saldo em destaque e encapsular as listagens do Extrato. Devem usar a sombra padrão (`z-depth-1`).
- **Formulários (`.input-field`):** Os inputs devem ser largos e burocráticos.
