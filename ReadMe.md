20200223  
**Nodeno JSON Server とそのサービス　My JSON Server **
https://www.xlsoft.com/jp/blog/blog/2019/08/20/post-7139/#My_JSON_Server

**01. Git リポを作る　giogiokuma/json **  s

**02. db.json コードを作る**   

**03. コードを貼り付ける**   
```
{
  "posts": [
    { "id": 1, "title": "json-server", "author": "typicode" }
  ],
  "comments": [
    { "id": 1, "body": "some comment", "postId": 1 }
  ],
  "profile": { "name": "typicode" }
}
```
**04 ローカルで動作**    
`
json-server --watch db.json  
`
これで動く  
```
PS D:\_dev\json-server> json-server --watch db.json  
 
  \{^_^}/ hi!
 
  Loading db.json
  Done
 
  Resources
  http://localhost:3000/posts
  http://localhost:3000/comments
  http://localhost:3000/profile
 
  Home
  http://localhost:3000
 
  Type s + enter at any time to create a snapshot of the database  
  Watching...  
```
**アクセス**  
http://localhost:3000  
http://localhost:3000/posts/    

**05 ターミナルからでも**    

```
curl localhost:3000/posts  
```

**curl でポスト**  

--------------------  
**Postman **  


**30秒で作れるモック**  
https://www.webprofessional.jp/mock-rest-apis-using-json-server/

--------------------  


**My JSON Server とは**  

https://www.xlsoft.com/jp/blog/blog/2019/08/20/post-7139/#My_JSON_Server


**06 My JSON Server**   
 01 giogiokuma/json リポジトリを作成  
 
 02 db.json を作成
 
 03 **URL にアクセス　**  
 https://my-json-server.typicode.com/giogiokuma/json
 
 https://my-json-server.typicode.com/giogiokuma/json/posts