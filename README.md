# webnhom2TT.github
<head>
    <title>Vận dụng 1 bài 12</title>
  </head>
  <body>
    <h1>Đăng kí thành viên câu lạc bộ ngoại khóa</h1>
    <form action="bieumau.html" method="post">
      <fieldset>
        <legend>ĐĂNG KÍ CÂU LẠC BỘ NGOẠI KHÓA TRƯỜNG NGUYỄN BỈNH KHIÊM</legend>
        <p>Vui lòng nhập đầy đủ thông tin để đăng kí thành viên của CLB</p>
        <ol>
          <li>
            <label for="fullname">Họ và tên:</label>
            <br />
            <input type="text" name="fullname" id="fullname" size="30" />
          </li>
          <li>
            <label for="class">Lớp: </label>
            <br />
            <input type="text" name="class" list="class" />
            <datalist id="class">
              <option value="10A">10A</option>
              <option value="10B">10B</option>
              <option value="10C">10C</option>
              <option value="100">100</option>
              <option value="10E">10E</option>
            </datalist>
          </li>
          <li>
            <label for="email">Email:</label>
            <br />
            <input type="text" name="email" id="email" size="30" />
          </li>
          <li>
            <label for="club">Lựa chọn CLB đăng kí: </label>
            <select name="club" id="club">
              <option value="football">CLB Bóng đá</option>
              <option value="volleyball">CLB Bóng chuyền</option>
              <option value="basketball">CLB Bóng rổ</option>
              <option value="karatedo">CLB Karatedo</option>
            </select>
          </li>
        </ol>
        <input type="submit" value="Đăng kí" />
      </fieldset>
    </form>
  </body>
</html>
