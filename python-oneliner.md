> Kroki provides an HTTP API to convert plain text diagrams to images.
> Kroki handles both GET and POST requests. When using GET requests,
> your diagram must be encoded in the URL using a deflate + base64 algorithm.
```sh
cat hello.dot | python -c "import sys; import base64; import zlib; print(base64.urlsafe_b64encode(zlib.compress(sys.stdin.read().encode('utf-8'), 9)).decode('ascii'))"
```