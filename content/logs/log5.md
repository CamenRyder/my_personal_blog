---
title: "Bài 5 - Biến và hằng số trong Java"
date: 2024-12-28T02:54:01+05:30
author: Minh Hiếu
description: Mô tả
tags:
  - log
---
<div class="article-content__body my-2 flex-fill"><div class="md-contents" style="font-size: 18px; line-height: 1.75;"><h3 id="_1-gioi-thieu-0">1. Giới thiệu.</h3>
<ul>
<li>Trong bài này, chúng ta sẽ tìm hiểu về hai khái niệm quan trọng khác đó là: biến (Variable) và hằng số (Constant) trong Java.</li>
</ul>
<h3 id="_2-variable-bien-1">2. Variable (Biến)</h3>
<h4>2.1 Khái niệm</h4>
<ul>
<li>
<p>Biến là tên gọi của một vùng nhớ dùng để lưu trữ giá trị mà chương trình của chúng ta cần sử dụng.</p>
</li>
<li>
<p>Mỗi biến trong Java bao gồm 3 phần sau: tên biến, kiểu dữ liệu và giá trị.</p>
<ul>
<li>Tên biến: là do bạn đặt và bạn nên đặt làm sao cho ngắn gọn, khái quát lên được ý nghĩa của biến đó.</li>
<li>Kiểu dữ liệu: dùng để xác định kích thước và loại giá trị có thể được lưu trữ.</li>
<li>Giá trị: là dữ liệu thực tế được lưu trữ trên biến và có thể thay đổi được.</li>
</ul>
</li>
<li>
<p>Trong Java có 3 loại biến thường gặp:</p>
<ul>
<li>Local variable (biến cục bộ),</li>
<li>Instance variable (thuộc tính)</li>
<li>Static variable (biến tĩnh)</li>
</ul>
</li>
<li>
<p>Có 2 cách khai báo biến trong Java:</p>
<ul>
<li>Cách 1: <code>[kiểu_dữ_liệu] [tên_biến];</code></li>
</ul>

            <div style="position:relative" onclick="this.removeAttribute('class');this.querySelectorAll('.v-markdown-it-show-more').forEach(el => el.remove());" onmouseenter="this.getElementsByClassName('v-markdown-it-show-more')[0] ? this.getElementsByClassName('v-markdown-it-show-more')[0].style.display='block' : null" onmouseleave="this.getElementsByClassName('v-markdown-it-show-more')[0] ? this.getElementsByClassName('v-markdown-it-show-more')[0].style.display='none' : null">
                <pre class="language-none" data-filename=""><code class="language-none">int age;
String fistName;
String lastName;
</code></pre>

                <button class="v-markdown-it-code-copy" data-clipboard-text="int age;
String fistName;
String lastName;
" delay="2000" title="Sao chép">
                    <span class="tooltiptext" style="display:none">Đã sao chép ✔️</span>
                    <span class="v-markdown-icon el-icon-document-copy"></span>
                </button>
                
            </div>
        <ul>
<li>Cách 2: <code>[kiểu_dữ_liệu] [tên_biến] = [giá_trị];</code></li>
</ul>

            <div style="position:relative" onclick="this.removeAttribute('class');this.querySelectorAll('.v-markdown-it-show-more').forEach(el => el.remove());" onmouseenter="this.getElementsByClassName('v-markdown-it-show-more')[0] ? this.getElementsByClassName('v-markdown-it-show-more')[0].style.display='block' : null" onmouseleave="this.getElementsByClassName('v-markdown-it-show-more')[0] ? this.getElementsByClassName('v-markdown-it-show-more')[0].style.display='none' : null">
                <pre class="language-none" data-filename=""><code class="language-none">int age = 20;
String fistName = "A"
String lastName = "Nguyễn Văn"
</code></pre>

                <button class="v-markdown-it-code-copy" data-clipboard-text="int age = 20;
