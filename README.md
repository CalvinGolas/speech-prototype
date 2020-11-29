To run, activate the virtual environemnt using:
	$source speech-prototype/Scripts/activate
Now cd into speech-prototype and then run the script using:
	$python transcribe.py --model deepspeech-0.9.1-models.pbmm --scorer deepspeech-0.9.1-models.scorer --audio audio/2830-3980-0043.wav
It should transcribe!! :D
