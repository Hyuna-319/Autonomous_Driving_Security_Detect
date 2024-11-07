## 절대 경로 지정해서 templates 인식 시키기

### web_server.py

app = Flask(
    __name__,
    template_folder='/home/hyuna/ros2_ws/src/yolo_integration/yolo_integration//templates'
)
