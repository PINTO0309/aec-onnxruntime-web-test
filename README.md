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
