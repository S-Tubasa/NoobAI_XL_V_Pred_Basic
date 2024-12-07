# NoobAI XL V Pred 0.65 Basic

## LandScape(3:2 [1824 x 1248])
![image](./landscape/workflow.png)

## Portait(2:3 [1248 x 1824])
![image](./portait/workflow.png)

## Setup
- Python 3.12.3
```bash
cd ComfyUI
pip install -r requirements.txt
pip install websocket-client

cd models/checkpoints
wget https://civitai.com/models/833294?token=xxxxxxxx --content-disposition

cd models/vea
wget https://huggingface.co/madebyollin/sdxl-vae-fp16-fix/resolve/main/sdxl_vae.safetensors
```

## Example
### LandScape
```bash
time python main.py --mode 1 --prompt "cute angel" --save_path "./test.png"
```
```

```

### Portait
```bash
time python main.py --mode 2 --prompt "cute angel" --save_path "./test.png"
```
```

```


