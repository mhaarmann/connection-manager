# Connection Manager

This is a tiny tool for storing and handling SSH/SCP connections.

Connections get stored in `~/.config/connection-manager/`.

## Setup

```console
wget https://gitlab.com/mhaarmann/connection-manager/-/raw/master/con
chmod +x con
sudo mv con /usr/local/bin/
```

## Usage

To display the options just run the command `con`.

## Config Examples

Run `con edit <connections|secrets>` to edit config files.

Connetction shortcuts need to match between both files. Setting secret entries is optional. 

#### Connections
```console
<connection-shortcut>:<user>@<server>
server1:user@server1.example.com
#server2:user@server2.example.com
```

#### Secrets
```console
<connection-shortcut>:<password>
server1:Secret#1
#server2:Secret#2
```