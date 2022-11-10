# htaccess-cheatsheet

```
RewriteEngine on
#if the file does not have one of theses extensions
RewriteCond %{REQUEST_URI} !\.(png|jpg|jpeg|gif|PNG|JPG|JPEG|GIF|Png|Jpg|Jpeg|Gif|pdf|PDF|Pdf)$
#then it should be marked as forbidden.
RewriteRule .*$ - [F]
```

Ref:

https://gist.github.com/roachhd/0d5c31aff7bcc720eb4b

https://htaccesscheatsheet.com/
