```
git clone https://github.com/bam6o0/planetary-scale.git
docker run --rm -it --net=host -v $(pwd):/src klakegg/hugo
hugo new what-is-devenv.md
chown $USER:&USER what-is-devenv.md
hugo server -D -p 8080
```