# VR Playground

Playing around with the WebXR APIs. 

Code samples at: https://github.com/immersive-web/webxr-samples

## Setup

### On Oculus
To view on the Oculus:
1. clone the repo
2. python -m SimpleHTTPServer 3000
3. ifconfig en0, find IP on local network
4. On Oculus Browswer - go to 192.168.0.x:3000 
Except it doesn't work because HTTPS is required to serve the WebXR
APIs - :grimace:

### On Emulator
1. Open Firefox
2. Go to page on localhost:4000
3. Option + Command + K to open the dev console
4. In the console top bar, find "WebXR". 
5. Click enter VR
6. boom done

## Resources

* https://www.khronos.org/gltf/
* https://get.webgl.org/
* https://www.youtube.com/watch?v=01Fl6gACK5g