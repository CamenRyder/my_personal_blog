---
title: "Bài 2 -  Chương trình Java đầu tiên HelloWorld"
date: 2024-12-28T02:54:01+05:30
author: Minh Hiếu
description: Mô tả
tags:
  - log
---
<div class="md-contents" style="font-size: 18px; line-height: 1.75;"><h3 id="_1-moi-truong-va-ung-dung-de-lap-trinh-0">1. Môi trường và ứng dụng để lập trình</h3>
<p>Để có thể bắt đầu lập trình một ứng dụng bằng Java thì chúng ta cần cài đặt môi trường và một ứng dụng để lâp trình.</p>
<ul>
<li>Môi trường: đã có rất nhiều hướng dẫn trên mạng về hướng dẫn cài đặt, cấu hình và thiết lập biến môi trường cho Java nên mình sẽ không hướng dẫn nữa.</li>
<li>Ứng dụng: thật ra có rất nhiều ứng dụng để lập trình như Eclipse, IntelliJ, NetBeans, Visual Studio Code...., bạn cũng có thể dễ dàng tìm thấy cách cài đặt và sử dụng chúng trên internet.</li>
</ul>
<p>=&gt; Ở đây mình sẽ sử dụng IntelliJ trong quá trình hướng dẫn các bạn code.</p>
<h3 id="_2-tao-project-java-tren-intellj-idea-1">2. Tạo project Java trên Intellj IDEA</h3>
<ul>
<li>Mở Intellij IDEA và chọn New Project</li>
</ul>
<p><span class="progressive-img_capturer progressive-img_wrapper article-img-wrapper"><canvas class="progressive-img_tiny progressive-img_filter-blur article-img-tiny" width="1824" height="1424" style="background: url('https://images.viblo.asia/60/37d2d291-72ec-49b0-8d57-28312af83736.png') 100%/100%"></canvas><img class="progressive-img_full progressive-img_hidden article-img" width="1824" height="1424" data-full-src="https://images.viblo.asia/37d2d291-72ec-49b0-8d57-28312af83736.png" alt="image.png" data-tiny-src="https://images.viblo.asia/60/37d2d291-72ec-49b0-8d57-28312af83736.png" data-zoom-src="https://images.viblo.asia/full/37d2d291-72ec-49b0-8d57-28312af83736.png" data-srcset="https://images.viblo.asia/retina/37d2d291-72ec-49b0-8d57-28312af83736.png 2x" data-wrapper-class="article-img-wrapper" data-tiny-class="article-img-tiny" data-full-class="article-img"></span></p>

            <div style="position:relative" onclick="this.removeAttribute('class');this.querySelectorAll('.v-markdown-it-show-more').forEach(el => el.remove());" onmouseenter="this.getElementsByClassName('v-markdown-it-show-more')[0] ? this.getElementsByClassName('v-markdown-it-show-more')[0].style.display='block' : null" onmouseleave="this.getElementsByClassName('v-markdown-it-show-more')[0] ? this.getElementsByClassName('v-markdown-it-show-more')[0].style.display='none' : null">
                <pre><code>* Name: đặt tên cho project, ví dụ ở đây mình đặt là HelloWorld.
* Location: chọn nơi lưu project.
* Language: chọn ngôn ngữ bạn muốn lập trình, ở đây là Java.
</code></pre>

                <button class="v-markdown-it-code-copy" data-clipboard-text="* Name: đặt tên cho project, ví dụ ở đây mình đặt là HelloWorld.
