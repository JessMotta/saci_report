# Report template for robotics projects
This a short introduction about the report.

The report consists of 7 chapters.
        
1. Introduction
2. System concept
3. System development
4. Results and analysis
5. System reliability
6. Knowledge management
7. Conclusion


## Installing *TexLive*
To use this repo it is necessary to install *TexLive*.
    
```sh

    sudo add-apt-repository ppa:jonathonf/texlive
        
    sudo apt update
        
    sudo apt install texlive-full
       
    tlmgr install abntex2
        
    tlmgr update abntex2

```


### All cleaning *TexLive* (if necessary)

```sh

    sudo apt-get install ppa-purge

    sudo ppa-purge ppa:jonathonf/texlive

    sudo apt-get autoremove --purge tex-common texlive-base texlive-binaries texlive-common texlive-doc-base texlive-latex-base texlive-latex-base-doc

    sudo apt-get autoclean

```


