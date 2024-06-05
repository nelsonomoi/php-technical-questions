# PHP Technical Interview Preparation

This repository contains detailed answers and code examples for common PHP technical interview questions. Each section covers fundamental PHP concepts, best practices, and advanced topics, including Object-Oriented Programming (OOP), database connectivity, security, cloud services, and more.

## Table of Contents

1. [String Differences](#string-differences)
2. [Object-Oriented Programming](#object-oriented-programming)
3. [Exception Handling](#exception-handling)
4. [Database Connectivity](#database-connectivity)
5. [Security Practices](#security-practices)
6. [Cloud Service Providers](#cloud-service-providers)
7. [Infrastructure as Code](#infrastructure-as-code)
8. [PHP Functions](#php-functions)
9. [File Operations](#file-operations)
10. [REST API Integration](#rest-api-integration)
11. [Auto-Scaling in AWS](#auto-scaling-in-aws)
12. [Advanced Topics](#advanced-topics)

## String Differences

### Single-Quoted vs Double-Quoted Strings

- **Single-Quoted Strings**: Do not interpret variables and escape sequences (except `\\` and `\'`).
  ```php
  $name = 'John';
  $singleQuoted = 'Hello, $name'; // Outputs: Hello, $name