String fistName = &quot;A&quot;
String lastName = &quot;Nguyễn Văn&quot;
" delay="2000" title="Sao chép">
                    <span class="tooltiptext" style="display:none">Đã sao chép ✔️</span>
                    <span class="v-markdown-icon el-icon-document-copy"></span>
                </button>
                
            </div>
        </li>
</ul>
<h4>2.2 Local variable (biến cục bộ).</h4>
<ul>
<li>Local variable được khai báo trong các phương thức, hàm contructor hoặc trong các block.</li>
<li>Biến cục bộ được tạo bên trong các phương thức, contructor, block và sẽ bị hủy khi kết thúc các phương thức, contructor và block.</li>
<li>Không được sử dụng “access modifier” khi khai báo biến cục bộ.</li>
<li>Các biến cục bộ sẽ nằm trên vùng bộ nhớ stack của bộ nhớ.</li>
<li>Bạn cần khởi tạo giá trị mặc định cho biến cục bộ trước khi có thể sử dụng.</li>
</ul>
<p><span class="progressive-img_capturer progressive-img_wrapper article-img-wrapper"><canvas class="progressive-img_tiny progressive-img_filter-blur article-img-tiny" width="1808" height="926" style="background: url('https://images.viblo.asia/60/5d4bcf8a-d934-45d4-9ad7-1f5f8226d534.png') 100%/100%"></canvas><img class="progressive-img_full progressive-img_hidden article-img" width="1808" height="926" data-full-src="https://images.viblo.asia/5d4bcf8a-d934-45d4-9ad7-1f5f8226d534.png" alt="Screen Shot 2022-08-06 at 15.00.01.png" data-tiny-src="https://images.viblo.asia/60/5d4bcf8a-d934-45d4-9ad7-1f5f8226d534.png" data-zoom-src="https://images.viblo.asia/full/5d4bcf8a-d934-45d4-9ad7-1f5f8226d534.png" data-srcset="https://images.viblo.asia/retina/5d4bcf8a-d934-45d4-9ad7-1f5f8226d534.png 2x" data-wrapper-class="article-img-wrapper" data-tiny-class="article-img-tiny" data-full-class="article-img"></span></p>
<h4>2.3 Instance variable (biến toàn cục).</h4>
<ul>
<li>Biến instance được khai báo trong một lớp(class), bên ngoài các phương thức, constructor và các block.</li>
<li>Biến instance được lưu trong bộ nhớ heap.</li>
<li>Biến instance được tạo khi một đối tượng được tạo bằng việc sử dụng từ khóa “new” và sẽ bị phá hủy khi đối tượng bị phá hủy.</li>
<li>Biến instance có thể được sử dụng bởi các phương thức, constructor, block, ... Nhưng nó phải được sử dụng thông qua một đối tượng cụ thể.</li>
<li>Được phép sử dụng "access modifier" khi khai báo biến instance, mặc định là "default".</li>
<li>Biến instance có giá trị mặc định phụ thuộc vào kiểu dữ liệu của nó. Ví dụ nếu là kiểu int, short, byte thì giá trị mặc định là 0, kiểu double thì là 0.0d, ... Vì vậy, bạn sẽ không cần khởi tạo giá trị cho biến instance trước khi sử dụng.</li>
<li>Bên trong class mà bạn khai báo biến instance, bạn có thể gọi nó trực tiếp bằng tên khi sử dụng ở khắp nơi bên trong class đó.</li>
</ul>
<p><span class="progressive-img_capturer progressive-img_wrapper article-img-wrapper"><canvas class="progressive-img_tiny progressive-img_filter-blur article-img-tiny" width="1586" height="1602" style="background: url('https://images.viblo.asia/60/e74327fd-9cf4-4358-8102-033297d36dae.png') 100%/100%"></canvas><img class="progressive-img_full progressive-img_hidden article-img" width="1586" height="1602" data-full-src="https://images.viblo.asia/e74327fd-9cf4-4358-8102-033297d36dae.png" alt="Screen Shot 2022-08-06 at 15.11.41.png" data-tiny-src="https://images.viblo.asia/60/e74327fd-9cf4-4358-8102-033297d36dae.png" data-zoom-src="https://images.viblo.asia/full/e74327fd-9cf4-4358-8102-033297d36dae.png" data-srcset="https://images.viblo.asia/retina/e74327fd-9cf4-4358-8102-033297d36dae.png 2x" data-wrapper-class="article-img-wrapper" data-tiny-class="article-img-tiny" data-full-class="article-img"></span></p>
<h4>2.4 Static variable (biến tĩnh).</h4>
<ul>
<li>Biến static được khai báo trong một class với từ khóa "static", phía bên ngoài các phương thức, constructor và block.</li>
<li>Sẽ chỉ có duy nhất một bản sao của các biến static được tạo ra, dù bạn tạo bao nhiêu đối tượng từ lớp tương ứng.</li>
<li>Biến static được lưu trữ trong bộ nhớ static riêng.</li>
<li>Biến static được tạo khi chương trình bắt đầu chạy và chỉ bị hủy khi chương trình dừng.</li>
<li>Giá trị mặc định của biến static phụ thuộc vào kiểu dữ liệu bạn khai báo tương tự biến instance.</li>
<li>Biến static được truy cập thông qua tên của class chứa nó, với cú pháp: TenClass.tenBien.</li>
<li>Trong class, các phương thức sử dụng biến static bằng cách gọi tên của nó khi phương thức đó cũng được khai báo với từ khóa "static".</li>
</ul>
<p><span class="progressive-img_capturer progressive-img_wrapper article-img-wrapper"><canvas class="progressive-img_tiny progressive-img_filter-blur article-img-tiny" width="1378" height="1016" style="background: url('https://images.viblo.asia/60/7fbf22e1-da29-40c3-ab0a-2954db2fc0b0.png') 100%/100%"></canvas><img class="progressive-img_full progressive-img_hidden article-img" width="1378" height="1016" data-full-src="https://images.viblo.asia/7fbf22e1-da29-40c3-ab0a-2954db2fc0b0.png" alt="Screen Shot 2022-08-06 at 15.16.34.png" data-tiny-src="https://images.viblo.asia/60/7fbf22e1-da29-40c3-ab0a-2954db2fc0b0.png" data-zoom-src="https://images.viblo.asia/full/7fbf22e1-da29-40c3-ab0a-2954db2fc0b0.png" data-srcset="https://images.viblo.asia/retina/7fbf22e1-da29-40c3-ab0a-2954db2fc0b0.png 2x" data-wrapper-class="article-img-wrapper" data-tiny-class="article-img-tiny" data-full-class="article-img"></span></p>
<h3 id="_3-constant-hang-so-2">3. Constant (hằng số).</h3>
<ul>
<li>Hằng số là những giá trị không bao giờ thay đổi trong suốt quá trình sử dụng, là một giá trị bất biến trong chương trình.</li>
<li>Nếu bạn cố ý thay đổi giá trị của Constant thì sẽ xảy ra lỗi.</li>
</ul>
<p><span class="progressive-img_capturer progressive-img_wrapper article-img-wrapper"><canvas class="progressive-img_tiny progressive-img_filter-blur article-img-tiny" width="1390" height="922" style="background: url('https://images.viblo.asia/60/34fb37ce-81fe-459d-99c1-07e836207f90.png') 100%/100%"></canvas><img class="progressive-img_full progressive-img_hidden article-img" width="1390" height="922" data-full-src="https://images.viblo.asia/34fb37ce-81fe-459d-99c1-07e836207f90.png" alt="Screen Shot 2022-08-06 at 15.27.36.png" data-tiny-src="https://images.viblo.asia/60/34fb37ce-81fe-459d-99c1-07e836207f90.png" data-zoom-src="https://images.viblo.asia/full/34fb37ce-81fe-459d-99c1-07e836207f90.png" data-srcset="https://images.viblo.asia/retina/34fb37ce-81fe-459d-99c1-07e836207f90.png 2x" data-wrapper-class="article-img-wrapper" data-tiny-class="article-img-tiny" data-full-class="article-img"></span></p>
</div> <!----></div>