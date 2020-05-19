
1. This is a .ipynb coding file for entire Quesiton 4. Open with Jupyter Notebook.
2. To read files from the code, you need to put the 'summary quality' file folder and 'GoogleNews-vectors-negative300.bin' file in the same folder with this code file.
3. When running the function with spacy token(nlp), you may need to rerun 'nlp = spacy.load("en_core_web_sm")' and 'sentencizer = nlp.create_pipe("sentencizer")
nlp.add_pipe(sentencizer)' codelines.