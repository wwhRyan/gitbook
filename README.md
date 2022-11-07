## Build Static Website

```bash
docker run -v `pwd`/<your book>:/srv/gitbook fellah/gitbook gitbook build . 
```

# GitBook Image

Run container:

```bash
docker run -p 4000:4000 -v `pwd`/<your book>:/srv/gitbook fellah/gitbook
```

`4000` – GitBook default service port.

`35729` – Live reload server port.

`/srv/gitbook` – Default working directory for GitBook container.

## Links

[GitHub: GitBook](https://github.com/GitbookIO/gitbook)

[GitBook Toolchain Documentation](http://toolchain.gitbook.com)
