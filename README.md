# Projeto Certificado 
Este projeto é uma automatização de assinaturas de certificado desenvolvido em Python utilizando a biblioteca Pillow e Openpyxl. Ele facilita a emissão de certificados personalizados (com fonte e assinatura) para cada aluno da base de dados. 

### Funcionalidades
- Assinatura automática para múltiplos documentos em lote
- Exportar o documento assinado em diferentes formatos
- Inserir assinaturas digitais ou imagens de assinatura em posições definidas
- Interface gráfica simples para selecionar arquivos e assinar

### Estrutura do Projeto
- `planilha_alunos.xlsx` → base de dados
- `certificado_padrao.jpg` → imagem base
- `tahoma.ttf` → fonte para o certificado
- `app.py` → import Openpyxl, biblioteca para ler, criar e modificar arquivos do Excel;<br>
→ import Pillow biblioteca para trabalhar com imagens no python (abrir, criar, modificar, redimensionar, converter formatos e
salvar imagens)</p>

### Tecnologias Utilizadas
- **Python 3**
- **Pillow**
- **Openpyxl**
