To run, activate the virtual environment using:

	$ source speech-prototype/Scripts/activate

Install DeepSpeech

    $ pip3 install deepspeech
    
Now cd into speech-prototype and download the required files and example audio file:


$ curl -LO https://github.com/mozilla/DeepSpeech/releases/download/v0.9.1/deepspeech-0.9.1-models.pbmm

$ curl -LO https://github.com/mozilla/DeepSpeech/releases/download/v0.9.1/deepspeech-0.9.1-models.scorer

$ curl -LO https://github.com/mozilla/DeepSpeech/releases/download/v0.9.1/audio-0.9.1.tar.gz

$ tar xvf audio-0.9.1.tar.gz

Run the script using:

	$ python transcribe.py --model deepspeech-0.9.1-models.pbmm --scorer deepspeech-0.9.1-models.scorer --audio audio/2830-3980-0043.wav
	
It should transcribe!! :D
