# Reddit-to-Instagram
Reddit-to-Instagram allows you to get hot/top/new/rising posts from various subreddits and repost them to your Instagram account automataically. **Don't you ever use your main Instagram account with this bot. What this bot does is against the Instagram's rules and your account may get banned. So, use another account.**

## Usage
[Video tutorial](https://youtu.be/5XbKDyxeN6Y)

- Clone or download this repo.
- Create a Reddit app from [here](https://ssl.reddit.com/prefs/apps/).
- Install requirements by typing ``pip install -r requirements.txt``
- Edit the config file (instructions below).
- Run ``python app.py``

## Editing the Config File
``client_id:`` Your Reddit App's client id.  
``client_secret:`` Your Reddit App's client secret.  
``user_agent:`` Set to whatever you want, but don't leave empty.  

``post_type:`` If typed "hot", it will search for hot Reddit posts. (You can use "hot", "top", "rising", "new".)    
``subreddits:`` Subreddits to be monitored.    
  
``comment_submission:`` If true, the bot comments to the post in Reddit before reposting it. Some subreddit mods may not be okay with reposting their content.  
``submission_comment:`` Comment.  
&mdash; ``{instagram}:`` Gets formatted to your Instagram username.  
&mdash; ``{instagram_post}:`` Gets formatted to the Instagram post's url.  
  
``instagram_username:`` Your Instagram username.   
``instagram_password:`` Your Instagram account.  
``post_caption:`` Instagram post's caption.  
&mdash; ``{title}:`` gets formatted to Reddit post's title.  
&mdash; ``{author}:`` gets formatted to Reddit post's author.  
&mdash; ``{subreddit}:`` gets formatted to Reddit post's subreddit.  
&mdash; ``{score}:`` gets formatted to Reddit post's score.

``wait_before_posting:`` Wait time before reposting a Reddit post to Instagram.