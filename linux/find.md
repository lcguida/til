# Search files between to dates

Ex: All files between 2017-11-01 and 2017-12-01

```bash
find . -newermt "2017-11-01 00:00:00" -not -newermt "2017-12-01 00:00:00"
```
