# project-q

                                 A daily motivational quote for everybody (or almost)
                                    
                                  
Project Q is a frontend development bootcamp project = a motivational quote generator with a translator's touch.

With 28 languages to choose from, Project Q can provide a motivational quote to about 6 billion speakers, including Chinese, Spanish, Czech, Brazillian (PT + BR), English (US + UK), French, Russian, Turkish, German, etc.
                                
                                
                                 How to use Project Q
1.- On load, you'll be given a random motivational quote and its author. To get a new motivational quote, tap Get new Quote.

2.- If your language was not recognized automatically, select it in the dropdown menu available in the middle of the page.

3.- Find your translated quote in the bottom area.

4.- The background image will change on reload so, e.g., when you wake up and come get your new quote to start an awesome day, you'll get an new and awesome background image.




                                  How Project Q works:
1. Fetching a quote from Quote Garden API.
2. Sending the quote to Deepl's translation API.
3. Presenting the translated quote.



                                   FAQs
                                      

Q: Where is Project Q getting the quotes from?
A: https://pprathameshmore.github.io/QuoteGarden/

Q: Why my language is not recognized automatically?
A: We aim offer a fluid motivational quote experience by recognizing your device language on load, however, if your device is using a locale that is not supported by the NMT engine, then Project Q is unable to recognize it automatically, and thus the quote can't be translated on load. 
Example: Project Q will recognize EUES on your device and translate the quote into Spanish; however, Project Q can't recognize MXES or LATAMES. If you have MXES or LATAMES on your device and want to get your quote in Spanish, select Spanish in the dropdown menu.

Q: I am using a compatible language, like EUES, but my language is not recognized automatically, why?
A: Some browsers, like Safari, have special requirements and restrictions in regard to accessing users’ data, like their device language.  A Chromium-based browser, like Chrome or Brave, will recognize a compatible language, like EUES or Chinese (simplified).

Q: I want to access Project Q every morning from my mobile phone. Do you have an app?
A: We don't have a downloadable app, but you can add Project Q to your home screen just like an app. In Safari, open the share sheet (tap the + symbol in bottom bar) and select Add to home. You'll now be able to access Project Q from your home page, just like an app.

If I add Project Q to my home screen, can I get quotes without Internet?
No. Retreiving and translating quotes require an Internet connection.
