# go-fiber-anime-downloader
learning fiber library for go :)  
App that lets you search and download anime from 9anime.  
Can be useful when your device can't use Adblock like Samsung TVs.  

# info
looks like 9anime IP blocks repeated requests after kissanime got banned.  
trying to find a workaround

# IMPORTANT
9anime changes their url alot lately to stuff like www10.9anime etc.  
Make sure to set the env variable NINE_ANIME_ROOT_URL to the current url if the app stops working.

# can not download your anime?
the app scrapes 9anime for all episodes that are uploaded on Streamtape.  
So if your anime is not on streamtape it can't be downloaded for now :/  

# usage 
git clone https://github.com/kantimam/go-fiber-anime-downloader.git  
make sure go version is above 1.15  
go build  
run the executable (most likely "goserver")

# try it out on
https://anime.baizuo.online/
