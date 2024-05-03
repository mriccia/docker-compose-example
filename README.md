To test from CodeCatalyst Dev Environment, run the flollowing

```
# clone the repo 
# cd into repo folder
sudo sysctl -w net.bridge.bridge-nf-call-iptables=0
docker compose up
```