# Wiki-Bot
WIKI-BOT is a NLP powered chatbot that searches and gathers information from Wikipedia and 
responds to simple cognitive questions asked by the user. It provides information on the desired 
topic in five different Indian languages namely Hindi, Kannada, Tamil, Telugu & Malayalam. It 
also has text-to-speech capabilities for English and a title generator which helps you by 
suggesting relevant topics based on your interest. It can provide a link to the Wikipedia source 
and extract text from a page and print it in simple understandable format as well.

INSTRUCTIONS:<br>
• Enter the topic you want to ask about.<br>
• Click on the instructions button to view the bot commands.<br>
• Say hi, hello to greet.<br>
• You can ask simple questions (in the entry bar located at the bottom) based on the entered topic.<br>
• You can use the title generator button to generate topics based on your past query.<br>
• Use the various commands to access all the functionalities of the bot.<br>
• Use %bye command to exit the program<br>

COMMANDS:<br>
  %title ➔ It is a title generator which suggests you with topics based on the topic title you’ve entered previously<br>
  %page ➔ It extracts text from the Wikipedia page and prints it.<br>
  %read ➔ It is a text to speech engine which reads out the summary to the user in English.<br>
  %readn ➔It is similar to read but reads out ‘n’ sentences. Where n is an integer. i.e., read2 command reads two sentences.<br>
  %hindi ➔It gives a brief summary of the entered topic in Hindi<br>
  %kannada ➔It gives a brief summary of the entered topic in Kannada<br>
  %tamil ➔It gives a brief summary of the entered topic in Tamil<br>
  %telugu ➔It gives a brief summary of the entered topic in Telugu<br>
  %malayalam ➔It gives a brief summary of the entered topic in Malayalam<br>
  %link ➔ It generates a link to the Wikipedia page of the topic.<br>
  thanks ➔ To move to a new topic<br>
  bye ➔To exit<br>
  
  The chatbot uses the following modules:<br>
• Wikipedia module – to access the Wikipedia Api<br>
• NLTK module – to implement NLP algorithms<br>
• Tkinter module – to implement GUI<br>
• pyttsx3 module – it carries out the text-to-speech operation<br>
• random module <br>
• string module<br>
• ctypes – to change the GUI title bar color<br>
• warnings – to filter warnings<br>
