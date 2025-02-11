# 2025-02-10-dockerfile
Learn about dockerfiles in dsci310 class - repeating work from 2025-02-04 for better understanding.

Hello from inside the container.
The command I ran was:

```bash
docker run --rm -it -e PASSWORD="pissa" -p 8787:8787 -v /$(pwd):/home/rstudio/work rocker/tidyverse:4.4.2
```
