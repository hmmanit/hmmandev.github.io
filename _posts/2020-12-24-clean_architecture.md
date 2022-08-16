---
layout: article
title: Clean Architecture
description: Explore Clean Architecture
image: assets/images/clean_architecture.webp
---
> We should think about our applications as group of use cases that describe the intent of the application and group of plugins that give those uses cases access to outside word. - **Uncle Bob**

## Why

### Independent of libraries & frameworks

- Khi Clean Architecture được triển khai một cách hoàn thiện, nó không cần quan tâm framework Web/Mobile hay thứ gì khác
- Cũng không cần biết thư viện chúng ta sẽ sử dụng là gì.

### Independent of UI

- Việc phân chia rõ ràng các tầng làm cho các tầng UI không tạo ra bất kì sự phụ thuộc nào cho các tầng bên dưới nó.

### Independent of data sources

- Không cần biết data source của chúng ta là từ local hay remote, chúng ta chỉ cần định nghĩa chức năng và phần còn lại sẽ được xử lý tùy theo điều kiện sử dụng.

## What

### Layers

- Về cơ bản, Clean Architecture chia ứng dụng thành 3 tầng: Presentation, Domain, Data
- Một số biến thể của mô hình có thể sẽ có thêm những tầng khác, nhưng mục đích chung cũng chỉ là tạo ra một cấu trúc code không phụ thuộc và rành mạch dễ bảo trì nhất.

### Dependency rule

<img src="{% link assets/images/clean/dependency.png %}" width="600" />

- The Dependency Rule states that the source code dependencies can only point inwards.
- This means nothing in an inner circle can know anything at all about something in an outer circle. i.e. the inner circle shouldn’t depend on anything in the outer circle. The Black arrows represented in the diagram show the dependency rule.

### Data flow

## How