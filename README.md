
## 我改的東西

- yolo裡面有一個detect.py我有更改程式碼


### 新增的程式碼

1. 安裝必要的套件及 YOLOv5：
    ```bash
    !git clone https://github.com/ultralytics/yolov5.git
    %cd yolov5
    !pip install -r requirements.txt
    ```

2. 跑模型解果最後多加一個--nosave：
    ```bash
    !python detect.py --weights /content/best_1.pt --img 640 --conf 0.5 --source /content/test_pic --nosave
    ```

3. 阿前面那些sudo只是我自己少的東西，不用管


