# Voice_Converter_with_VOICEVOX

## 1. Description
This is a voice converter for Japanese based on the VOICEVOX. You can convert to the wave file from the text that is inputed by keyboard and/or voice.  

## 2. Operational Environment
- Windows 10/11 64-bit
- Visual Studio Code (VS Code)
- Python 3.9.4 64-bit
- Browser: Microsoft Edge or Google Chrome

## 3. Demo
![Voice Converter](https://to-fujita.github.io/Images/Voice_Converter.png "Images for Voice Converter")

## 4. Details
I have confirmed this Python Script on the above conditions only. I will show you below how to execute the Python script.

### 4-1. Preparation
(a) Download & install VOICEVOX  
Please download the [VOICEVOX](https://voicevox.hiroshiba.jp/), and install to your PC. 
  
(b) Download & unzip the file.  
Please download following file and put the unzipped folder under the system path passed.
- Voice_Converter_with_VOICEVOX: Please download from above "Code".
  
(c) Install some libraries to your Python  
Please install following libraries to your Python system.
- requests: pip install requests
- wave: pip install wave
- Flask: pip install Flask
  
### 4-2. Try to Convert to wave file
(a) Execute the VOICEVOX  
Please execute the VOICEVOX that is downloaded and installed to your PC, before execute the voice converter.   
  
(b) Execute the Voice_Converter  
The voice converter program is as follow.  
- main_Voice_Converter.py
Please open the above file on the VS Code, then click the "Run" and the "Start Debugging" or the "Run Without Debugging". Wait a few second, it will be displayed "*Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)" at the Terminal. Then, after open the Browser, please input "http://127.0.0.1:5000". You can convert the input text by keybord and/or voice to the wave file and voice that is selected character.  
  
## 5. Reference
- [VOICEVOX](https://voicevox.hiroshiba.jp/)
- [VS Code](https://azure.microsoft.com/ja-jp/products/visual-studio-code/)
- [Python](https://www.python.org/)
  
## 6. License
- Programs: MIT
- All of the images and VOICEVOX: Please confirm to each author.
  
## 7. Author
[T. Fujita](https://github.com/To-Fujita)
