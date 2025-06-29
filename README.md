# 🔘 Teste de Presença de parafusos com ESP32

## 📌 Descrição  
Este projeto utiliza um **ESP32 WROOM-32** para testar a presença de dois dois parafusos a partir de um acionador.  

### 🔍 Funcionamento:  
1. O usuário pressiona o **botão de teste**.  
2. O sistema **aguarda alguns segundos** antes de iniciar a verificação.  
3. Um **LED acende** para indicar que o teste está em andamento.  
4. O sistema **verifica se há a presença dos dois parafusos**.  
5. O teste **só é concluído quando ambos os parafusos estiverem presentes**.  
6. No final do teste, o **LED apaga e um buzzer emite beeps breves caso encontrados parafusos**.
7. Ou um beep longo **Caso não encontre a presença dos parafusos ou um deles**  

---

## 💻 Desenvolvimento  

Para um melhor desenvolvimento, organização e qualidade do código, utilize o **Visual Studio Code** junto com a extensão **PlatformIO**.  

O **PlatformIO** é um ambiente de desenvolvimento avançado para sistemas embarcados que facilita a compilação, upload e monitoramento do ESP32.  

### 🔧 Requisitos  
- **[Visual Studio Code](https://code.visualstudio.com/)**
- **[PlatformIO IDE](https://platformio.org/install/ide?install=vscode)**  

Após instalar o **PlatformIO**, basta clonar o repositório e abrir no **VS Code**.

---

## 🛠️ Hardware Utilizado  
- **ESP32 WROOM-32**  
- **1 botão de pressão** (push buttons)  
- **2 Switch Probes**
- **1 LED indicador** *(opcional)*  
- **1 Buzzer** *(aviso sonoro)* 
- **1 Transistor**
- **Resistores pull-up internos ativados via `INPUT_PULLUP`**