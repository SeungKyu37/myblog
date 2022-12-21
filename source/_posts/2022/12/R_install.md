---
title: R 설치하기
date: 2022/12/20 12:04:25 
categories:
- R
tags:
- R
- RStudio
- Rtools
- 4.1.3
---

# R

- R : [https://www.r-project.org/](https://www.r-project.org/)
    
    4.1.3버전으로 다운로드
    

![Untitled](/images/2022/12/R_install/Untitled.png)

- Rstudio : [https://posit.co/download/rstudio-desktop/](https://posit.co/download/rstudio-desktop/)

![Untitled](/images/2022/12/R_install/Untitled%201.png)

- Rtools : [https://cran.r-project.org/bin/windows/Rtools/rtools40.html](https://cran.r-project.org/bin/windows/Rtools/rtools40.html)

![Untitled](/images/2022/12/R_install/Untitled%202.png)

차례대로 설치 후 RStudio 실행

 “+” 버튼 클릭 후  R Script 클릭

![Untitled](/images/2022/12/R_install/Untitled%203.png)

- `write('PATH="${RTOOLS40_HOME}\\usr\\bin;${PATH}"', file = "~/.Renviron", append = TRUE)` 입력 후 실행

![Untitled](/images/2022/12/R_install/Untitled%204.png)

![Untitled](/images/2022/12/R_install/Untitled%205.png)

- console에 `install.packages("jsonlite", type = "source")` 입력 후 실행

![Untitled](/images/2022/12/R_install/Untitled%206.png)

![Untitled](/images/2022/12/R_install/Untitled%207.png)

- install.packages(”tidymodels”) 입력 후 실행

![Untitled](/images/2022/12/R_install/Untitled%208.png)

- Tools > global option > code
    
    ![Untitled](/images/2022/12/R_install/Untitled%209.png)
    
    - Soft-wrap R source file 체크
        
        ![Untitled](/images/2022/12/R_install/Untitled%2010.png)
        
        - saving 에서 UTF-8로 바꾸기
            
            ![Untitled](/images/2022/12/R_install/Untitled%2011.png)