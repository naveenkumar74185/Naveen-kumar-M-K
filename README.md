{
readkey: [Function: readkey],
createkey: [Function: createkey],
deletekey: [Function: deletekey],
}
db.createkey("apple", 30)
key-value pair created
 db.readkey("apple")
{"apple":30}
 db.createkey("grape",30,15)
key-value pair created
 db.readkey("grape")
{"grape":30}
> db.createkey("lemon", 100,40)
"key-value pair created
 db.readkey("lemon")
{"lemon":100}
> db.createkey("banana", 50)
"key-value pair created
 db.readkey("banana")
{"banana":50}
> db.deletekey("banana")
"key deleted"
