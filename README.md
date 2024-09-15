FR
Cette application Streamlit propose une interface de chatbot basée sur l'intelligence artificielle permettant aux utilisateurs d'interagir avec plusieurs types de documents : PDF 📄, fichiers Word 📃 et présentations PowerPoint 📊, en utilisant le langage naturel. Les principales fonctionnalités incluent :

Traitement des Documents : Téléchargez et traitez des fichiers PDF, des documents Word et des présentations PowerPoint.
Extraction de Texte : Extrait le texte de divers formats de documents pour une analyse approfondie.
IA Conversationnelle : Utilise un modèle de langage pour répondre aux questions sur le contenu des documents téléchargés.
Découpage de Texte : Divise les grands textes en morceaux gérables pour une interrogation efficace.
Intégration de Stockage Vectoriel : Convertit les morceaux de texte en embeddings et les stocke dans une base de données vectorielle pour une récupération rapide.
Détection de Langue : Détecte automatiquement la langue de la question de l'utilisateur pour fournir des réponses contextuellement pertinentes.
Interaction en Temps Réel : Fournit une interface de chat où les utilisateurs peuvent poser des questions et recevoir des réponses en temps réel, avec les temps de réponse affichés ⏱️.
L'application utilise LangChain pour le traitement de texte et le stockage vectoriel, PyPDF2 et python-docx pour la lecture des documents, et streamlit pour l'interface web. Elle est conçue pour faciliter la récupération efficace d'informations et améliorer l'interaction des utilisateurs avec le contenu basé sur des documents.

EN
This Streamlit application offers a conversational AI interface that allows users to interact with various document types: PDFs 📄, Word files 📃, and PowerPoint presentations 📊, using natural language. Key features include:

Document Processing: Upload and process PDFs, Word documents, and PowerPoint presentations.
Text Extraction: Extracts text from different document formats for in-depth analysis.
Conversational AI: Uses a language model to answer questions about the content of uploaded documents.
Text Chunking: Splits large texts into manageable chunks for efficient querying.
Vector Store Integration: Converts text chunks into embeddings and stores them in a vector database for quick retrieval.
Language Detection: Automatically detects the language of the user's question to provide contextually relevant responses.
Real-time Interaction: Provides a chat interface where users can ask questions and receive answers in real-time, with response times displayed ⏱️.
The app utilizes LangChain for text processing and vector storage, PyPDF2 and python-docx for document reading, and streamlit for the web interface. It is designed to facilitate efficient information retrieval and enhance user interaction with document-based content.
