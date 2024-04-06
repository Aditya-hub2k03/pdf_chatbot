PDF Chat Bot 

This chat bot is desgined for interacting with the documents uploaded and answering any questions related to the documents.

This bot is designed using streamlit ('refer: https://streamlit.io/')

The llm used in this app is Gemini, formerly known as Bard, which is a generative artificial intelligence chatbot developed by Google.

Here a seperate file called as ".env" has to be created in the parent folder with the contents in it as 

"GOOGLE_API_KEY='Google Gemini API key'

HUGGINGFACEHUB_API_TOKEN='Hugging Face API key' "

Alternatively, A huggingface model is also mentioned in the 'app.py' code where it comes to use after removing the comment label in the line of llm and embeddings

The pip library for the hugging face model can also be used after removing the comment label from the requirements file and installing the required libraries.

Installation:

1. Create a virtual environment by installing python virtual environment ('pip3 install virtualenv')
	
 	1.a. Execute the command 'virtualenv venv' to create a virtual environment venv in the Parent folder.
	
	1.b. In Windows actiavte the venv by 'venv/Scripts/activate' and in Linux and Mac activate the venv by 'source venv/bin/activate'.
   
3. Install the requirements by 'pip3 install -r requirements.txt' and in rare cases of Linux distros 'pip3 install -r requirements.txt --break-system-packages'.
4. Execute the command of streamlit 'streamlit run app.py' to run the program.




#reference git "https://github.com/yesbhautik/Talk-with-PDF.git".

'https://pdfchatbot-gitaditya.streamlit.app/' - A preview of the designed website deployed on streamlit without any environment variables including the API.
