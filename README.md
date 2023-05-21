<h1>OCR para busca de ocorrências de palavras em imagens<br><h1>

  <h4>Este é um projeto que utiliza a tecnologia de OCR (Optical Character Recognition) para buscar ocorrências de palavras em imagens. O OCR é capaz de extrair texto de imagens, permitindo realizar buscas e análises de conteúdo textual em documentos visuais.<h4><br>
 
   
   <h1> Funcionalidades <h1>
<h4>- Carrega imagens a partir de um diretório especificado.<br>
- Utiliza o OCR para processar cada imagem e extrair o texto contido nelas.<br>
- Realiza a busca de ocorrências de palavras específicas nas imagens.<br>
- Retorna o número de ocorrências encontradas para cada imagem.<br>
- Mostra as imagens processadas, destacando as ocorrências encontradas.<h4><br>
  <br>
  <h1> Configuração do ambiente <h1>
   <h3> Antes de executar o projeto, é necessário configurar o ambiente seguindo as instruções abaixo:<br><h3>
     <h4>- Certifique-se de ter instalado a biblioteca OpenCV (cv2) e as dependências do Tesseract OCR.<br>
     -Baixe o arquivo contendo o modelo de linguagem apropriado para o Tesseract OCR, de acordo com o idioma dos textos nas imagens a serem processadas.<h4><br>
     <h1>Utilização<h1>
       
  <h4> - Coloque as imagens que deseja processar em um diretório específico.<br>

- Abra o arquivo main.py e configure as variáveis caminho e termo_pesquisa de acordo com as suas necessidades.<br>

- caminho: Especifique o diretório onde as imagens estão localizadas.<br>
-termo_pesquisa: Defina a palavra ou termo que deseja buscar nas imagens.<br>
Execute o arquivo main.py.<br>

- O projeto irá percorrer todas as imagens no diretório especificado, processá-las utilizando OCR e buscar as ocorrências do termo de pesquisa.<br>

- O número de ocorrências encontrado para cada imagem será exibido no console, juntamente com o nome da imagem.<br>

- As imagens processadas serão exibidas, destacando as ocorrências encontradas.<br><h4><br>
   <h1> Conclusão<h1>
    <h4> Este projeto de OCR para busca de ocorrências de palavras em imagens pode ser uma ferramenta útil para análise de documentos visuais e extração de informações textuais. Personalize-o de acordo com suas necessidades e explore as possibilidades de aplicação em diversos domínios, como processamento de documentos, automação.<h4>
