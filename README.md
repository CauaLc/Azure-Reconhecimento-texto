# 🚀 Reconhecimento de Texto em Imagens com Azure OpenAI

Este projeto utiliza a API de Visão Computacional do Azure OpenAI para extrair automaticamente texto de imagens.

## 📂 Estrutura do Projeto

📁 `inputs/` → Armazene aqui as imagens a serem processadas.  
📁 `output/` → Os arquivos `.txt` com os textos extraídos serão salvos aqui.  
📄 `script.py` → Código Python responsável pelo processamento das imagens.  
📄 `README.md` → Documentação sobre como utilizar o projeto.  

---

## 🛠 Pré-requisitos

1. **Criar uma conta no Azure**: Se ainda não tiver, acesse [portal.azure.com](https://portal.azure.com).
2. **Configurar o Azure OpenAI**: 
   - Crie um recurso OpenAI no Azure.
   - Obtenha o `AZURE_ENDPOINT` e `AZURE_API_KEY`.
3. **Instalar as dependências**:
   ```sh
   pip install requests pillow
   ```

---

## ▶️ Como Usar

1️⃣ **Configure o script**: Substitua `AZURE_ENDPOINT` e `AZURE_API_KEY` pelos seus valores reais no `script.py`.  
2️⃣ **Adicione imagens**: Coloque os arquivos `.jpg` ou `.png` na pasta `inputs/`.  
3️⃣ **Execute o script**:
   ```sh
   python script.py
   ```
4️⃣ **Confira os resultados**: Os textos extraídos serão salvos na pasta `output/` como arquivos `.txt`.

---

## 📌 Exemplo de Uso

Se houver uma imagem `exemplo.jpg` na pasta `inputs/`, após rodar o script, o texto extraído será salvo em:
```
output/exemplo.txt
```

---

## 🔗 Como Compartilhar no GitHub

1. Crie um repositório no GitHub.
2. Suba os arquivos do projeto.

