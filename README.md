# Cadastro Automático de Notas Fiscais

Este projeto tem como objetivo automatizar o processo de cadastro de produtos a partir de notas fiscais. A partir de uma imagem ou PDF de uma nota fiscal, o programa realiza a leitura das informações dos produtos (como nome e custo), organiza os dados e os insere automaticamente no sistema de gestão de estoque (GestãoClick).

## Funcionalidades
- Leitura de notas fiscais em formato de imagem ou PDF utilizando OCR.
- Processamento das informações extraídas para identificar campos como nome e custo dos produtos.
- Automação do cadastro no sistema GestãoClick usando Selenium.
- Funcionalidade adicional: cálculo automático de preço de venda com margem de lucro.

## Tecnologias Utilizadas
- **Python**: Linguagem principal do projeto.
- **Tesseract OCR**: Para leitura de texto a partir das imagens das notas fiscais.
- **Selenium**: Para automação do preenchimento de dados no sistema de gestão.
- **Pandas**: Para organizar os dados extraídos em tabelas.

## Como Executar

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/cadastro_automatico_notas_fiscais.git
    cd cadastro_automatico_notas_fiscais
    ```

2. Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```

3. Certifique-se de ter o Tesseract OCR instalado em seu sistema:
    - **Windows**: [Download do Tesseract](https://github.com/tesseract-ocr/tesseract)
    - **Linux**: 
      ```bash
      sudo apt-get install tesseract-ocr
      ```

4. Execute o script principal:
    ```bash
    python main.py
    ```

## Estrutura do Projeto



## Contribuindo
Sinta-se à vontade para abrir issues e pull requests para melhorias e sugestões. Toda contribuição é bem-vinda!

## Licença
Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.


