# soapi-cookbook


- [ ] Authentification WMS: curl-Befehle, anderer Zugang, GetCapabilities (Achtung api-auth vs. das andere auth)
- [ ] WMS-Filtering etc.
- [ ] Naming-Logik

- [ ] WFS Auth?

```
curl -v --user foo:bar -X GET "https://geo.so.ch/api-auth/wms?SERVICE=WMS&REQUEST=GetCapabilities&VERSION=1.3.0"
```

## Github pages

https://edigonzales.github.io/soapi-cookbook/master.html

## Setup Github pages

```
cd /path/to/repo-name
git symbolic-ref HEAD refs/heads/gh-pages
rm .git/index
git clean -fdx
echo "My GitHub Page" > index.html
git add .
git commit -a -m "First pages commit"
git push origin gh-pages
```

