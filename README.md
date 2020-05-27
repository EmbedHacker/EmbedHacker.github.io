## soft deb Package Repository for i386

# For i386
(1)、Add repository
```
echo "deb https://EmbedHacker.github.io/ trusty main" | sudo tee -a /etc/apt/sources.list
```
(2)、Add public GPG key
```
curl https://EmbedHacker.github.io/keyfile | sudo apt-key add -
```
