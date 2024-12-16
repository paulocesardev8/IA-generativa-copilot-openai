# Reconhecimento de Texto em Imagens

## Sobre o Projeto
Este repositório contém um projeto de reconhecimento de texto em imagens utilizando ferramentas como OCR (Tesseract, OpenCV, etc.). 

O projeto está organizado para facilitar a manipulação e o entendimento dos dados de entrada e saída.

---

## Estrutura do Repositório
- **inputs/**: Contém as imagens utilizadas como entrada para o processo de reconhecimento.
- **output/**: Contém os resultados extraídos das imagens em arquivos de texto ou JSON.

---

## Ferramentas Utilizadas
- **Python**: Linguagem principal para o script de processamento.
- **Tesseract OCR**: Ferramenta de OCR para extração de texto.
- **OpenCV**: Para pré-processamento das imagens, como conversão para escala de cinza e binarização.

---

## Passos Realizados
1. **Pré-processamento das Imagens**:
   - As imagens foram convertidas para escala de cinza e binarizadas para melhorar a detecção de texto.
   
2. **Extração do Texto**:
   - Utilizamos a biblioteca Tesseract OCR para identificar e extrair o texto das imagens.

3. **Organização dos Resultados**:
   - Os textos extraídos foram salvos na pasta `output` em arquivos `.txt` ou `.json`.

---

## Resultados

### Exemplo de Imagem Processada
**Imagem Original (inputs):**
![Imagem Original](inputs/exemplo.png)

**Resultado Extraído (output):**
