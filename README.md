# Backup-manager

## Usage

```
$ docker run -d \
    -v /etc/backup-manager.conf:/etc/backup-manager.conf:ro \
    -v $PWD:/backups:ro \
    hellslicer/backup-manager
```