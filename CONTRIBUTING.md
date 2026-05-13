### 🚀 Cách đóng góp

#### Cách 1 — Tạo Issue (dễ nhất, không cần biết Git)

1. Vào tab **[Issues](../../issues)** → nhấn **New Issue**
2. Đặt tiêu đề theo dạng: `Thêm nickname cho tên X`
   > Ví dụ: `Thêm nickname cho tên Đức`
3. Trong phần mô tả, ghi rõ:
   ```
   Nickname đề xuất:
   - Đức cớp
   - Đức toàn cầu 
   ```
4. Nhấn **Submit** — xong! Tôi sẽ xem xét và thêm vào.

---

#### Cách 2 — Tạo Pull Request (dành cho dân Git)

**Bước 1 — Fork repo**

**Bước 2 — Chỉnh sửa file `README.md`**

Tìm đúng mục chữ cái, thêm nickname theo đúng format:

```markdown
<details>
<summary><strong>Tên</strong></summary>

- Tên nickname 1
- Tên nickname 2

</details>
```

> ⚠️ Giữ đúng thứ tự **alphabet**. Nếu tên đã có `<details>`, chỉ cần thêm dòng vào bên trong.

**Bước 3 — Commit & Push**
```bash
git add README.md
git commit -m "feat: thêm nickname cho [Tên] chữ [X]"
git push origin main
```

**Bước 4 — Tạo Pull Request**
```
Vào repo gốc → nhấn "Compare & pull request" → điền mô tả ngắn → Submit
```

**Bước 5 — Chờ review 🎉**

> PR sẽ được merge nếu đúng format và không vi phạm quy tắc nội dung.
