# 0x01. NoSQL
---

## Example: MongoDB: Install MongoDB 4.2 in Ubuntu 18.04
- Commands to install MongoDB
  1. wget -qO - https://www.mongodb.org/static/pgp/server-4.2.asc | apt-key add -
  2. echo "deb [ arch=amd64,arm64 ] https://repo.mongodb.org/apt/ubuntu bionic/mongodb-org/4.2 multiverse" > /etc/apt/sources.list.d/mongodb-org-4.2.list
  3. sudo apt-get update
  4. sudo apt-get install -y mongodb-org
  5. sudo service mongod status
  6. mongo --version
  7. pip3 install pymongo
  8. python3
  9. >>> import pymongo
  10. pymongo.__version__
---

