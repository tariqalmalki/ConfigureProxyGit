# ConfigureProxyGit

1- download git fom this link :
https://git-scm.com/downloads

2- then type Next command

git config --global http.proxy http://UserName@ProxyIP:ProxyPort

git config --global https.proxy https://UserName@ProxyIP:ProxyPort


3- Checking Active proxy 
git config --global --list
git config --local --list

4- Removing Active Proxy
git config --global --unset https.proxy
git config --global --unset http.proxy
