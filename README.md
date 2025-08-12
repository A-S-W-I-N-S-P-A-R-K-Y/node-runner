# X--BOT--MD - WhatsApp Bot (Colab Edition)

A powerful WhatsApp bot built with Node.js, tailored to run even in temporary environments like **Google Colab** for quick testing and experimentation.

> ⚠️ This setup is best for **testing or development** purposes. Google Colab is not designed for long-term bot hosting or persistent sessions.

---

## 🚀 Quick Start in Google Colab

Follow these steps to run the bot in Google Colab:

### 1. Open a New Colab Notebook

Go to: [https://colab.research.google.com](https://colab.research.google.com)

### 2. Paste the Full Setup Code

```bash
# Install Node.js (v18)
!curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -
!sudo apt-get install -y nodejs

# Install ffmpeg
!sudo apt-get install -y ffmpeg

# Check versions
!node -v
!npm -v
!ffmpeg -version

# Clone the bot repo
!git clone https://github.com/A-S-W-I-N-S-P-A-R-K-Y/X--BOT--MD.git

# Change directory
%cd X--BOT--MD

# Install dependencies
!npm install

# Start the bot
!npm start
