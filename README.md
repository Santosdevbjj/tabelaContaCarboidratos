## Tabela Para Contagem de Carboidratos.

Ferramentas Low Code 

A ideia é criar uma aplicação completa com uma interface amigável, a solução ideal seria combinar as ferramentas:

​Use o Make para o "cérebro" da aplicação, lidando com a lógica de geração do menu.

​Use o Lovable para construir a interface visual (a parte que o usuário vê e interage), que se comunicaria com o fluxo de trabalho do Make para obter o menu gerado.



Lovable: Esta plataforma é excelente para a criação de interfaces de usuário (front-end). Você poderia usá-la para construir uma tela bonita e intuitiva onde o usuário clica em um botão "Gerar Menu" e visualiza o resultado. 

No entanto, o Lovable não é projetado para lidar com a lógica complexa de processamento de dados e regras de negócio, como somar carboidratos ou selecionar alimentos aleatoriamente de uma base de dados. O Lovable seria o "corpo" da aplicação, mas não o "cérebro".

​Make: O Make é uma ferramenta de automação e fluxo de trabalho (back-end), e é aqui que a lógica do seu projeto reside. O Make pode:
​Ler dados: Conectar-se a uma planilha (como a tabela de carboidratos) ou a uma base de dados.

​Processar regras: Criar um fluxo de trabalho que selecione alimentos com base em critérios estritos (ex: CHO = 0,00 ou < 5).
​Calcular: Somar o valor dos carboidratos a cada seleção para garantir que o limite de 15g não seja ultrapassado.
​Gerar a saída: Criar o menu final com base nos alimentos selecionados.


