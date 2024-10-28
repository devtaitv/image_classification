Để chạy ứng dụng, bạn sẽ cần các thư viện Python sau:

**_tkinter_**: Cho giao diện đồ họa (thường được tích hợp sẵn trong Python).

**_Pillow_** (PIL): Để xử lý hình ảnh.

**_numpy_**: Để xử lý dữ liệu số.

**_skimage_** (scikit-image): Để tính toán đặc trưng HOG cho hình ảnh.

**_scikit-learn_**: Để huấn luyện các mô hình học máy như SVM và KNN.

**_matplotlib_**: Để vẽ biểu đồ.

**seaborn**: Để vẽ ma trận nhầm lẫn (confusion matrix).

**_joblib_**: Để lưu và tải mô hình.

Bạn có thể cài đặt tất cả các thư viện này bằng lệnh sau:

**pip install pillow numpy scikit-image scikit-learn matplotlib seaborn joblib**

Lưu ý: Thư viện tkinter thường được tích hợp sẵn trong các bản cài đặt Python, nhưng nếu bạn gặp lỗi "No module named 'tkinter'" trên Linux, bạn có thể cần cài đặt thủ công bằng lệnh:

**sudo apt-get install python3-tk**
