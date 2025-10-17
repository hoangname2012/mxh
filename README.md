<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Dịch vụ Mạng Xã Hội</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0; padding: 0;
      background-color: #f8f9fa;
      color: #333;
    }
    header {
      background-color: #007bff;
      color: white;
      padding: 20px;
      text-align: center;
    }
    main {
      max-width: 800px;
      margin: 20px auto;
      padding: 0 15px;
    }
    h1, h2 {
      color: #007bff;
    }
    section {
      margin-bottom: 30px;
      background: white;
      padding: 20px;
      border-radius: 6px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 10px;
    }
    th, td {
      border: 1px solid #ddd;
      padding: 12px;
      text-align: center;
    }
    th {
      background-color: #007bff;
      color: white;
    }
    form {
      display: flex;
      flex-direction: column;
    }
    label {
      margin: 10px 0 5px;
    }
    input, select, textarea {
      padding: 10px;
      font-size: 1rem;
      border: 1px solid #ccc;
      border-radius: 4px;
      resize: vertical;
    }
    button {
      margin-top: 15px;
      padding: 12px;
      font-size: 1rem;
      background-color: #007bff;
      border: none;
      color: white;
      cursor: pointer;
      border-radius: 4px;
      transition: background-color 0.3s ease;
    }
    button:hover {
      background-color: #0056b3;
    }
    footer {
      text-align: center;
      padding: 15px;
      background: #f1f1f1;
      margin-top: 40px;
      font-size: 0.9rem;
      color: #666;
    }
  </style>
</head>
<body>

<header>
  <h1>Dịch vụ Mạng Xã Hội</h1>
  <p>Tăng like, follow, view chất lượng trên Facebook, Instagram, TikTok, YouTube...</p>
</header>

<main>

  <section>
    <h2>Giới thiệu dịch vụ</h2>
    <p>Chúng tôi cung cấp các dịch vụ giúp bạn phát triển thương hiệu và tăng tương tác trên các nền tảng mạng xã hội phổ biến như Facebook, Instagram, TikTok, YouTube, X (Twitter). Dịch vụ uy tín, nhanh chóng và bảo mật.</p>
  </section>

  <section>
    <h2>Bảng giá dịch vụ</h2>
    <table>
      <thead>
        <tr>
          <th>Dịch vụ</th>
          <th>Giá (VNĐ)</th>
          <th>Mô tả</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Tăng Like Facebook</td>
          <td>50,000 / 100 likes</td>
          <td>Like thật, tương tác cao</td>
        </tr>
        <tr>
          <td>Tăng Follow Instagram</td>
          <td>100,000 / 100 followers</td>
          <td>Follower chất lượng, an toàn</td>
        </tr>
        <tr>
          <td>Tăng View TikTok</td>
          <td>70,000 / 1,000 views</td>
          <td>View thật, tăng uy tín</td>
        </tr>
      </tbody>
    </table>
  </section>

  <section>
    <h2>Đặt dịch vụ</h2>
    <form id="orderForm">
      <label for="service">Chọn dịch vụ:</label>
      <select id="service" name="service" required>
        <option value="">-- Chọn dịch vụ --</option>
        <option value="like_fb">Tăng Like Facebook</option>
        <option value="follow_ig">Tăng Follow Instagram</option>
        <option value="view_tt">Tăng View TikTok</option>
      </select>

      <label for="link">Link bài viết / trang cá nhân:</label>
      <input type="url" id="link" name="link" placeholder="https://..." required />

      <label for="quantity">Số lượng:</label>
      <input type="number" id="quantity" name="quantity" min="1" placeholder="Nhập số lượng" required />

      <label for="note">Ghi chú (nếu có):</label>
      <textarea id="note" name="note" rows="3" placeholder="Ví dụ: ưu tiên nhanh"></textarea>

      <button type="submit">Gửi đơn hàng</button>
    </form>
  </section>

</main>

<footer>
  &copy; 2025 Dịch vụ Mạng Xã Hội. Liên hệ: info@dichvumangxahoi.vn
</footer>

<script>
  document.getElementById('orderForm').addEventListener('submit', function(e) {
    e.preventDefault();
    alert('Cảm ơn bạn đã gửi đơn hàng! Chúng tôi sẽ liên hệ lại sớm.');
    this.reset();
  });
</script>

</body>
</html>

