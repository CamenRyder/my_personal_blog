---
title: Bài viết 1 - Giới thiệu về ngôn ngữ Java
date: 2024-12-28
author: Minh Hiếu
description: mô tả
tags:
  - log
---

<h1 class="article-content__title">
            Giới thiệu về ngôn ngữ Java
        </h1>
<div class="md-contents" style="font-size: 18px; line-height: 1.75;"><p>

<span class="progressive-img_capturer progressive-img_wrapper article-img-wrapper"><canvas class="progressive-img_tiny progressive-img_filter-blur article-img-tiny progressive-img_hidden" width="573" height="403" style="background: url('https://images.viblo.asia/60/2cba74bc-ede4-41e8-b957-240206f2e979.png') 100%/100%"></canvas><img class="progressive-img_full article-img" width="573" height="403" data-full-src="https://images.viblo.asia/2cba74bc-ede4-41e8-b957-240206f2e979.png" alt="image.png" data-tiny-src="https://images.viblo.asia/60/2cba74bc-ede4-41e8-b957-240206f2e979.png" data-zoom-src="https://images.viblo.asia/full/2cba74bc-ede4-41e8-b957-240206f2e979.png" data-srcset="https://images.viblo.asia/retina/2cba74bc-ede4-41e8-b957-240206f2e979.png 2x" data-wrapper-class="article-img-wrapper" data-tiny-class="article-img-tiny" data-full-class="article-img" src="https://images.viblo.asia/2cba74bc-ede4-41e8-b957-240206f2e979.png"></span>


</p>
<h3 id="_1-java-la-gi--0">1. Java là gì ?</h3>
<ul>
<li>Rất đơn giản, Java là một ngôn ngữ lập trình, để lập trình các ứng dụng (web app, android app...)</li>
<li>Java được phát triển bởi Sun Microsystem vào năm 1995.</li>
<li>Java là ngôn ngữ lập trình hướng đối tượng.</li>
</ul>
<h3 id="_2-java-duoc-su-dung-de-lam-gi--1">2. Java được sử dụng để làm gì ?</h3>
<ul>
<li>Lập trình các ứng dụng cho các thiết bị android (android app): ứng dụng trên điện thoại di động, máy tính bảng..., thiết bị sử dụng hệ điều hành android</li>
<li>Lập trình các ứng dụng web (web app): có thể một trong những trang web bạn truy cập hằng ngày được lập trình bằng Java.</li>
<li>Lập trình các ứng dụng trên hệ điều hành window (win app): ứng dụng trên máy tính, thiết bị sử dụng hệ điều hành microsoft window.</li>
<li>Phát triển nhiều loại ứng dụng khác nhau: Cơ sở dữ liệu, mạng, Internet, viễn thông, giải trí,...</li>
</ul>
<h3 id="_3-dac-diem-co-ban-cua-java-2">3. Đặc điểm cơ bản của Java</h3>
<h4>3.1 Java là ngôn ngữ lập trình hướng đối tượng.</h4>
<ul>
<li>Mọi thực thể trong chương trình đều là một đối tượng (1 class xác định)</li>
<li>Các biến, hàm đều nằm trong một class nào đó</li>
</ul>
<h4>3.2 Đơn giản</h4>
<ul>
<li>Loại bỏ con trỏ</li>
<li>Loại bỏ lệnh goto</li>
<li>Không cho phép đa kế thừa (chuyển sang sử dụng interface)</li>
</ul>
<h4>3.3 Độc lập nền</h4>
<ul>
<li>Khác với các ngôn ngữ lập trình khác, thay vì biên dịch mã nguồn thành mã máy hoặc thông dịch mã nguồn khi chạy, Java được thiết kế để biên dịch mã nguồn thành bytecode, bytecode sau đó sẽ được môi trường thực thi (runtime environment).
=&gt; Do đó một chương trình viết bằng Java có thể chạy trên nhiều thiết bị, nhiều hệ điều hành khác nhau, với điều kiện ở đó có cài sẵn máy ảo Java.</li>
</ul>
<h4>3.4 Mạnh mẽ</h4>
<ul>
<li>Quá trình cấp phát, giải phóng bộ nhớ được thực hiện tự động.</li>
<li>Yêu cầu chặt chẽ khi khai báo dữ liệu, ép kiểu dữ liệu.</li>
<li>Tự động phát hiện lỗi lúc biên dịch.</li>
<li>Không sử dụng con trỏ hoặc các phép toán con trỏ.</li>
</ul>
<h4>3.5 Đa nhiệm</h4>
<ul>
<li>Java hỗ trợ lập trình đa luồng (multithreading): cho phép hoạt động đa tiến trình, tiểu trình có thể chạy song song cùng một thời điểm và có thể tương tác với nhau.</li>
</ul>
<h4>3.6 Cơ chế thu gom rác tự động</h4>
<ul>
<li>Khi các đối tượng được tạo ra trong Java, chúng sẽ được JRE  tự động cấp phát không gian bộ nhớ cho các đối tượng trên heap.</li>
</ul>
<h4>3.7 Tính an toàn và bảo mật</h4>
<h5>3.7.1 Tính an toàn</h5>
<ul>
<li>Ngôn ngữ lập trình Java yêu cầu chặt chẽ về kiểu dữ liệu.</li>
<li>Dữ liệu phải được khai báo tường minh.</li>
<li>Không sử dụng con trỏ và các phép toán với con trỏ.</li>
<li>Java kiểm soát chặt chẽ việc truy nhập đến mảng, chuỗi. Không cho phép sử dụng các kỹ thuật tràn. Do đó các truy nhập sẽ không vượt quá kích thước của mảng hoặc chuỗi.</li>
<li>Quá trình cấp phát và giải phóng bộ nhớ được thực hiện tự động.</li>
<li>Cơ chế xử lý lỗi giúp việc xử lý và phục hồi lỗi dễ dàng hơn.</li>
</ul>
<h5>3.7.2 Tính bảo mật</h5>
<p>Java cung cấp một môi trường quản lý chương trình với nhiều mức khác nhau:</p>
<ul>
<li>Mức 1 : Chỉ có thể truy xuất dữ liệu cũng như phương phức thông qua giao diện mà lớp cung cấp.</li>
<li>Mức 2 : Trình biên dịch kiểm soát các đoạn mã sao cho tuân thủ các quy tắc của ngôn ngữ lập trình Java trước khi thông dịch.</li>
<li>Mức 3 : Trình thông dịch sẽ kiểm tra mã byte code xem các đoạn mã này có đảm bảo được các quy định, quy tắc trước khi thực thi.</li>
<li>Mức 4: Java kiểm soát việc nạp các lớp vào bộ nhớ để giám sát việc vi phạm giới hạn truy xuất trước khi nạp vào hệ thống.</li>
</ul>
<h3 id="_4-cac-thanh-phan-cua-java-se-platform-3">4. Các thành phần của Java SE Platform</h3>
<p>Java Platform gồm có 3 thành phần chính:</p>
<ul>
<li>Java Virtual Machine (Java VM): Máy ảo Java.</li>
<li>Java Application Programming Interface (Java API).</li>
<li>Java Development Kit (JDK) gồm trình biên dịch, thông dịch, trợ giúp, soạn tài liệu... và các thư viện chuẩn.</li>
</ul>
</div>
