---
type: Page
title: 'hàm trong C++ '
description: null
icon: null
createdAt: '2024-11-24T00:38:49.683Z'
creationDate: 2024-11-24 07:38
modificationDate: 2024-11-23 16:40
tags: []
coverImage: null
---

### 1. **Hàm định nghĩa (User-defined Functions)**

Đây là những hàm mà bạn tự định nghĩa trong chương trình để thực hiện một nhiệm vụ cụ thể.

**Cấu trúc chung:**

cpp

`return_type function_name(parameters) {     // Mã thực thi }`

Ví dụ về hàm định nghĩa:

cpp

`int add(int a, int b) {     return a + b; }`

### 2. **Hàm không có giá trị trả về (Void Functions)**

Đây là hàm không trả về giá trị nào, chúng chỉ thực hiện một hành động cụ thể. Kiểu trả về sẽ là `void`.

**Cấu trúc chung:**

cpp

`void function_name(parameters) {     // Mã thực thi }`

Ví dụ về hàm void:

cpp

`void printMessage() {     cout << "Hello, World!" << endl; }`

### 3. **Hàm trả về giá trị (Functions with Return Type)**

Những hàm này sẽ trả về một giá trị sau khi thực hiện. Kiểu dữ liệu của giá trị trả về phải được xác định trước trong phần khai báo hàm.

**Cấu trúc chung:**

cpp

`return_type function_name(parameters) {     // Mã thực thi     return value;  // Trả về giá trị }`

Ví dụ:

cpp

`int multiply(int a, int b) {     return a * b; }`

### 4. **Hàm tham chiếu (Reference Functions)**

Hàm tham chiếu là hàm trả về một tham chiếu đến một đối tượng. Điều này cho phép bạn thay đổi giá trị của đối tượng trong hàm mà không cần phải sao chép nó.

**Cấu trúc chung:**

cpp

`return_type& function_name(parameters) {     // Mã thực thi     return variable; }`

Ví dụ:

cpp

`int& getElement(int arr[], int index) {     return arr[index]; }`

### 5. **Hàm nạp chồng (Overloaded Functions)**

Hàm nạp chồng là khi có nhiều hàm cùng tên nhưng khác nhau về số lượng hoặc kiểu tham số. Compiler sẽ chọn hàm phù hợp dựa trên tham số khi gọi.

**Ví dụ:**

cpp

`int add(int a, int b) {     return a + b; }  double add(double a, double b) {     return a + b; }`

### 6. **Hàm tĩnh (Static Functions)**

Hàm tĩnh là hàm mà chỉ có thể được gọi trong phạm vi của cùng một lớp hoặc file nguồn. Hàm này không thể truy cập các thành viên không tĩnh của lớp.

**Cấu trúc chung:**

cpp

`static return_type function_name(parameters) {     // Mã thực thi }`

Ví dụ:

cpp

`class MyClass { public:     static void display() {         cout << "This is a static function." << endl;     } };`

### 7. **Hàm đệ quy (Recursive Functions)**

Đây là hàm gọi lại chính nó để giải quyết bài toán. Hàm đệ quy thường được sử dụng trong các bài toán như tìm kiếm, sắp xếp, hoặc tính toán đệ quy.

**Ví dụ:**

cpp

`int factorial(int n) {     if (n == 0) return 1;     return n * factorial(n - 1); }`

### 8. **Hàm Lambda (Lambda Functions)**

Đây là một loại hàm vô danh (không có tên) có thể được khai báo và sử dụng trong chương trình. Hàm lambda có thể sử dụng các biến bên ngoài phạm vi của nó mà không cần phải khai báo lại.

**Cấu trúc chung:**

cpp

`[capture](parameter_list) -> return_type { body };`

**Ví dụ:**

cpp

`auto sum = [](int a, int b) { return a + b; }; cout << sum(3, 4);  // Output: 7`

### 9. **Hàm const (Const Functions)**

Hàm `const` là hàm không thay đổi trạng thái của đối tượng mà nó được gọi trên. Các hàm này thường được sử dụng trong các lớp để đảm bảo tính bất biến của đối tượng.

**Cấu trúc chung:**

cpp

`return_type function_name(parameters) const {     // Mã thực thi }`

**Ví dụ:**

cpp

`class MyClass { public:     int getValue() const {         return value;     } private:     int value = 10; };`

### 10. **Hàm template (Template Functions)**

Hàm template là các hàm có thể làm việc với nhiều kiểu dữ liệu khác nhau. Bạn chỉ cần định nghĩa một hàm duy nhất với các tham số kiểu dữ liệu chung.

**Cấu trúc chung:**

cpp

`template <typename T> return_type function_name(T parameter) {     // Mã thực thi }`

**Ví dụ:**

cpp

`template <typename T> T add(T a, T b) {     return a + b; }`

### 11. **Hàm kết hợp (Inline Functions)**

Hàm inline là những hàm có thể được thực thi trực tiếp mà không cần phải gọi. Compiler sẽ thay thế việc gọi hàm bằng mã thực thi của hàm đó. Hàm inline thường được sử dụng với các hàm đơn giản và nhỏ để tăng hiệu suất.

**Cấu trúc chung:**

cpp

`inline return_type function_name(parameters) {     // Mã thực thi }`

**Ví dụ:**

cpp

`inline int square(int x) {     return x * x; }`

### Kết luận

C++ cung cấp một loạt các loại hàm có thể giúp bạn linh hoạt hơn trong việc thiết kế chương trình. Từ những hàm đơn giản, đệ quy cho đến hàm template mạnh mẽ, bạn có thể tận dụng chúng để giải quyết các vấn đề phức tạp.


