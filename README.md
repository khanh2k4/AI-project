Hướng dẫn sử dụng ChatBot

Đầu tiên, tạo file .env đặt các biến môi trường và APT key vào 
VD:
LIVEKIT_URL="..."
LIVEKIT_API_SECRET="..."
LIVEKIT_API_KEY="..."
OPENAI_API_KEY="..."
DEEPGRAM_API_KEY= "..."

Lệnh cài môi trường ảo
python -m venv env

Kích hoạt môi trường ảo
./env/Scripts/activate

Lệnh cài các module cần thiết trong file requirements.txt
pip install -r requirements.txt

Run command
python main.py start

Link kết nối tới server livekit
https://agents-playground.livekit.io/
