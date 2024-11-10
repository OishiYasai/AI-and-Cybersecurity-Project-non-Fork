##Virtual Env
Python3.7
python -m venv myenv37
.\myenv37\Scripts\activate
Set-ExecutionPolicy RemoteSigned
Set-ExecutionPolicy Restricted
pip install setuptools==58.2.0
pip install torch==1.7.0+cpu torchvision==0.8.1+cpu torchaudio===0.7.0 -f https://download.pytorch.org/whl/torch_stable.html
