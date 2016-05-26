# node-express-mongodb
1.首先搭建mongo

  use nem
  db.createCollection("users")
  db.users.insert({userid: "admin", password: "123456"})
  db.users.find()

  成功将输出{ "_id" : ObjectId("573d8565151f7a9f1723c8f6"), "userid" : "admin", "password" : "123456" }

2.安装node模块

  cd nem  ##进入此目录
  npm install
  npm start
  
成功后，访问http://127.0.0.1:8000/
