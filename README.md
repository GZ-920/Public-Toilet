# 完全本地 Logo + PaddleOCR

安装：`npm install`

运行：`npm run dev`

构建：`npm run build`

放入：
- public/logo/black.png
- public/logo/white.png
- public/models/PP-OCRv5_mobile_det.tar
- public/models/PP-OCRv5_mobile_rec.tar
- public/wasm/ 下的 ONNX Runtime Web WASM 文件

模型 tar 必须是未压缩 ustar，并包含 inference.onnx 和 inference.yml；model_name 必须与 PP-OCRv5_mobile_det / PP-OCRv5_mobile_rec 一致。
