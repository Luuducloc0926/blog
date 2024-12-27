---
title: "Làm quen với OOP trong Java"
date: 2024-12-26
tags: ["Java", "OOP"]
---

### OOP là gì?  
Lập trình hướng đối tượng (Object-Oriented Programming - OOP) là một mô hình lập trình dựa trên khái niệm "đối tượng" (objects). Trong Java, OOP là cốt lõi, giúp bạn mô hình hóa các đối tượng trong thế giới thực vào chương trình.

### 4 nguyên lý của OOP trong Java  
1. **Encapsulation (Đóng gói)**:  
   - Dữ liệu (fields) và phương thức (methods) được đóng gói trong một class.  
   - Dữ liệu được bảo vệ bởi các từ khóa như `private`, `protected`.  

   **Ví dụ**:  
   ```java
   public class Person {
       private String name; // Đóng gói dữ liệu

       // Getter và Setter
       public String getName() {
           return name;
       }
       public void setName(String name) {
           this.name = name;
       }
   }
