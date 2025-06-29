# comfyui-man-3d
comfy-ui-w-manager-3d


On arch, use 
```
downgrade cuda -> 2.12
downgrade gcc13 gcc13-libs
```

* Use Python 3.11 (diso requires 3.11)
* run `./install-comfyui-venv-linux.sh`
* edit run_gpu.sh to include --listen
* 
* Run run_gpu.sh once
* Navigate to localhost:8188
* click manager - custom nodes manager - search 3d pack
* click install

* diso will probably fail.
* Ctrl-c server
*  vim  ComfyUI/custom_nodes/ComfyUI-3D-Pack/requirements.txt
* comment out the diso git link and add regular diso
* 
* pip install xformers==0.0.30
* 
* downgrade glibc to 2.40
* pip install diso
* 

* source ComfyUi/venv/bin/activate

* python install.py (from 3d directory)
* pip install pyhocon torchtyping jaxtyping iopath  easydict plotly
* 
