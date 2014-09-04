1. brew tap Anakros/homebrew-tsocks
2. brew install --HEAD tsocks
3. vim /usr/local/etc/tsocks.conf
4. ssh -D 5555 server
5. server = localhost
6. server_port = 5555
7. tsocks something
