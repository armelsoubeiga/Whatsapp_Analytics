# Whatsapp_Analytics

The script reads an exported whatsapp chat and then extracts the data. You may need to install some packages before run it


### Requirements
- Python 2.7+ or Python 3
```python
pip install pandas emoji seaborn matplotlib numpy wordcloud 
```
### Usage
```
$ git clone https://github.com/armelsoubeiga/Whatsapp_Analytics.git

$ cd Whatsapp_Analytics
$ python whatsapp_analyzer.py
```

### Notes
- This script use regex to extract the data.
- Currently support below chat pattern:
 ```python
    "14/10/18, 11:16 - Contact Name: this is a message"
    "2/30/18, 2:07 AM - Contact Name:  Test??"
    "[30/12/18 4.59.25 PM] Nama User: ??test"
    "[06/07/17 13.23.30] ?+62 123-456-78910?: image omitted"
  ```
- Some date format may not supported
- Tested in python 2.7+ on MacOS
- When using virtualenv there is error backend stuff
  I don't know how to fix it yet. Help please :)

### Getting chat source
#### Android:
- Open a chat/group chat
- Tap on trhee dots oh the top right
- Tap "More"
- Choose "Export chat"
- Choose "Without Media"

#### iOS
- Open a chat/group chat
- Tap on contact name/group name on the top to see the details
- Scroll down to find "Export Chat" menu
- Choose "Without Media"


## Jupyter Notebook
Description included inside
#### Visualization Preview
 - Top 20 most active member
   ![](https://i.imgur.com/dqC83Gb.png)
 - Peaktime
   ![](https://i.imgur.com/C4D2cjw.png)
 - Attachment Share
   ![](https://i.imgur.com/mEWKSRj.png)
 - Top Mentioned Website
   ![](https://i.imgur.com/9Y8hTwE.png)
 - Wordcloud


#### Raw
 
  
