---
title: "Bài 6 - Các toán tử thường dùng trong Java"
date: 2024-12-28T02:54:01+05:30
author: Minh Hiếu
description: Mô tả
tags:
  - log
---

<div class="post-body__main post-content"><article class="post-content">
        <div class="d-md-flex align-items-top justify-content-between"><div data-v-4365a2a0="" class="tags d-flex flex-wrap align-items-center">  </div> <div class="post__menu"><div class="el-dropdown"><button type="button" class="el-button p-0 el-button--text text-muted el-dropdown-selfdefine" data-tippy="" data-original-title="Hiển thị các hành động" aria-haspopup="list" aria-controls="dropdown-menu-6781" role="button" tabindex="0"><!----><i class="post__menu__more el-icon-more-outline"></i><!----></button> <ul class="el-dropdown-menu el-popper el-dropdown-menu--medium" id="dropdown-menu-6781" style="display: none;"><!----> <li tabindex="-1" class="el-dropdown-menu__item"><!----><i aria-hidden="true" class="fa fa-flag-o pr-0 mr-05"></i>
                Báo cáo
            </li> <li tabindex="-1" class="el-dropdown-menu__item"><!----><i aria-hidden="true" class="fa fa-plus-square-o pr-0 mr-05"></i>
                Thêm vào series của tôi
            </li> <!----> <!----> <!----> <!----> <!----> <!----></ul></div> <!----> <!----> <!----> <!----> <!----></div></div> <!----> <div><div role="alert" class="el-alert mt-1 el-alert--warning is-light"><i class="el-alert__icon el-icon-warning is-big"></i><div class="el-alert__content"><!----><p class="el-alert__description">
            Bài đăng này đã không được cập nhật trong 2 năm
        </p><!----><i class="el-alert__closebtn el-icon-close"></i></div></div></div> <div class="article-content__body my-2 flex-fill"><div class="md-contents" style="font-size: 18px; line-height: 1.75;"><ul>
