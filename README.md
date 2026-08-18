fih
if bash idk figure it out
```
set D /tmp/claude-1000/-home-posei/874df2f9-e768-4ce9-86b7-af88f80961e9/scratchpad
sudo install -m755 $D/hosts-focus /usr/local/bin/hosts-focus
sudo install -m644 $D/hosts-focus.{service,timer} /etc/systemd/system/
sudo systemctl enable --now hosts-focus.timer
```
