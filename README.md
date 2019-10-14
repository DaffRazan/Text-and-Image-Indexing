# ProjectRDM-Indexing

## Image-Search-Indexing and Text-Indexing

1. **Text-Indexing** Using Swish-e
    - Requirements :
        a) Install Swish-e (Ubuntu's Package) 
            ![Swish-e Install](https://github.com/DaffRazan/ProjectRDM-Indexing/blob/master/pics/text-indexing/swish-e-install.png)
        b) Steps how to run **Text-Indexing**
            - Make one folder named **swish** , in folder **swish** , create one folder named **corpus**
            that contains 10 txt's files, then fill each of the files with the description.
            - Make text-indexing configuration using syntax  ```swish-e -c main.conf```
            ![text configuration](https://github.com/DaffRazan/ProjectRDM-Indexing/blob/master/pics/text-indexing/conf.jpg)
            - Run text-indexing using syntax ```swish-e -w {word}```
            ![search index](search.index.jpg) 
            - Image-Search-Indexing done.


