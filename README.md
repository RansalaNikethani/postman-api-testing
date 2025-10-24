# JSONPlaceholder API Testing Collection

Comprehensive Postman collection for testing the JSONPlaceholder REST API.

## 📋 What's Tested

### Users Endpoints (5 tests)
- Get all users
- Get single user by ID
- Get user's posts
- Get user's albums
- Get user's todos

### Posts Endpoints (6 tests)
- Get all posts
- Get single post
- Create new post (POST)
- Update post (PUT)
- Partially update post (PATCH)
- Delete post

### Comments Endpoints (4 tests)
- Get all comments
- Get single comment
- Get comments for specific post
- Filter comments by parameters

### Albums & Photos (4 tests)
- Get all albums
- Get single album
- Get all photos
- Get photos from specific album

### Todos Endpoints (3 tests)
- Get all todos
- Get single todo
- Filter completed todos

### Negative Testing (3 tests)
- Invalid endpoint (404)
- Invalid user ID
- Invalid post ID

## 🎯 Test Coverage

- **Total Requests:** 25
- **HTTP Methods Tested:** GET, POST, PUT, PATCH, DELETE
- **Assertions:** Status codes, response structure, data validation
- **Negative Tests:** Error handling and edge cases

## 🚀 How to Use

1. Import `JSONPlaceholder-API-Tests.json` into Postman
2. Open the collection
3. Click "Run Collection" to execute all tests
4. Review test results

## ✅ Skills Demonstrated

- RESTful API testing
- HTTP methods (GET, POST, PUT, PATCH, DELETE)
- Request/response validation
- Test automation with Postman
- Negative testing
- Data validation
- API documentation

## 📊 Test Results

All 25 requests execute successfully with proper assertions.

## 🔧 API Used

[JSONPlaceholder](https://jsonplaceholder.typicode.com/) - Free fake REST API for testing and prototyping

---

**Created as part of QA portfolio development**
```
  
  📁 Todos (3 requests)
  
  📁 Negative Tests (3 requests)
  
