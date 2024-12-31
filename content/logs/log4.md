---
title: "Bài 4 - Các kiểu dữ liệu trong java"
date: 2024-12-28T02:54:01+05:30
author: Minh Hiếu
description: Mô tả
tags:
  - log
---
<div class="md-contents" style="font-size: 18px; line-height: 1.75;"><h3 id="_1-gioi-thieu-0">1. Giới thiệu</h3>
<ul>
<li>Trong Java, kiểu dữ liệu được chia thành hai loại:
<ul>
<li>Primitive: kiểu dữ liệu nguyên thủy</li>
<li>Non-primitive: kiểu dữ liệu đối tượng</li>
</ul>
</li>
<li>Trong bài này mình sẽ không đi chuyên sâu, mình chỉ muốn giới thiệu qua chúng để các bạn có một cái nhìn khái quát, trong quá trình học chúng ta sẽ hiểu rõ hơn về từng kiểu dữ liệu.</li>
</ul>
<h3 id="_2-primitive-kieu-du-lieu-nguyen-thuy-1">2. Primitive (kiểu dữ liệu nguyên thủy)</h3>
<ul>
<li>Primitive bao gồm các kiểu dữ liệu cơ bản sau:</li>
</ul>
<table>
<thead>
<tr>
<th>Kiểu dữ liệu</th>
<th>Mô tả</th>
</tr>
</thead>
<tbody>
<tr>
<td>byte</td>
<td>Dùng để lưu dữ liệu kiểu số nguyên có kích thước một byte (8 bít). Phạm vi biểu diễn giá trị từ -128 đến 127.</td>
</tr>
<tr>
<td>char</td>
<td>Dùng để lưu dữ liệu kiểu kí tự hoặc số nguyên không âm có kích thước 2 byte (16 bít). Phạm vi biểu diễn giá trị từ 0 đến u\ffff.</td>
</tr>
<tr>
<td>boolean</td>
<td>Dùng để lưu dữ liệu chỉ có hai trạng thái đúng hoặc sai (độ lớn chỉ có 1 bít). Phạm vi biểu diễn giá trị là {“True”, “False”}.</td>
</tr>
<tr>
<td>short</td>
<td>Dùng để lưu dữ liệu có kiểu số nguyên, kích cỡ 2 byte (16 bít). Phạm vi biểu diễn giá trị từ - 32768 đến 32767.</td>
</tr>
<tr>
<td>int</td>
<td>Dùng để lưu dữ liệu có kiểu số nguyên, kích cỡ 4 byte (32 bít). Phạm vi biểu diễn giá trị từ -2,147,483,648 đến 2,147,483,647.</td>
</tr>
<tr>
<td>long</td>
<td>Dùng để lưu dữ liệu có kiểu số nguyên có kích thước lên đến 8 byte.</td>
</tr>
<tr>
<td>float</td>
<td>Dùng để lưu dữ liệu có kiểu số thực, kích cỡ 4 byte (32 bít).</td>
</tr>
<tr>
<td>double</td>
<td>Dùng để lưu dữ liệu có kiểu số thực có kích thước lên đến 8 byte.</td>
</tr>
</tbody>
</table>
<h3 id="_3-non---primitive-kieu-du-lieu-doi-tuong-2">3. Non - Primitive (kiểu dữ liệu đối tượng)</h3>
<ul>
<li>Trong java có 3 kiểu dữ liệu đối tượng:</li>
</ul>
<table>
<thead>
<tr>
<th>Kiểu dữ liệu</th>
<th>Mô tả</th>
</tr>
</thead>
<tbody>
<tr>
<td>Array</td>
<td>Một mảng của các dữ liệu cùng kiểu.</td>
</tr>
<tr>
<td>Class</td>
<td>Dữ liệu kiểu lớp đối tượng do người dùng định nghĩa. Chứa tập các thuộc tính và phương thức.</td>
</tr>
<tr>
<td>Interface</td>
<td>Dữ liệu kiểu lớp giao tiếp do người dùng định nghĩa. Chứa các phương thức của giao tiếp.</td>
</tr>
</tbody>
</table>
</div>