AI Parking Billing System
This project uses EasyOCR and OpenCV to automate parking fees based on Indian License Plate recognition.

Requirements
pip install easyocr opencv-python-headless pandas pytz

GPU support is recommended for faster OCR processing.

Features
IST Timezone: Automatically converts time to Indian Standard Time (+5:30).

Regex Validation: Only accepts Indian plates matching AA ## AA #### (e.g., AP22KA2468).

High-Frequency Scanning: Samples every 5th frame for better accuracy.

Fuzzy Matching: Matches plates even with minor OCR errors.

Automated Billing: Calculates fees at a rate of ₹80 per hour.
