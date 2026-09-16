# RELATÓRIO-OPERACIONAL-DE-PRÉ-DECOLAGEM
RELATÓRIO OPERACIONAL DE PRÉ-DECOLAGEM (FIAP - Gabriel Bela dos Santos)

Este projeto tem como objetivo verificar as condições físicas e operacionais de uma espaçonave(Aurora-01) antes da decolagem.
Nesse tocante, os dados interpretados serão: Temperatura interna e externa, integridade estrutural, níveis de energia, pressão dos tanques e status dos módulos críticos.
Será realizada a verificação dessas variavéis, e depois será constatado se a decolagem pode seguir ou se a decolagem deve ser abortada. 
Caso a decolagem seja autorizada será realizada uma análise energética para saber a autonomia inicial da aeronave.
A IA também será responsável por fazer uma análise assistida do código, dos dados e identificar possíveis falhas.


# Como utilizar esse programa?

Instruções de uso:

1) Para iniciar clicar primeiro em "Executar Tudo"![Inicio](assets/inicio.png)

2) Ao iniciar esse programa será solicitado inserir as variavéis (Temperatura interna e externa, integridade estrutural, níveis de energia, pressão dos tanques e status dos módulos críticos.)
[Variáveis](assets/variáveis.png)

3) Preencha as variavéis assim como solicitado, lembrando que integridade e módulos críticos só podem receber "1" ou "0".[Inserir dados](assets/Inserir.png)

4) Após inserir os valores o programa iniciará a verificação.

5) O resultado será exibido para cada componete. 

6) Por fim, o resultado de "Autorizado para decolagem" ou "Decolagem abortada" aparecerá no final, após considerar todos componentes. [Resultado](assets/resultado.png)

7) Caso a decolagem seja autrizada, então digite 'enter' para iniciar a análise energética da nave. [Aperte Enter](assets/comando.png)

8) Os valores energéticos seram calculados e exibidos, será considerado também o nível de energia disponível inicialmente. [Análise energética](assets/energ.png)

9) Caso a decolagem seja abortada, então será exibida a mensagem e encerrado o programa.


Arquivos inseridos no projeto: assets(Imagens), README.md(Informações do projeto), .gitignore e ScrptDecolagem.ipynd(Código do programa). [Arquivos](assets/arquivos.png)