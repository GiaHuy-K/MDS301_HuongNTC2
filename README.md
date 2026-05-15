# MDS301- Môi trường lập trình

Dự án này chứa các mã nguồn và bài tập cho môn học **MDS (Machine Learning In Data Science)**. Để đảm bảo tính nhất quán và tránh xung đột thư viện, vui lòng thiết lập môi trường ảo theo hướng dẫn dưới đây.
## 1. Danh sách các thư viện 

| Nhóm chức năng | Các thư viện sử dụng |
| :--- | :--- |
| **Data Processing** | `numpy`, `pandas` |
| **Visualization** | `matplotlib` |
| **Machine Learning** | `scikit-learn`, `statsmodels`, `prophet`, `surprise` |
| **Deep Learning** | `torch`, `torchvision`, `torchmetrics` |
| **Web API & Deployment** | `flask`, `fastapi`, `uvicorn` |
| **MLOps & Testing** | `mlflow`, `evidently`, `pytest` |
| **Utilities** | `joblib`, `pathlib`, `gensim` |

---
## 2. Yêu cầu hệ thống
- Python 3.9+ (Khuyên dùng 3.10)
- Trình quản lý gói `pip`

## 3. Thiết lập môi trường ảo (venv)

### Bước 1: Tạo môi trường ảo
Mở Terminal tại thư mục dự án và chạy:
```bash
python -m venv .venv
```
### Bước 2: Kích hoạt môi trường
- **Windows (PowerShell):**
```
.\.venv\Scripts\Activate.ps1
```
- **Windows (Command Prompt):**
```cmd
.venv\Scripts\activate.bat
```  
- **Mac/Linux::**
 ```cmd
 source .venv/bin/activate 
```

### Bước 3: Cài đặt các thư viện cần thiết
Cài đặt toàn bộ danh sách thư viện từ file `requirements.txt`:
```bash
pip install -r requirements.txt
```