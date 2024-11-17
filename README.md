# Graph - Đồ thị

### **Đồ thị** là gì?
Đồ thị là một cấu trúc dữ liệu (CTDL) bao gồm các đỉnh và cạnh được nối với nhau. Đồ thị mô tả các đối tượng và các mối quan hệ giữa chúng. Các đối tượng được gọi là **đỉnh** (hay nút, điểm), còn mối quan hệ giữa các đối tượng gọi là **cạnh** (hay liên kết, đường thẳng).

Thông thường, đồ thị được mô tả dưới dạng sơ đồ với các chấm hoặc hình tròn đại diện cho đỉnh và các đường thẳng hoặc đường cong đại diện cho các cạnh.

[Wikipedia](https://en.wikipedia.org/wiki/Graph_(discrete_mathematics)#:~:text=a%20graph%20is,for%20the%20edges.)

![Đồ thị](https://files.catbox.moe/r42dar.png)

---

## 1. Đồ thị có hướng (Directed Graph hay Digraph)

Đồ thị có hướng bao gồm các đỉnh và cạnh được nối với nhau, nhưng các cạnh có **hướng** (thể hiện bằng mũi tên) chỉ ra chiều đi của các kết nối. 

- **Ví dụ:** Nếu có cạnh từ A -> B, chỉ có một con đường duy nhất từ A đến B. Không thể đi ngược lại từ B -> A.

![Đồ thị có hướng](https://files.catbox.moe/zrqxas.png)

[Source: Wikipedia](https://vi.wikipedia.org/wiki/%C4%90%E1%BB%93_th%E1%BB%8B_(l%C3%BD_thuy%E1%BA%BFt_%C4%91%E1%BB%93_th%E1%BB%8B)#%C4%90%E1%BB%93_th%E1%BB%8B_c%C3%B3_h%C6%B0%E1%BB%9Bng)

---

## 2. Đồ thị vô hướng (Undirected Graph)

Đồ thị vô hướng là đồ thị mà các cạnh **không có hướng**, nghĩa là nếu có một cạnh nối giữa hai đỉnh A và B, bạn có thể di chuyển từ A đến B hoặc từ B đến A mà không phân biệt chiều của cạnh.
- **Ví dụ:** Nếu có cạnh từ A -> B, thì có thể đi ngược lại từ B -> A

![Đồ thị vô hướng](https://files.catbox.moe/bqv8ak.png)