* Location: chọn nơi lưu project.
* Language: chọn ngôn ngữ bạn muốn lập trình, ở đây là Java.
" delay="2000" title="Sao chép">
                    <span class="tooltiptext" style="display:none">Đã sao chép ✔️</span>
                    <span class="v-markdown-icon el-icon-document-copy"></span>
                </button>
                
            </div>
        <p><span class="progressive-img_capturer progressive-img_wrapper article-img-wrapper"><canvas class="progressive-img_tiny progressive-img_filter-blur article-img-tiny" width="1598" height="1242" style="background: url('https://images.viblo.asia/60/6f6eec71-fbc4-495d-9ea0-94aef5f2df7f.png') 100%/100%"></canvas><img class="progressive-img_full progressive-img_hidden article-img" width="1598" height="1242" data-full-src="https://images.viblo.asia/6f6eec71-fbc4-495d-9ea0-94aef5f2df7f.png" alt="Screen Shot 2022-08-04 at 11.54.41.png" data-tiny-src="https://images.viblo.asia/60/6f6eec71-fbc4-495d-9ea0-94aef5f2df7f.png" data-zoom-src="https://images.viblo.asia/full/6f6eec71-fbc4-495d-9ea0-94aef5f2df7f.png" data-srcset="https://images.viblo.asia/retina/6f6eec71-fbc4-495d-9ea0-94aef5f2df7f.png 2x" data-wrapper-class="article-img-wrapper" data-tiny-class="article-img-tiny" data-full-class="article-img"></span></p>
