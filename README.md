# video-hand-positioning-and-gesture-recognition

1. 创建一个新的虚拟环境。

```
conda create -n mediapipe_env python=3.8
```

2. 激活新创建的环境：

```
conda activate mediapipe_env
```

3. 使用 `pip` 安装 TensorFlow：

```
pip install tensorflow
```

4. 确认 TensorFlow 安装成功，尝试导入 TensorFlow 并检查版本：

```
import tensorflow as tf
print(tf.__version__)
```

5. 如果 TensorFlow 安装成功，现在可以安装 MediaPipe 库：

```
pip install mediapipe
```

6. 运行代码，可以实时看到两个手的骨骼点

```
python main.py
```

