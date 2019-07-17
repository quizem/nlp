# Named Entity Recognition
Usually, a piece of text document is full of references to people, places, organizations and other entities (NOTE that entities can include such things as currency, numbers etc in addition to the ones we include in our little demo here). We want to be able to automatically retrieve this information. Perhaps we can then ask why some entites are referenced more times than others.  

## In this demo,
- we start with a simple text preprocesing
- generate a spacy doc with Named Entity recognition engine on
- extract the entities using the extract_entities function in textacy
- create a pandas dataframe and do simple frequency counts
- finish with a nice visualization of the result

<strong>NOTE</strong>: In practice you'll do more than these few simple steps.
