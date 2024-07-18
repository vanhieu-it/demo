# test jenkins http://localhost:9090/login 

### Chạy ứng dụng bằng cách chạy tệp TodoApplication.java.

- API có các endpoint cơ bản:
+ GET /api/todos: Lấy tất cả công việc.
+ GET /api/todos/{id}: Lấy công việc theo ID.
+ POST /api/todos: Tạo một công việc mới.
+ PUT /api/todos/{id}: Cập nhật công việc theo ID.
+ DELETE /api/todos/{id}: Xóa công việc theo ID.
  
```cmd
mvn clean install
```
###  Kiểm Tra API
- GET tất cả công việc:
```yaml
curl -X GET http://localhost:8080/api/todos
```
-POST tạo công việc mới:
```yaml
curl -X POST http://localhost:8080/api/todos -H "Content-Type: application/json" -d '{"title":"New Task","description":"Task description"}'
```

```
mvn spring-boot:run
```