<li>Nhằm giúp các bạn dễ hiểu và không bị rối thì ở bài viết này mình sẽ chỉ giới thiệu cho các bạn một số toán tử thường dùng và phổ biến.</li>
</ul>
<h3 id="_1-toan-tu-so-hoc-0">1. Toán tử số học</h3>
<ul>
<li>Các toán tử số học được sử dụng trong các biểu thức toán học theo cách tương tự như chúng được sử dụng trong đại số học.</li>
</ul>
<table>
<thead>
<tr>
<th>Toán tử</th>
<th>Tên</th>
<th>Mô tả</th>
</tr>
</thead>
<tbody>
<tr>
<td>+</td>
<td>Cộng</td>
<td>Là tổng của hai toán hạng</td>
</tr>
<tr>
<td>-</td>
<td>Trừ</td>
<td>Là hiệu của hai toán hạng.</td>
</tr>
<tr>
<td>*</td>
<td>Nhân</td>
<td>Là tích của hai toán hạng.</td>
</tr>
<tr>
<td>/</td>
<td>Chia</td>
<td>Là thương của phép chia.</td>
</tr>
<tr>
<td>%</td>
<td>Phép chia lấy dư</td>
<td>Giá trị trả về là phần dư của phép chia</td>
</tr>
<tr>
<td>++</td>
<td>Tăng dần</td>
<td>Tăng giá trị của biến lên 1. <code>a++ &lt;=&gt; a = a + 1</code></td>
</tr>
<tr>
<td>--</td>
<td>Giảm dần</td>
<td>Giảm giá trị của biến 1 đơn vị. <code>a-- &lt;=&gt; a = a - 1</code></td>
</tr>
<tr>
<td>+=</td>
<td>Cộng và gán giá trị</td>
<td>Cộng các giá trị của toán hạng bên trái vào toán hạng bên phải và gán giá trị trả về vào toán hạng bên trái. <code>c+=a &lt;=&gt; c = c + a</code></td>
</tr>
<tr>
<td>-=</td>
<td>Trừ và gán giá trị</td>
<td>Trừ các giá trị của toán hạng bên trái vào toán toán hạng bên phải và gán giá trị trả về vào toán hạng bên trái. <code>c-=a &lt;=&gt; c = c - a</code></td>
</tr>
<tr>
<td>*=</td>
<td>Nhân và gán</td>
<td>Nhân các giá trị của toán hạng bên trái với toán toán hạng bên phải và gán giá trị trả về vào toán hạng bên trái. <code>c*=a &lt;=&gt; c = c*a</code></td>
</tr>
<tr>
<td>/=</td>
<td>Chia và gán</td>
<td>Chia giá trị của toán hạng bên trái cho toán toán hạng bên phải và gán giá trị trả về vào toán hạng bên trái. <code>c/=a &lt;=&gt; c = c/a</code></td>
</tr>
<tr>
<td>%=</td>
<td>Lấy số dư và gán</td>
<td>Chia giá trị của toán hạng bên trái cho toán toán hạng bên phải và gán giá trị số dư vào toán hạng bên trái. <code>c%=a &lt;=&gt; c = c%a</code></td>
</tr>
</tbody>
</table>
<h3 id="_2-toan-tu-quan-he-1">2. Toán tử quan hệ</h3>
<ul>
<li>Các toán tử quan hệ được sử dụng kiểm tra mối quan hệ giữa hai toán hạng.</li>
</ul>
<table>
<thead>
<tr>
<th>Toán tử</th>
<th>Tên</th>
<th>Mô tả</th>
</tr>
</thead>
<tbody>
<tr>
<td>==</td>
<td>So sánh bằng</td>
<td>Toán tử này kiểm tra sự tương đương của hai toán hạng</td>
</tr>
<tr>
<td>!=</td>
<td>So sánh khác</td>
<td>Toán tử này kiểm tra sự khác nhau của hai toán hạng</td>
</tr>
<tr>
<td>&gt;</td>
<td>Lớn hơn</td>
<td>Kiểm tra giá trị của toán hạng bên phải lớn hơn toán hạng bên trái hay không</td>
</tr>
<tr>
<td>&lt;</td>
<td>Nhỏ hơn</td>
<td>Kiểm tra giá trị của toán hạng bên phải có nhỏ hơn toán hạng bên trái hay không</td>
</tr>
<tr>
<td>&gt;=</td>
<td>Lớn hơn hoặc bằng</td>
<td>Kiểm tra giá trị của toán hạng bên phải có lớn hơn hoặc bằng toán hạng bên trái hay không</td>
</tr>
<tr>
<td>&lt;=</td>
<td>Nhỏ hơn hoặc bằng</td>
<td>Kiểm tra giá trị của toán hạng bên phải có nhỏ hơn hoặc bằng toán hạng bên trái hay không</td>
</tr>
</tbody>
</table>
<h3 id="_3-toan-tu-logic-trong-java-2">3. Toán tử logic trong Java</h3>
<ul>
<li>Các toán tử logic làm việc với các toán hạng Boolean. Các toán tử quan hệ được sử dụng trong các cấu trúc điều khiển.</li>
</ul>
<table>
<thead>
<tr>
<th>Toán tử</th>
<th>Tên</th>
<th>Mô tả</th>
</tr>
</thead>
<tbody>
<tr>
<td>&amp;&amp;</td>
<td>Toán tử và (AND)</td>
<td>Trả về một giá trị “Đúng” (True) nếu chỉ khi cả hai toán tử có giá trị “True”</td>
</tr>
<tr>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td>^</td>
<td>Toán tử XOR</td>
<td>Trả về giá trị True nếu và chỉ nếu chỉ một trong các giá trị là True, các trường hợp còn lại cho giá trị False (sai)</td>
</tr>
<tr>
<td>!</td>
<td>Toán tử phủ định (NOT)</td>
<td>Toán hạng đơn tử NOT. Chuyển giá trị từ True sang False và ngược lại.</td>
</tr>
</tbody>
</table>
<h3 id="_4-thu-tu-uu-tien-cua-cac-toan-tu-3">4. Thứ tự ưu tiên của các toán tử</h3>
<ul>
<li>Thứ tự ưu tiên quyết định trật tự thực hiện các toán tử trên các biểu thức.</li>
</ul>
<table>
<thead>
<tr>
<th>Thứ tự</th>
<th>Mô tả</th>
</tr>
</thead>
<tbody>
<tr>
<td>1</td>
<td>Các toán tử đơn như +,-,++,--</td>
</tr>
<tr>
<td>2</td>
<td>Các toán tử số học và các toán tử dịch như *,/,+,-,&lt;&lt;,&gt;&gt;</td>
</tr>
<tr>
<td>3</td>
<td>Các toán tử quan hệ như &gt;,&lt;,&gt;=,&lt;=,= =,!=</td>
</tr>
<tr>
<td>4</td>
<td>Các toán tử logic và Bit như &amp;&amp;,</td>
</tr>
<tr>
<td>5</td>
<td>Các toán tử gán như =,*=,/=,+=,-=</td>
</tr>
</tbody>
</table>
<h3 id="_5-thay-doi-thu-tu-uu-tien-cua-cac-toan-tu-4">5. Thay đổi thứ tự ưu tiên của các toán tử</h3>
<ul>
<li>Để thay đổi thứ tự ưu tiên trên một biểu thức, bạn có thể sử dụng dấu ngoặc đơn ():
<ul>
<li>Phần trong ngoặc đơn được thực hiện trước.</li>
<li>Nếu dùng nhiều ngoặc đơn lồng nhau thì toán tử nằm trong ngoặc đơn phía trong sẽ thực thi trước, sau đó đến các vòng phía ngoài.</li>
<li>Trong phạm vi một cặp ngoặc đơn thì quy tắc thứ tự ưu tiên vẫn giữ nguyên tác dụng.</li>
</ul>
</li>
</ul>
</div> <!----></div> <!----> <div data-v-4365a2a0="" class="tags d-flex flex-wrap align-items-center"> <a data-v-19d5ce29="" data-v-4365a2a0="" href="/tags/java-core" class="el-tag tag el-tag--info el-tag--medium">
        java core
    </a><a data-v-19d5ce29="" data-v-4365a2a0="" href="/tags/java" class="el-tag tag el-tag--info el-tag--medium">
        Java
    </a> </div> <br> <p title="People cannot distribute, remix, adapt, and build upon this workwithout author's permission (or as permitted by fair use)." class="license-text text-muted">
    All rights reserved
