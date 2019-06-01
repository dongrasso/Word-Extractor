# Word-Extractor
Word Extractor is a software made with C# using a Visual Studio WPF. It can extract the frequent words from an italian or english online 
article. 
Main funtions:
• Show the most frequent words within the text.
• Propose the original web page showing the keywords in bold.
• Display the frequent words through a “Word Cloud”.
• Save the analyzed text and the result in a database.


HOW IT WORKS?

Main Window:
-The main window contains a list of the compatible web sites. If you click it, it will open a new Chrome tab showing the homepage of the site.
-The text box on the top allows to paste the URL of a compatible web site article.
-Once you paste the URL, you have to press the button "Mostra articolo". After a few seconds, it will show the main content of the article.
-The button "Mostra occorrenze" opens a new window with all words and their occurrences within the article.
-Through the button "Mostra HTML" a new window will be loaded that will contain the entire page we choose with the most repeated occurrences 
 in bold.
-"Word Cloud" will show the words with several dimentions based on the number of occurrences.
-"Get db" takes the URL and the HTML code form the db inside which is saved, and it shows the URL.

Each time the content of an article is displayed, the link, the text, the keywords and the html are saved in our SQL Server database.


