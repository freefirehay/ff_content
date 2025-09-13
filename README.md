# FF FaceSwap – GitHub Pages (embed từ Hugging Face Spaces)

- Space gốc: https://huggingface.co/spaces/freefirehay/ff_faceswap  
- Direct URL: https://freefirehay-ff-faceswap.hf.space

## Sử dụng
- `index.html`: nhúng trực tiếp Space với `<gradio-app>`.
- `api-demo.html`: ví dụ gọi API Space bằng @gradio/client (JS), chạy trên GitHub Pages.

## Phát hành
- Repo bật GitHub Pages (Source: GitHub Actions).
- Mỗi lần push lên `main`, trang sẽ tự cập nhật.

## Ghi chú
- Hãy giữ **gradio.js** đúng version khớp Space (hiện tại 5.45.0).
- Nếu dùng Space Private, cần token & cấu hình CORS phù hợp.
