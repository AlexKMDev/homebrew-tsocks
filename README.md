1. `brew tap Anakros/homebrew-tsocks`
2. `brew install --HEAD tsocks` 
3. `ssh -D 5555 server`
4. `vim /usr/local/etc/tsocks.conf`
5. `server = localhost`
6. `server_port = 5555`
7. `tsocks curl ifconfig.me`
