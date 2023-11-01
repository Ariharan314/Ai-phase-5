IN[]: 

Import re 

Def clean_text(text): 

 Text = re.sub(r’http\S+’, ‘’, text) # Remove URLs 

 Text = re.sub(r’[^A-Za-z0-9]+’, ‘ ‘, text) # Remove special characters 

 Text = text.lower() # Convert to lowercase 

 Return text 

Clean the dataset.., 

Cleaned_text = clean_text(text)

o/p[]:
