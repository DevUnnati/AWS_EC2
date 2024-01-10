<h1> Setup AWS CLI </h1>

# Update system

sudo apt update

# Install Unzip

sudo apt install -y unzip

# Download and install AWS CLI v2
curl "https://d1vvhvl2y92vvt.cloudfront.net/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
unzip awscliv2.zip
sudo ./aws/install

# Verify the installation
aws --version
