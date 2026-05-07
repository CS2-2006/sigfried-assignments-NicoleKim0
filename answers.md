In your own words, what does signal-finder do?
A signal finder goes to a website like Reddit, takes the raw data, then curates and renders it for that person's feed to match their interests.

What does the project mean when it says "bad curation is usually a context problem, not an AI problem"?
Bad curation is a result of a lack of context provided to ensure the outcome was properly tailored to someone's interests rather than faulty AI curation.

What is the purpose of file A? What kind of information does it contain?
This file primarily focuses on what information the curator will pull from the data. It offers source, author, title, subreddit, etc. for each post, filters out over 18 posts, and summarizes the posts for the reader.

What is the purpose of file B? Why is it mostly empty?
The purpose of file B is for the reader/client to customize their curation - it's mostly empty because it's room meant for the reader to input their interests, guidelines, priorities, and preferred output style. 

What is the purpose of file C? How is it different from A and B?
The purpose of file C is to detail how exactly the curated page will be made. From steps like rating each post to deleting anything too similar, and even a reflection, file C, unlike A and B, is less about what the reader wants but more how the person will get to that point.

If you wanted the AI to stop showing you sports content, which file would you edit and what would you change?
I would change file B and alter section 2: the I do not want section. I would write that I do not want to see sports posts from reddit and that would lead to a less sports centered curation. 

What do you think fetch_reddit.py does based on its name and any comments you can find?
I think fetch_reddit.py is for the initial pulling of the data from reddit and it seems to filter out what to download and what not to download. 

What is requirements.txt for? (Hint: try asking Copilot Chat if you are not sure)
Requirements.txt is for specifying python dependencies for the project. The trafilatura in the file is a library used for extracting and storing data from web pages. 

Imagine you are building your own version of this project, but instead of Reddit, you are curating content from a different source (YouTube, TikTok, news sites, sports scores, etc.). What source would you choose and why?
I would use Instagram because I find that I spend a lot of time on there without very specialized videos, so just seeing what I'm interested in I think would be better for me. 
How could the A/B/C framework apply to your version? What would go in each file?
I think B would stay the same in terms of preferences, but A would probably change to showing the original account or top three comments. C would also change since there are videos and posts that are mostly visual. I would likely change it to pulling the thumbnail of each video. 