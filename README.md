# Sound fix!
Kali Linux NetHunter (rootless) sound problem fix!

# Usage

💲 `pkg install pulseaudio`

💲 `nano ~/.bashrc`

💲 `pulseaudio --start \
    --load="module-native-protocol-tcp auth-ip-acl=127.0.0.1 auth-anonymous=1" \
    --exit-idle-time=-1`

💲 `bash`

💲 `echo "export PULSE_SERVER=127.0.0.1" >> ~/.bashrc ; bash`


