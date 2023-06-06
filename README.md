# Cottage HomeLab


## NOTES

Docker Command to map NFS share
```cmd
docker volume create --driver local --opt type=nfs --opt o=addr=[ip-address],rw --opt device=:[path-to-directory] [volume-name]
```