<ul>
<li>Kết quả Project HelloWorld được tạo ra với cấu trúc như sau:</li>
</ul>
<p><span class="progressive-img_capturer progressive-img_wrapper article-img-wrapper"><canvas class="progressive-img_tiny progressive-img_filter-blur article-img-tiny" width="2880" height="1800" style="background: url('https://images.viblo.asia/60/869449ce-f3c2-4ab0-a693-b4c74a720082.png') 100%/100%"></canvas><img class="progressive-img_full progressive-img_hidden article-img" width="2880" height="1800" data-full-src="https://images.viblo.asia/869449ce-f3c2-4ab0-a693-b4c74a720082.png" alt="Screen Shot 2022-08-04 at 13.04.01.png" data-tiny-src="https://images.viblo.asia/60/869449ce-f3c2-4ab0-a693-b4c74a720082.png" data-zoom-src="https://images.viblo.asia/full/869449ce-f3c2-4ab0-a693-b4c74a720082.png" data-srcset="https://images.viblo.asia/retina/869449ce-f3c2-4ab0-a693-b4c74a720082.png 2x" data-wrapper-class="article-img-wrapper" data-tiny-class="article-img-tiny" data-full-class="article-img"></span></p>
<ul>
<li>Tiếp theo, tạo Package. Click chuột phải vào folder src và chọn New -&gt; Package -&gt; nhập tên Package.</li>
<li>Tiếp theo, tạo file java cho project. Click chuột phải vào Package đã tạo và chọn New -&gt; Java Class -&gt; nhập tên class</li>
</ul>
<p><span class="progressive-img_capturer progressive-img_wrapper article-img-wrapper"><canvas class="progressive-img_tiny progressive-img_filter-blur article-img-tiny" width="2880" height="1800" style="background: url('https://images.viblo.asia/60/9dfdc3e0-007d-4000-96f7-015de12937cb.png') 100%/100%"></canvas><img class="progressive-img_full progressive-img_hidden article-img" width="2880" height="1800" data-full-src="https://images.viblo.asia/9dfdc3e0-007d-4000-96f7-015de12937cb.png" alt="Screen Shot 2022-08-04 at 13.12.51.png" data-tiny-src="https://images.viblo.asia/60/9dfdc3e0-007d-4000-96f7-015de12937cb.png" data-zoom-src="https://images.viblo.asia/full/9dfdc3e0-007d-4000-96f7-015de12937cb.png" data-srcset="https://images.viblo.asia/retina/9dfdc3e0-007d-4000-96f7-015de12937cb.png 2x" data-wrapper-class="article-img-wrapper" data-tiny-class="article-img-tiny" data-full-class="article-img"></span></p>
<p><span class="progressive-img_capturer progressive-img_wrapper article-img-wrapper"><canvas class="progressive-img_tiny progressive-img_filter-blur article-img-tiny" width="2880" height="1800" style="background: url('https://images.viblo.asia/60/77e41b02-93e2-4a20-853a-d488fb50a7d0.png') 100%/100%"></canvas><img class="progressive-img_full progressive-img_hidden article-img" width="2880" height="1800" data-full-src="https://images.viblo.asia/77e41b02-93e2-4a20-853a-d488fb50a7d0.png" alt="Screen Shot 2022-08-04 at 13.15.55.png" data-tiny-src="https://images.viblo.asia/60/77e41b02-93e2-4a20-853a-d488fb50a7d0.png" data-zoom-src="https://images.viblo.asia/full/77e41b02-93e2-4a20-853a-d488fb50a7d0.png" data-srcset="https://images.viblo.asia/retina/77e41b02-93e2-4a20-853a-d488fb50a7d0.png 2x" data-wrapper-class="article-img-wrapper" data-tiny-class="article-img-tiny" data-full-class="article-img"></span></p>
<ul>
<li>Để code của ta được thực thi sau khi run thì ta cần viết code bên trong hàm main.
<ul>
<li>public static void main(String[] args){...}: sẽ thực thi code bên trong nó.</li>
<li>System.out.println(""): dùng để in ra màn hình 1 chuỗi ký tự.</li>
</ul>
</li>
</ul>
<p><span class="progressive-img_capturer progressive-img_wrapper article-img-wrapper"><canvas class="progressive-img_tiny progressive-img_filter-blur article-img-tiny" width="890" height="406" style="background: url('https://images.viblo.asia/60/75694b3e-167d-4c59-8216-faeda596143f.png') 100%/100%"></canvas><img class="progressive-img_full progressive-img_hidden article-img" width="890" height="406" data-full-src="https://images.viblo.asia/75694b3e-167d-4c59-8216-faeda596143f.png" alt="Screen Shot 2022-08-04 at 13.18.40.png" data-tiny-src="https://images.viblo.asia/60/75694b3e-167d-4c59-8216-faeda596143f.png" data-zoom-src="https://images.viblo.asia/full/75694b3e-167d-4c59-8216-faeda596143f.png" data-srcset="https://images.viblo.asia/retina/75694b3e-167d-4c59-8216-faeda596143f.png 2x" data-wrapper-class="article-img-wrapper" data-tiny-class="article-img-tiny" data-full-class="article-img"></span></p>
<ul>
<li>Click vào nút run màu xanh để build code và được kết quả:</li>
</ul>
<p><span class="progressive-img_capturer progressive-img_wrapper article-img-wrapper"><canvas class="progressive-img_tiny progressive-img_filter-blur article-img-tiny" width="2880" height="1800" style="background: url('https://images.viblo.asia/60/29e8b4ad-f3fe-4723-871d-abfad4986ccf.png') 100%/100%"></canvas><img class="progressive-img_full progressive-img_hidden article-img" width="2880" height="1800" data-full-src="https://images.viblo.asia/29e8b4ad-f3fe-4723-871d-abfad4986ccf.png" alt="Screen Shot 2022-08-04 at 13.20.01.png" data-tiny-src="https://images.viblo.asia/60/29e8b4ad-f3fe-4723-871d-abfad4986ccf.png" data-zoom-src="https://images.viblo.asia/full/29e8b4ad-f3fe-4723-871d-abfad4986ccf.png" data-srcset="https://images.viblo.asia/retina/29e8b4ad-f3fe-4723-871d-abfad4986ccf.png 2x" data-wrapper-class="article-img-wrapper" data-tiny-class="article-img-tiny" data-full-class="article-img"></span></p>
<h3 id="_3-ket-2">3. Kết</h3>
<ul>
<li>Thông qua bài viết này bạn đã biết tạo ra một ứng dụng cơ bản nhất từ Java, cũng là tiền đề để bạn học thêm về Java.</li>
</ul>
</div>