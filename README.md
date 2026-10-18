# Contador

Contador de calorias, proteínas, carboidratos e gorduras por refeição, com a tabela TACO (Unicamp) e alimentos comuns com porções caseiras.

Acesse: https://anapaulaaraujorocha-ops.github.io/contador/

Entre com sua conta Google para salvar os registros na nuvem (Firebase) e usar o mesmo histórico no celular e no computador. Sem login, os dados ficam só no navegador do aparelho; nesse caso use "Exportar dados" e "Importar dados" (aba Dieta) para backup.

## Pratos prontos e cálculos

- Aba **✨ IA** (padrão ao adicionar): descreva o que comeu ou mande uma foto do prato. A IA (Gemini, pelo Firebase AI Logic) separa cada alimento, estima o peso e calcula calorias e macros, e você confere antes de adicionar. Para funcionar, o Firebase AI Logic precisa estar ativado no projeto `contador-76398` com a Gemini Developer API.

- A busca inclui a tabela TACO, cerca de 160 pratos prontos da USDA traduzidos (peixes, frangos, frituras, massas, fast food) e mais de 90 versões empanadas, fritas, na air fryer e grelhadas calculadas a partir dos alimentos crus.
- Aba **Preparo**: escolha o alimento cru e o modo de preparo. A conta considera a perda de água (rendimento), o óleo absorvido e o empanamento, e todos esses números podem ser ajustados.
- Aba **Receita**: some os ingredientes, informe o peso final e as porções, e salve a receita em "Meus alimentos".
- Botão **Procurar produto de marca na internet**: busca no Open Food Facts.

Fontes: TACO 4ª ed. (NEPA/Unicamp); USDA FoodData Central SR Legacy (dados via TempoLife, tempolife.app, CC-BY-4.0); Open Food Facts (ODbL).
