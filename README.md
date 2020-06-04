# Connection Manager

This is a tiny tool for storing and handling SSH/SCP connections.

Connections get stored in `~/.config/connection-manager/`.

# Setup

```console
cd ~/
git clone https://gitlab.com/mhaarmann/connection-manager.git
chmod +x connection-manager/con
echo "alias con='~/connection-manager/con'" >> .bashrc
source .bashrc
```

# Usage

To display the options just run the command `con`.