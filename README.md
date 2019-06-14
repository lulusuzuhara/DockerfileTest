# dockerfiletest

```bash
docker build . -t hogeimage
docker run -it --name hogecontainer -v $PWD:/hogedir hogeimage "/bin/bash"
cd hogedir
cargo run # Hello, world!
```