</p> <div class="post-footer d-flex align-items-center justify-content-end mb-2"><div data-v-235dd1c0="" class="social-sharing mr-1 social-sharing--vertical social-sharing--medium"><a data-v-235dd1c0="" tooltip-placement="bottom" rel="noopener" class="link link--muted link--muted" data-tippy="" data-original-title="Chia sẻ liên kết đến trang này trên Facebook"><i data-v-235dd1c0="" aria-hidden="true" class="fa fa-facebook"></i></a> <a data-v-235dd1c0="" tooltip-placement="bottom" rel="noopener" class="link link--muted link--muted" data-tippy="" data-original-title="Chia sẻ liên kết đến trang này trên Twitter"><i data-v-235dd1c0="" aria-hidden="true" class="fa fa-twitter"></i></a></div> <div class="post__menu"><div class="el-dropdown"><button type="button" class="el-button p-0 el-button--text text-muted el-dropdown-selfdefine" data-tippy="" data-original-title="Hiển thị các hành động" aria-haspopup="list" aria-controls="dropdown-menu-654" role="button" tabindex="0"><!----><i class="post__menu__more el-icon-more-outline"></i><!----></button> <ul class="el-dropdown-menu el-popper el-dropdown-menu--medium" id="dropdown-menu-654" style="display: none;"><!----> <li tabindex="-1" class="el-dropdown-menu__item"><!----><i aria-hidden="true" class="fa fa-flag-o pr-0 mr-05"></i>
                Báo cáo
            </li> <li tabindex="-1" class="el-dropdown-menu__item"><!----><i aria-hidden="true" class="fa fa-plus-square-o pr-0 mr-05"></i>
                Thêm vào series của tôi
            </li> <!----> <!----> <!----> <!----> <!----> <!----></ul></div> <!----> <!----> <!----> <!----> <!----></div></div></article></div>
