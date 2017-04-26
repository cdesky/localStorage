# localStorage

1、存储：localStorage.setItem(key,value)
如果key存在时，更新value

2、获取：localStorage.getItem(key)
如果key不存在返回null

3、删除：localStorage.removeItem(key)
一旦删除，key对应的数据将会全部删除

4、全部清除：localStorage.clear()
某些时候使用removeItem逐个删除太麻烦，可以使用clear,执行的后果是会清除所有localStorage对象保存的数据

5、遍历localStorage存储的key
.length 数据总量，例：localStorage.length
.key(index) 获取key，例：var key=localStorage.key(index);

6、存储JSON格式数据
JSON.stringify(data) 将一个对象转换成JSON格式的数据串,返回转换后的串
JSON.parse(data) 将数据解析成对象，返回解析后的对象
