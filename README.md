# Torrents Tracker - Data Repository

![logo](doc/img/logo_small.png)
 
Public data for [torrents-tracker](https://github.com/arsscriptum/torrents-tracker).
This is an application to query different torrents indexers (i.e. PirateBay) to find differents media files. 

## Data Repository

Contains only the public data files fetch for versioning


## Looks and Feel

### How to Search

![1](doc/img/tracker01.png)

### Options

![2](doc/img/tracker02.png)


### About Page

![3](doc/img/tracker03.png)


### Results Page

![4](doc/img/tracker04.png)


### Download a Item

![5](doc/img/tracker05.png)



#### Database View

![db](doc/img/dbview.png)



## DEMO: Popular Title Search

**NOTE** Yeah! I fixed that pop up message when the magneet link is sent to *qbittorrentvpn* (when I press download)

![db](doc/img/popular.gif)



## DEMO: VPN Server Selection

I use **EXPRESS VPN** but with minor code changes, you can use your own VPN provider.

![db](doc/img/vpn.gif)


**NOTE** In  order to reduce the video lenght, I removed the time after I reset the VPN location. This launches a script that will stop the docker container, change the docker-compose.yml file and restart the compose stack. It's not hugely long, but it'smore than  what's  shown. Like 30 seconds...