<!--
# Modern Convolutional Neural Networks
-->

# Mạng Nơ-ron Tích chập Hiện đại
:label:`chap_modern_cnn`

<!--
Now that we understand the basics of wiring together convolutional neural networks, we will take you through a tour of modern deep learning.
In this chapter, each section will correspond to a significant neural network architecture that was at some point (or currently) 
the base model upon which an enormous amount of research and projects were built.
Each of these networks was at briefly a dominant architecture and many were
at one point winners or runners-up in the famous ImageNet competition,
which has served as a barometer of progress on supervised learning in computer vision since 2010.
-->

Chúng ta đã hiểu các khái niệm cơ bản trong việc xây dựng mạng nơ-ron tích chập, giờ hãy cùng tìm hiểu về học sâu hiện đại.
Trong chương này, mỗi phần sẽ trình bày một kiến trúc mạng nơ-ron quan trọng mà tại một thời điểm nào đó (có thể cả trong hiện tại) là mô hình nền tảng được sử dụng trong một lượng lớn các nghiên cứu và dự án.
Mỗi kiến trúc mạng này thống trị trong một khoảng thời gian, nhiều mạng đã về nhất hoặc nhì tại ImageNet, cuộc thi được coi là thước đo sự phát triển của học có giám sát trong thị giác máy tính kể từ năm 2010.

<!--
These models include AlexNet, the first large-scale network deployed to beat conventional computer vision methods on a large-scale vision challenge;
the VGG network, which makes use of a number of repeating blocks of elements; the network in network (NiN) which convolves whole neural networks
patch-wise over inputs; the GoogLeNet, which makes use of networks with parallel concatenations; residual networks (ResNet), which are the
most popular go-to architecture today, and densely connected networks (DenseNet), which are expensive to compute but have set some recent benchmarks.
-->

Các mô hình này bao gồm AlexNet, mạng quy mô lớn đầu tiên được triển khai để đánh bại các phương pháp thị giác máy tính truyền thống trong một thử thách quy mô lớn;
VGG, mạng này tận dụng một số lượng lặp đi lặp lại các khối;
Mạng trong Mạng (*Network in Network - NiN*), kiến trúc này di chuyển toàn bộ mạng nơ-ron theo từng điểm ảnh ở đầu vào;
GoogLeNet, sử dụng phép nối song song giữa các mạng;
Mạng thặng dư (*residual networks - ResNet*), đây là kiến trúc được sử dụng phổ biến nhất hiện nay;
và mạng kết nối dày đặc (*densely connected network - DenseNet*), dù yêu cầu khối lượng tính toán lớn nhưng đạt được đánh giá xếp hạng cao gần đây.

```toc
:maxdepth: 2

alexnet_vn
vgg_vn
nin_vn
googlenet_vn
batch-norm_vn
resnet_vn
densenet_vn
```

## Những người thực hiện
Bản dịch trong trang này được thực hiện bởi:
<!--
Tác giả của mỗi Pull Request điền tên mình và tên những người review mà bạn thấy
hữu ích vào từng phần tương ứng. Mỗi dòng một tên, bắt đầu bằng dấu `*`.

Lưu ý:
* Nếu reviewer không cung cấp tên, bạn có thể dùng tên tài khoản GitHub của họ
với dấu `@` ở đầu. Ví dụ: @aivivn.

* Tên đầy đủ của các reviewer có thể được tìm thấy tại https://github.com/aivivn/d2l-vn/blob/master/docs/contributors_info.md
-->

* Đoàn Võ Duy Thanh
* Nguyễn Văn Cường
