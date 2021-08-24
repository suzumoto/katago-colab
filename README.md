# colab-katago-gd

This program has been modified from the original colab-katago to store SSH information on Google Drive.

See how to use:   

**English Version**  
https://colab.research.google.com/github/mildinvestor/katago-colab/blob/master/colab_katago_gd_en.ipynb

# Build
```
GOOS=darwin GOARCH=amd64 go build -o ./bin/colab-katago-for-mac 
GOOS=linux GOARCH=amd64 go build -o ./bin/colab-katago-for-linux
GOOS=windows GOARCH=amd64 go build -o ./bin/colab-katago-for-windows
```

See how to build:

This notebook contains examples of how to build colab-katago-gd and KataGo, and how to create KataGo's tuning files.
https://colab.research.google.com/github/mildinvestor/katago-colab/blob/master/build_colab_katago_gd.ipynb
