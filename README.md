# Tweet-Cleaning-using-Python-NLTK-
When we scrape twitter data, it is available in raw format. Hence, it is essential to clean all those tweets using text analysis libraries in python. 

Data Cleaning/ Data Preprocessing

1. Step 1: HTML decoding 
Data obtained from web usually contains a lot of html entities like &lt; &gt; &amp; which gets embedded in the original data. It is thus necessary to get rid of these entities. One approach is to directly remove them using specific regular expressions. Here we took help of BeautifulSoup library. 

2. Step 2: Removal of @mention 
When people tagged someone in tweets is just for reference. So, that tagged text is not actually causing any value for our analysis purpose. Hence, it is essential for us to get rid of those tagged text. We used regex package available in python to remove those tagged text present in tweet. 

3. Step 3: Removal of URL Links
Like tags, these URL links are irrelevant part of tweets. Hence, we removed all URL links mentioned in tweets. Problem in removing URL links is that we can’t easily remove them from our text. There are some links starts with http: and some just www. So, we needed complex regex equation for this operation.

4. Step 4: Removal of UTF-8 BOM (Byte Order Mark)
Text data may be subject to different forms of decoding like “Latin”, “UTF8” etc. Therefore, for better analysis, it is necessary to keep the complete data in standard encoding format. UTF-8 encoding is widely accepted and is recommended to use.
The outputs after performing step 1 to step 3 is given in below screenshots. These screenshots include part of python code along with before and after looks.   


All above oprations are performed in python. 

I have attached python files which will help you with all text analysis syntaxes. 

Any suggestion would be appreciated.

Ankita
