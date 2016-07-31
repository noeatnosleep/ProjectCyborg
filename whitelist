import praw

r = praw.Reddit('useragent')
r.login("username","password")

Wiki_Page = r.get_wiki_page("subreddit","Name_of_Page")
domains = Wiki_Page.content_md.split('\r\n\r\n') 
unmoderated = s.get_unmoderated()

for submission in unmoderated:
    if submission.domain in domains:
        submission.approve() 
