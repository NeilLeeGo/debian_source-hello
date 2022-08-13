# Howto

## Extarct source 

```bash
dpkg-source -x hello_2.10-2ubuntu3.dsc 
 ```

## build debian package

``` bash
cd hello-2.10
debuild -us -uc
```
