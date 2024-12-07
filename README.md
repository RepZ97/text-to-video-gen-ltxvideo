<div align="center">

# LTX-Video

Official links below.

[Website](https://www.lightricks.com/ltxv) |
[Github](https://github.com/Lightricks/LTX-Video) |
[Model](https://huggingface.co/Lightricks/LTX-Video) |
[Demo](https://fal.ai/models/fal-ai/ltx-video) |
[Paper (Soon)](https://github.com/Lightricks/LTX-Video)

</div>


# Windows installation


Step 1: Navigate inside the cloned repository
	
	cd LTXVideo

Step 2: Create virtual environment
	
	conda create -n LTXVideo python==3.10.11 -y

Step 3: Activate virtual environment
	
	conda activate LTXVideo

Step 4: Install wheel package

	pip install wheel

Step 5: Install requirements

	pip install -r requirements.txt

Step 6: Instal torchao

	pip install --pre torchao --index-url https://download.pytorch.org/whl/nightly/cpu

Step 7: Download models

	git clone https://huggingface.co/PixArt-alpha/PixArt-XL-2-1024-MS PixArt-alpha/PixArt-XL-2-1024-MS
	
	git clone https://huggingface.co/Lightricks/LTX-Video Lightricks/LTX-Video
	
Step 8: Inference (Update config.yaml)

```
conda activate LTXVideo
	
python inference.py
```