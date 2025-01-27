# Managing Conversation History with ChatGPT Model

Para probar este proyecto, estos son los pasos a seguir:

1. Con una terminal de `Git Bash`, **clona** el repositorio:
   
   ```bash
   git clone https://github.com/alejandrorod-tajamar/ManagingConversationHistoryWithGPTModel.git
   ```
   
2. Abre una terminal de `Command Prompt`.
   
3. Navega al **directorio del proyecto**:
   
   ```cmd
   cd ManagingConversationHistoryWithGPTModel
   ```

4. Crea un **entorno virtual**:

   ```cmd
   python -m venv nombre_del_entorno
   ```

5. Activa el entorno virtual:

   ```cmd
   .\nombre_del_entorno\Scripts\activate
   ```

7. Crea un archivo `.env` en el directorio raíz del proyecto con el siguiente contenido, reemplazando con tu Endpoint y tu clave de API:

   ```.env
   AZURE_OPENAI_API_KEY=tu_clave_api
   AZURE_OPENAI_ENDPOINT=tu_endpoint
   ```

8. Sigue las instrucciones en [chatGPT_managing_conversation.ipynb](chatGPT_managing_conversation.ipynb).
