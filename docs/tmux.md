# Tmux documentation 

## Installation
* 1.how to install tmux in your terminal 
```
sudo apt install tmux
```
* 2.how to start a tmux session 
```
tmux
```

![type:video-tag](./videos.md/1a.mp4)

## Opening and toggling panes 
* 1.how to open different vertical panes 
``` 
ctrl+b % 
```
* 2.how to open different horizontal panes 
```
ctrl+b "
```
* 3.how to toggle btw different panes
```
ctrl+b 'arrow keys'
```

![type:video-tag](./videos.md/2.mp4)


## Opening and toggling windows
* 1.how to open different windows  
```
ctrl+b c
```
* 2.how to toggle btw different windows 
```
ctrl+b 'windows numeric value, ex. 0,1,2'
```
* 3.how to rename a window name => get to the desired window >>  `ctrl+b ,` >> now enter the name and press enter

![type:video-tag](./videos.md/3.mp4)


## Session controls
* 1.how to detach from a session
```
ctrl+b d
```
* 2.how to attach a session  
```
tmux attach -t 'new name'
```
* 3.how to see different tmux session  
```
tmux ls
```
* 4.how to rename the session 
```
tmux rename-session -t 'old name' 'new name'
```
* 5.how to rename a seesion at the time of starting it 
```
tmux new -s 'new name'
```
* 6.how to remove/kill a session 
```
tmux kill-session -t 'session name'
```

![type:video-tag](./videos.md/first.mp4)
