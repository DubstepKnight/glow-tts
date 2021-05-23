This is an implementation of a web application with multispeaker TTS using GlowTTS based on the Mozilla's TTS [repository](https://github.com/mozilla/TTS).

### How to start the application

In order to start the application you need to:
1. Clone the repository.
2. Use `python -m TTS.server.server --tts_checkpoint=/home/nurs/PycharmProjects/TTS/TTS/TTS/server/model/tts/best_model.pth.tar` command to start the applicaiton. The checkpoint is important to start the application with correct checkpoint.
3. It should start the server on the `http://0.0.0.0:5002/`. Visit that URL.
4. You will see a simple UI with text input. The text input does not work because of the problem described in my thesis (I will put the link to my thesis later, once it becomes available online).

