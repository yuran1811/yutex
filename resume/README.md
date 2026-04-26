- Build using Docker

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex dev-resume/yuran1811-dev.tex
```
