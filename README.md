A few websites for offline use.

## golang.org

```
wget --limit-rate=200k --no-clobber --convert-links --random-wait -r -p -E -e robots=off -U mozilla http://golang.org/
```

# gobyexample.com
                                                                                                                     
```
wget --limit-rate=200k --no-clobber --convert-links --random-wait -r -p -E -e robots=off -U mozilla https://gobyexample.com/
```

# godoc.org

Kubernetes

```
wget --recursive --no-clobber --page-requisites --html-extension --convert-links --restrict-file-names=windows --domains godoc.org --no-parent http://godoc.org/github.com/GoogleCloudPlatform/kubernetes
```
