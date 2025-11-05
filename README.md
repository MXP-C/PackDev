# 🧩 PackDev

Um **Modpack Builder** avançado para **Minecraft**, feito em Python com **Tkinter** e integração direta com a **API do Modrinth**.  
Crie, gerencie e exporte seus modpacks com facilidade — incluindo **busca inteligente, recomendações automáticas e salvamento de projetos em JSON**.

---

## 🚀 Funcionalidades

- 🔍 **Busca de mods** no Modrinth diretamente pelo app  
- ⚙️ **Adição e remoção rápida** de mods na interface  
- 💾 **Salvar e carregar projetos** em `.json`  
- 🤖 **Recomendações automáticas** de mods semelhantes  
- 🧠 **Filtro por loader, versão e autor**  
- 🧾 **Logs em tempo real** das ações  
- 📦 **Download e exportação de modpacks completos**

---

## 🧠 Como funciona

O ModForge usa a [API do Modrinth](https://docs.modrinth.com/api-spec/) para buscar informações dos mods.  
Ele salva o projeto localmente em `.json`, incluindo todos os mods, versões e configurações, permitindo que você continue depois exatamente de onde parou.

---

## 🧰 Requisitos

- **Python 3.10+**
- **Bibliotecas necessárias:**
  ```bash
  pip install requests pillow
