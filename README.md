# Computer vision models
Dự án được tạo ra để lưu trữ các mô hình liên quan đến lĩnh vực computer vision, các kiến trúc ở đây đều được cài đặt và huấn luyện lại từ đầu và sử dụng pytorch để cài đặt
# Các kiến trúc
## ResNet
- Kiến trúc ResNet được xây dựng dựa trên mạng ResNet34 với các thông số giống với trong bài báo [Deep Residual Learning for Image Recognition](https://arxiv.org/abs/1512.03385)

![image](https://github.com/takanami12/computer_vision_models/blob/main/ResNet/Architecture-of-ResNet34-29.png)

- Mô hình được huấn luyện từ đầu trên bộ dữ liệu MNIST và bộ dữ liệu MNIST được chỉnh cho bài toán phân loại chữ số có nên thẳng và nét cong
- Sau khi được huấn luyện trên bộ dữ liệu MNIST, mô hình đạt độ chính xác là 99.53%

## Vision Transformer
- Kiến trúc Vision Transformer được xây dựng theo đúng với kiến trúc trong bài báo [An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale
](https://arxiv.org/abs/2010.11929)

![image](https://github.com/takanami12/computer_vision_models/blob/main/ViT/vision_transformer_architecture.png)

- Mô hình được huấn luyện từ đầu trên bộ dữ liệu MNIST
- Sau khi được huấn luyện trên bộ dữ liệu MNIST, mô hình đạt độ chính xác là 98.39%
