# Hướng dẫn cài đặt Dependencies

## Cài đặt tất cả dependencies

```bash
npm install
```

## Hoặc cài đặt từng package riêng lẻ

### AWS SDK
```bash
npm install @aws-sdk/client-dynamodb
npm install @aws-sdk/client-s3
npm install @aws-sdk/lib-dynamodb
```

### Web Framework & Template Engine
```bash
npm install express
npm install ejs
```

### Utilities
```bash
npm install dotenv
npm install method-override
npm install multer
npm install uuid
```

## Cài đặt với phiên bản cụ thể

```bash
npm install @aws-sdk/client-dynamodb@^3.978.0 @aws-sdk/client-s3@^3.978.0 @aws-sdk/lib-dynamodb@^3.978.0 dotenv@^17.2.3 ejs@^4.0.1 express@^5.2.1 method-override@^3.0.0 multer@^2.0.2 uuid@^13.0.0
```

## Mô tả các package

- **@aws-sdk/client-dynamodb**: AWS SDK cho DynamoDB
- **@aws-sdk/client-s3**: AWS SDK cho S3
- **@aws-sdk/lib-dynamodb**: Thư viện DynamoDB Document Client
- **dotenv**: Quản lý biến môi trường
- **ejs**: Template engine để render views
- **express**: Web framework cho Node.js
- **method-override**: Hỗ trợ HTTP methods như PUT, DELETE
- **multer**: Middleware xử lý file upload
- **uuid**: Tạo unique identifiers
