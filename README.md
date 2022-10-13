# Eclipse im Browser

Diese Repository ist eine Demonstration wie die Eclipse IDE im Browser in der KBK genutzt werden kann, um dort z.B. Projekte im EAI Umfeld zu realisieren.

Insgesamt startet der Workspace mit dem Download und dem Starten von Eclipse in unter einer Minute.

![](./assets/eclipse.png)

## Installation EAI

```
echo -e "# For Tizen studio\ndeb http://cz.archive.ubuntu.com/ubuntu bionic main universe" | sudo tee /etc/apt/sources.list.d/tizen-bionic-libwebkitgtk.list
sudo apt-get update
sudo apt-get install libwebkitgtk-1.0-0
sudo apt-get install webkit*
```