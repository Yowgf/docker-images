FROM cypress/browsers:node-18.16.0-chrome-113.0.5672.92-1-ff-113.0-edge-113.0.1774.35-1

apt-get update
apt-get install \
        wget \
        unzip \
        python3-pip \
        python3-venv \
        build-essential \
        libncursesw5-dev \
        libssl-dev \
        libsqlite3-dev \
        tk-dev \
        libgdbm-dev \
        libc6-dev \
        libbz2-dev \
        libffi-dev \
        zlib1g-dev

# Install Python
wget https://www.python.org/ftp/python/3.10.6/Python-3.10.6.tgz
tar -xf Python-3.10.6.tgz
cd Python-3.10.6
./configure --enable-optimizations
make altinstall

# Install pnpm
npm i -g pnpm
