# Projects Name

## [WIP] About

Docker with a Mac is painfully slow

## Requirements
Install docker-sync
```
gem install docker-sync --no-rdoc --no-ri
docker pull eugenmayer/unison:2.51.2.1
```
See "More information::Inspirated by" for further information

## [WIP] How to use
```
git clone https://github.com/OXIDFabian/oxid-php.git
git clone https://github.com/michaelkeiluweit/OXID_Docker_Stackv2_4Mac.git docker-sync
cp docker-sync/docker-compose.yml docker-sync/docker-compose-dev.yml docker-sync/docker-sync.yaml ./

docker-sync start
docker-compose -f docker-compose.yml -f docker-compose-dev.yml up -d

```


## Troubleshooting

### Error response from daemon: network 8bf[...]c77 not found
`docker system prune`


## More information

Inspirated by: https://dienbui.medium.com/speed-up-docker-for-mac-with-docker-sync-480c65d4013a
