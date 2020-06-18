# Secure-Audio-Based-Data-Transfer
RSA based Secure Transmission of data via audio waves 

## Getting Started
  ```bash
	pip install numpy wave struct matplotlib simpleaudio time sounddevice scipy soundfile pyaudio
```

* Take an 8-bit wav file and set it as input
* Run EnAudio.py to encrypt the audio file using <strong>RSA</strong>
```console
python EnAudio.py
```
* Run NSDT.ipynb using:
```console
jupyter notebook NSDT.ipynb
```
* Decrypt recieved audio file using DeAudio.py
```console
python DeAudio.py
```
