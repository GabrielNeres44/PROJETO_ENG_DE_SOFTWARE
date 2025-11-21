Este é um documento para leitura do grupo, adicionar informações a respeito do trabalho, descrever o que é cada arquivo, etc

----------------------------------------------------------------


FRONT-END
-Responsividade
-Media query
-Intuitividade
-Reutilização para aprimoramento de código

BACK-END
-Flask
-Receber e validar os dados enviados pelo formulário front-end
-Sem bibliotecas externas, deve persistir os dados #não sei oq isso significa
-Tem que ter tratamento de erros


----------------------------------------------------------------


    app.py
-Este será o arquivo principal da sua aplicação Flask. É aqui que você instanciará o seu aplicativo Flask e, idealmente, fará a chamada para inicializar a leitura do arquivo dados.csv. O arquivo dados.csv deve ser lido na inicialização da aplicação para que os dados estejam disponíveis para uso em qualquer parte da aplicação quando ela for iniciada.
    static/
-Esta pasta é onde ficam armazenados todos os arquivos estáticos da aplicação web (imagens, css, etc).
    templates/
-Esta pasta é onde o Flask procurará seus arquivos HTML (templates Jinja2).
    -base.html: Este é o template base que conterá a estrutura geral da sua aplicação (cabeçalho, rodapé, navegação). Outros templates irão "herdar" ou "estender" este template para reutilizar o layout.
    -index.html: O template da página inicial da sua aplicação.
    outros_templates.html: Exemplo de outros templates HTML necessários para diferentes páginas ou componentes da aplicação.

só pra testar