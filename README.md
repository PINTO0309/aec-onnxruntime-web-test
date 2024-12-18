# aec-onnxruntime-web-test
AEC (Acoustic Echo Cancellation) execution test environment by onnxruntime-web.

## 0. AEC ONNX model

![image](https://github.com/user-attachments/assets/5880393f-13fb-4187-a9dc-aa3f42a9040a)

## 1. Load the model and test inference with dummy data

```bash
python -m http.server 8888
```

Access the following URL from your browser.

http://localhost:8888/test-model-load.html

![image](https://github.com/user-attachments/assets/c34fcf89-fdab-43e5-be0d-8ea80c19f7e9)

## 2. WIP

```bash
nvm use v18.16.1

npm init -y

npm info fft.js versions
[
  '1.0.0', '1.0.1', '2.0.0',
  '2.1.0', '3.0.0', '3.0.1',
  '3.0.2', '3.0.3', '3.0.4',
  '3.0.5', '3.0.6', '3.0.7',
  '3.0.8', '3.1.0', '3.1.1',
  '3.1.2', '3.1.3', '3.2.0',
  '4.0.0', '4.0.1', '4.0.2',
  '4.0.3', '4.0.4'
]

npm install fft.js@4.0.4
npm install -g browserify@17.0.1

npm list --depth=0
aec-onnxruntime-web-test@1.0.0 /home/xxxx/git/aec-onnxruntime-web-test
└── fft.js@4.0.4

browserify node_modules/fft.js/lib/fft.js --standalone FFT -o fft.js
```
