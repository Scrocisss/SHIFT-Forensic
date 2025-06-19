
volatility3:

```bash
cd ~
python3 -m venv myenv
source myenv/bin/activate
pip install volatility3
git clone https://github.com/volatilityfoundation/volatility3.git
cd volatility3/
pip install -e ".[dev]"
```



volatility2:

```bash
cd ~
deactivate
git clone https://github.com/volatilityfoundation/volatility
cd volatility
python2 setup.py install
curl https://bootstrap.pypa.io/pip/2.7/get-pip.py --output get-pip.py
python2 get-pip.py
pip2 --version
pip2 install virtualenv==16.7.10
python2 /usr/local/lib/python2.7/dist-packages/virtualenv.py -p /usr/bin/python2 /root/volatility/myenv2
source /root/volatility/myenv2/bin/activate
python --version
apt install -y python2.7-dev build-essential
pip install pycryptodome
pip install distorm3
```
