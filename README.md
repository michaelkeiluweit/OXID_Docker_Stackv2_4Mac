# Projects Name

## [WIP] About

Docker with a Mac is painfully slow

## [WIP] How to use
```
git clone oxidfabiandockerstackv2
git clone this docker-sync
cp docker-sync/docker-compose.yml docker-sync/docker-compose-dev.yml docker-sync/docker-sync.yaml ./

docker-sync start
docker-compose -f docker-compose.yml -f docker-compose-dev.yml up -d

```


## Troubleshooting

### Error response from daemon: network 8bf[...]c77 not found
`docker system prune`


## More Information

https://dienbui.medium.com/speed-up-docker-for-mac-with-docker-sync-480c65d4013a
