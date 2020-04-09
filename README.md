# Use Citrix with Hungarian Windows keyboard on MacOS 

**Use-case:** User --> Hungarian Keyboard Layout --> MacOs --> Citrix --> Windows

This script will _override_ your current Citrix config!
```bash
git clone https://github.com/it-was-working-yesterday/macos-citrix-hun-key-layout.git
cd macos-citrix-hun-key-layout
sudo cp Hungarian_Win.keylayout /Library/Keyboard Layouts/
cp Config /Users/$USER/Library/Application Support/Citrix Receiver/
```

Select Hun layout from Keyboard Settings



Keyboard layout is from https://github.com/zaki/mac-hun-keyboard 
