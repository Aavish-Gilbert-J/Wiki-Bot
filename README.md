# Wiki-Bot
WIKI-BOT is a NLP powered chatbot that searches and gathers information from Wikipedia and 
responds to simple cognitive questions asked by the user. It provides information on the desired 
topic in five different Indian languages namely Hindi, Kannada, Tamil, Telugu & Malayalam. It 
also has text-to-speech capabilities for English and a title generator which helps you by 
suggesting relevant topics based on your interest. It can provide a link to the Wikipedia source 
and extract text from a page and print it in simple understandable format as well.

INSTRUCTIONS:
• Enter the topic you want to ask about.
• Click on the instructions button to view the bot commands.
• Say hi, hello to greet.
• You can ask simple questions (in the entry bar located at the bottom) based on the entered topic.
• You can use the title generator button to generate topics based on your past query.
• Use the various commands to access all the functionalities of the bot.
• Use %bye command to exit the program

COMMANDS:
  %title ➔ It is a title generator which suggests you with topics based on the topic title you’ve entered previously
  %page ➔ It extracts text from the Wikipedia page and prints it.
  %read ➔ It is a text to speech engine which reads out the summary to the user in English.
  %readn ➔It is similar to read but reads out ‘n’ sentences. Where n is an integer. i.e., read2 command reads two sentences.
  %hindi ➔It gives a brief summary of the entered topic in Hindi
  %kannada ➔It gives a brief summary of the entered topic in Kannada
  %tamil ➔It gives a brief summary of the entered topic in Tamil
  %telugu ➔It gives a brief summary of the entered topic in Telugu
  %malayalam ➔It gives a brief summary of the entered topic in Malayalam
  %link ➔ It generates a link to the Wikipedia page of the topic.
  thanks ➔ To move to a new topic
  bye ➔To exit
  
  The chatbot uses the following modules:
• Wikipedia module – to access the Wikipedia Api
• NLTK module – to implement NLP algorithms
• Tkinter module – to implement GUI
• pyttsx3 module – it carries out the text-to-speech operation
• random module 
• string module
• ctypes – to change the GUI title bar color
• warnings – to filter warnings
