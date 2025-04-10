# NppExcelUDL

Disponibilizar instruções de como adicionar ao editor Notepad++[^1], realce de sintaxe customizado, *User Defined Language (UDL)*[^2], com base nas fórmulas do **Excel 365 (PT-BR)**. Bem como preenchimento automático das funções[^3] e apresentação de seus respectivos argumentos.

# 1. Destaque de Sintaxe

Este recurso colore e estiliza o texto para facilitar a leitura e a compreensão.

Para o caso, faça o download do arquivo [EXCEL UDL.xml](EXCEL%20UDL.xml)

No Notepad++ acesse no menu `Linguagem` > `Linguagem definida pelo usuário` > `Defina a sua linguagem...`

Clique no botão `Importar...` e selecione o arquivo que baixou.


# 2. Autocompletar Funções

Além da sintaxe personalizada, é possível implementar o preenchimento automático das funções conhecidas.

Baixe o arquivo [EXCEL.xml](EXCEL.xml) e salve-o na subpasta `autoCompletion` da pasta onde o Notepad++ foi instalado.

Caso tenha mantido o caminho padrão, será: `%ProgramFiles%\Notepad++\autoCompletion\`

Cabe destacar que, diferentemente de alguns arquivos de configuração, este não funcionará através do caminho `"%AppData%\Notepad++\...`


## 2.1 Dicas de parâmetros

O arquivo de definição de preenchimento automático pode especificar se uma palavra-chave é uma função. Quando o nome de uma função é digitado, seguido pelo parêntese de abertura usado para delimitar os argumentos da função, o Notepad++ exibirá uma dica, uma pequena caixa no estilo de dica de ferramenta, contendo a descrição da função e seus argumentos.


[^1]: [Notepad++](https://notepad-plus-plus.org/)
[^2]: [Syntax Highlighting - User Defined Languages | Notepad++ User Manual](https://npp-user-manual.org/docs/user-defined-language-system/)
[^3]: [Auto-Completion | Notepad++ User Manual](https://npp-user-manual.org/docs/auto-completion/)
