 Easy File Share
 
 Easy file share is a cross-platform desktop application that lets you securely share folders and stream videos between Windows and macOS computers on the same local network.
✨ Features
🔒 Password-protected access
🌐 Automatic device discovery
📁 Share folders directly from your computer
🎬 Built-in video player with subtitle support
⚡ Fast streaming with instant seeking
🖥️ Windows & macOS support

📸 Screenshot
(Add a screenshot here)

💻 Installation
Windows
Download Easy-File-Share-Windows.exe from the Releases page.
Run the installer.
Launch Easy File Share.

macOS
Download easy-file-share-for-mac.zip.
Extract the archive.
Run:
chmod +x setup-mac.sh
./setup-mac.sh
Start the application.

🚀 Usage
Share Files
Launch Easy File Share.
Select the folder you want to share.
Enter:
Username
Password
Port (default: 3000)
Click Start Sharing.

Connect to Another Computer
Wait until nearby devices appear.
Select a device.
Enter its password.
Click Connect.

Watch Videos
Click ▶ Play on any video.
Videos stream instantly using the built-in player.
Load subtitles (SRT, VTT, ASS, SUB) using the 📄 Subtitles button.
Jump to any position without downloading the entire file.

🛠 Build from Source
Requirements
Node.js 16+
npm
Git
git clone https://github.com/yourusername/easy-file-share.git
cd easy-file-share
npm install
npm start
Windows
npm run build:win
macOS
npm run build:mac

🐛 Troubleshooting
Devices not found
Run:
.\fix-windows-firewall.ps1
Also verify:
Both devices are on the same network.
Windows network profile is Private.

Connection timeout
Allow TCP port 3000 through the firewall.

Video won't play
Verify the server is still running.
Check your network connection.
If streaming fails, download the file and play it locally.

Folder selection issues
Restart the application.
On macOS, grant Full Disk Access in System Settings → Privacy & Security.

📄 License
MIT License.

