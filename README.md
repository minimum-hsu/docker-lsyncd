# Build

docker build -t minimum/lsyncd .

# Run

docker run -d -v /path/to/lsyncd.lua:/root/lsyncd.lua -e CONFIG=/root/lsyncd.lua minimum/lsyncd
