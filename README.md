## 1. First install pixi globally: 

```bash 
curl -fsSL https://pixi.sh/install.sh | sh
source ~/.bashrc 

```


## 2. clone pixi_ws 

```bash
 cd ~/ardu_ws && git clone "https://github.com/irocu26/pixi_ws.git"  

```

## 3. Pixi commands 

```bash

cd ~/ardu_ws/pixi_ws
pixi shell
pixi bootstrap

```

## 4. Check Installation 

```bash
source ~/ardu_ws/pixi_ws/devel/setup.bash
rosrun kalibr kalibr_calibrate_cameras --help
```