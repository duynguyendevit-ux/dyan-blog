---
title: Bài viết đầu tiên
draft: false
tags:
  - random
  - thoughts
date: 2026-06-06
---

# Bài viết đầu tiên 🚀

Đây là bài viết đầu tiên trên blog mới. Mình đang test xem Quartz hoạt động như thế nào.

## Features hay của Quartz

### 1. Syntax Highlighting

```java
@RestController
@RequestMapping("/api")
public class UserController {
    
    @GetMapping("/users/{id}")
    public ResponseEntity<User> getUser(@PathVariable Long id) {
        User user = userService.findById(id);
        return ResponseEntity.ok(user);
    }
}
```

### 2. Wikilinks

Có thể link đến bài khác dễ dàng: [[welcome]] hoặc [[tech-stack]]

### 3. Tags

Dùng tags để phân loại bài viết: #tech #java #blog

### 4. Backlinks

Quartz tự động tạo backlinks - xem phần cuối mỗi trang để thấy bài nào link đến trang này.

### 5. Graph View

Có graph view để visualize mối quan hệ giữa các bài viết.

## Kế hoạch tiếp theo

- [ ] Viết về Spring Boot best practices
- [ ] Share kinh nghiệm làm microservices
- [ ] Tutorials về Redis & Kafka
- [ ] Side project ideas

---

*Published on 2026-06-06*
