# banana_Translator
https://astonishing-rugelach-2f20a4.netlify.app


WORKING
User enters the text to be translated in a <textarea> field.
When user clicks the "Translate" button, the event handler associated with button click is invoked.
The event handler then retrieves the text from the <textarea>, and creates a fetch() request to the URL: https://api.funtranslations.com/translate/minion.json?text=userText, where userText is the to be translated.
Once the translation is returned as a Response object, it is then converted to an object to retrieve the translation from the key contents.translated.
The translation is displayed using a readonly <textarea>.
