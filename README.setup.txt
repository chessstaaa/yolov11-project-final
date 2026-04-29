SETUP ENVIRONTMENT PADA FILE JUPYTER CPU ONLY:
1. Pada terminal VS Code (CTRL + ~)
2. python -m venv venv
3. venv\Scripts\activate
4. pip install ultralytics

SETUP APABILA MEMILIKI GPU NVIDIA (CUDA):
1. py -3.11 -m venv venv (PASTIKAN MEMILIKI PYTHON VERSI 3.11)
2. .\venv\Scripts\Activate.ps1
3. python -m pip install --upgrade pip
4. pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121

DATASET: -

SETUP DATASET:
1. Extract ke folder projek yolo nya
2. Gunakan train.ipynb untuk training