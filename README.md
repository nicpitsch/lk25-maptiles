lk25-maptiles
=============

Simple local map tileserver with a test map

# Usage

Clone this repo somewhere and run `python corsserver.py` in it. This will start a local server on port 8000, which you can access at `0.0.0.0:8000`, `127.0.0.1:8000` or your local network IP, `192.168.???.???:8000`. It sends super friendly CORS headers so you can access it from everywhere. 

The tile URL scheme is `hostName+':8000/{z}/{x}/{y}.png'`, in this particular case in CRS EPSG 21781, if you find your offsets are weird, this is why. 
