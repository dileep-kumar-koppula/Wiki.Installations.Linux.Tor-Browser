# How to Install Tor on Your PC

Tor (The Onion Router) is a free software that enables anonymous communication over the internet. It helps protect your privacy and allows you to browse the web without being tracked. Below are the steps to install Tor on your PC using the terminal.

## Installation Instructions

Follow these commands in your terminal to download and install Tor:

1. Install the Tor Browser Launcher
   ```bash
   sudo apt install torbrowser-launcher
   ```

2. Download the Tor Browser package
   ```bash
   wget https://www.torproject.org/dist/torbrowser/10.0.5/tor-browser-linux64-10.0.5_en-US.tar.xz
   ```

3. Extract the downloaded package
   ```bash
   tar -xf tor-browser-linux64-10.0.5_en-US.tar.xz
   ```

4. Start the Tor Browser
   ```bash
   ./tor-browser_en-US/start-tor-browser.desktop
   ```

5. Move the Tor Browser to the /opt directory for system-wide access
   ```bash
   sudo mv tor-browser_en-US /opt
   ```

6. Change directory to the Tor Browser installation
   ```bash
   cd /opt/tor-browser_en-US
   ```

7. Register the Tor Browser application
  ```bash
  ./start-tor-browser.desktop --register-app
  ```
