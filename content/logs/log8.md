---
title: "Bài 8 - Vòng lặp for trong java"
date: 2024-12-28T02:54:01+05:30
author: Minh Hiếu
description: Mô tả
tags:
  - log
---
<article class="post-content"> <div class="d-md-flex align-items-top justify-content-between"><div data-v-4365a2a0="" class="tags d-flex flex-wrap align-items-center">  </div> <div class="post__menu"><div class="el-dropdown"><button type="button" class="el-button p-0 el-button--text text-muted el-dropdown-selfdefine" data-tippy="" data-original-title="Hiển thị các hành động" aria-haspopup="list" aria-controls="dropdown-menu-3294" role="button" tabindex="0"><!----><i class="post__menu__more el-icon-more-outline"></i><!----></button> <ul class="el-dropdown-menu el-popper el-dropdown-menu--medium" id="dropdown-menu-3294" style="display: none;"><!----> <li tabindex="-1" class="el-dropdown-menu__item"><!----><i aria-hidden="true" class="fa fa-flag-o pr-0 mr-05"></i>
                Báo cáo
            </li> <li tabindex="-1" class="el-dropdown-menu__item"><!----><i aria-hidden="true" class="fa fa-plus-square-o pr-0 mr-05"></i>
                Thêm vào series của tôi
            </li> <!----> <!----> <!----> <!----> <!----> <!----></ul></div> <!----> <!----> <!----> <!----> <!----></div></div> <!----> <div><div role="alert" class="el-alert mt-1 el-alert--warning is-light"><i class="el-alert__icon el-icon-warning is-big"></i><div class="el-alert__content"><!----><p class="el-alert__description">
            Bài đăng này đã không được cập nhật trong 2 năm
        </p><!----><i class="el-alert__closebtn el-icon-close"></i></div></div></div> <div class="article-content__body my-2 flex-fill"><div class="md-contents" style="font-size: 18px; line-height: 1.75;"><h3 id="_1-gioi-thieu-0">1. Giới thiệu</h3>
<ul>
<li>Vòng lặp for là cấu trúc điều khiển lặp được dùng để thực hiện một lệnh hay một khối lệnh với số lần lặp xác định trước.</li>
<li>Có 3 kiểu của vòng lặp for trong java:
<ul>
<li>Vòng lặp for đơn giản</li>
<li>Vòng lặp for cải tiến</li>
<li>Vòng lặp for gán nhãn</li>
</ul>
</li>
<li>Nhưng chúng ta chỉ đi tìm hiểu 2 kiểu vòng lặp phổ biến là <code>vòng lặp for đơn giản và cải tiến</code>.</li>
</ul>
<h3 id="_2-vong-lap-for-don-gian-1">2. Vòng lặp for đơn giản</h3>
<ul>
<li>Cú pháp:</li>
</ul>

            <div style="position:relative" onclick="this.removeAttribute('class');this.querySelectorAll('.v-markdown-it-show-more').forEach(el => el.remove());" onmouseenter="this.getElementsByClassName('v-markdown-it-show-more')[0] ? this.getElementsByClassName('v-markdown-it-show-more')[0].style.display='block' : null" onmouseleave="this.getElementsByClassName('v-markdown-it-show-more')[0] ? this.getElementsByClassName('v-markdown-it-show-more')[0].style.display='none' : null">
                <pre class="language-none" data-filename=""><code class="language-none">for (khoi_tao_bien ; check_dieu_kien ; tang/giam_bien) {  
    // Khối lệnh được thực thi
}
</code></pre>

                <button class="v-markdown-it-code-copy" data-clipboard-text="for (khoi_tao_bien ; check_dieu_kien ; tang/giam_bien) {  
    // Khối lệnh được thực thi
}
" delay="2000" title="Sao chép">
                    <span class="tooltiptext" style="display:none">Đã sao chép ✔️</span>
                    <span class="v-markdown-icon el-icon-document-copy"></span>
                </button>
                
            </div>
        <p><span class="progressive-img_capturer progressive-img_wrapper article-img-wrapper"><canvas class="progressive-img_tiny progressive-img_filter-blur article-img-tiny" width="1398" height="1210" style="background: url('https://images.viblo.asia/60/66a620c6-0981-4acd-844d-c034a6a6ca4a.png') 100%/100%"></canvas><img class="progressive-img_full progressive-img_hidden article-img" width="1398" height="1210" data-full-src="https://images.viblo.asia/66a620c6-0981-4acd-844d-c034a6a6ca4a.png" alt="Screen Shot 2022-08-10 at 23.00.26.png" data-tiny-src="https://images.viblo.asia/60/66a620c6-0981-4acd-844d-c034a6a6ca4a.png" data-zoom-src="https://images.viblo.asia/full/66a620c6-0981-4acd-844d-c034a6a6ca4a.png" data-srcset="https://images.viblo.asia/retina/66a620c6-0981-4acd-844d-c034a6a6ca4a.png 2x" data-wrapper-class="article-img-wrapper" data-tiny-class="article-img-tiny" data-full-class="article-img"></span></p>
<ul>
<li>Ta có:
<ul>
<li><code>khoi_tao_bien</code> là <code>int i = 0</code></li>
<li><code>check_dieu_kien</code> là <code>i &lt; month</code> với <code>month = 12</code></li>
<li><code>tang_bien</code>: vòng lặp for này sử dụng tăng biến với <code>i++</code> (tăng i lên 1 đơn vị)</li>
</ul>
</li>
<li>Vòng lặp trên chạy như sau:
<ul>
<li>Bước 1: Bắt đầu vòng lặp thứ nhất với <code>khoi_tao_bien</code> là <code>int i = 0</code></li>
<li>Bước 2: Check điều kiện nếu <code>i &lt; month</code> thì thực hiện khối lệnh bên trong <code>for</code></li>
<li>Bước 3: Sau đó biến i tăng lên 1 đơn vị (i++) và tiếp tục với vòng lặp thứ 2 giống vòng lặp 1 nhưng lúc này <code>i = 1</code></li>
<li>Bước 4: Cứ thế for lặp đến khi i = 12, lúc này check điều thấy <code>i không còn &lt; month</code> nên kết thúc vòng lặp.</li>
</ul>
</li>
</ul>
<p><span class="progressive-img_capturer progressive-img_wrapper article-img-wrapper"><canvas class="progressive-img_tiny progressive-img_filter-blur article-img-tiny" width="1068" height="1220" style="background: url('https://images.viblo.asia/60/1dda85e7-8d0b-46f6-9f2f-7389ada20546.png') 100%/100%"></canvas><img class="progressive-img_full progressive-img_hidden article-img" width="1068" height="1220" data-full-src="https://images.viblo.asia/1dda85e7-8d0b-46f6-9f2f-7389ada20546.png" alt="Screen Shot 2022-08-10 at 23.18.24.png" data-tiny-src="https://images.viblo.asia/60/1dda85e7-8d0b-46f6-9f2f-7389ada20546.png" data-zoom-src="https://images.viblo.asia/full/1dda85e7-8d0b-46f6-9f2f-7389ada20546.png" data-srcset="https://images.viblo.asia/retina/1dda85e7-8d0b-46f6-9f2f-7389ada20546.png 2x" data-wrapper-class="article-img-wrapper" data-tiny-class="article-img-tiny" data-full-class="article-img"></span></p>
<h3 id="_3-vong-lap-for-cai-tien-2">3. Vòng lặp for cải tiến</h3>
<ul>
<li>Vòng lặp for cải tiến được sử dụng để lặp mảng(array) hoặc collection trong java.</li>
<li>Bạn có thể sử dụng nó dễ dàng, dễ hơn cả vòng lặp for đơn giản. Bởi vì bạn không cần phải tăng hay giảm giá trị của biến rồi check điều kiện, bạn chỉ cần sử dụng ký hiệu hai chấm ":"</li>
<li>Cú pháp:</li>
</ul>

            <div style="position:relative" onclick="this.removeAttribute('class');this.querySelectorAll('.v-markdown-it-show-more').forEach(el => el.remove());" onmouseenter="this.getElementsByClassName('v-markdown-it-show-more')[0] ? this.getElementsByClassName('v-markdown-it-show-more')[0].style.display='block' : null" onmouseleave="this.getElementsByClassName('v-markdown-it-show-more')[0] ? this.getElementsByClassName('v-markdown-it-show-more')[0].style.display='none' : null">
                <pre class="language-none" data-filename=""><code class="language-none">for (Type var : array) {  
    // Khối lệnh được thực thi
} 
</code></pre>

                <button class="v-markdown-it-code-copy" data-clipboard-text="for (Type var : array) {  
    // Khối lệnh được thực thi
} 
" delay="2000" title="Sao chép">
                    <span class="tooltiptext" style="display:none">Đã sao chép ✔️</span>
                    <span class="v-markdown-icon el-icon-document-copy"></span>
                </button>
                
            </div>
        <p><span class="progressive-img_capturer progressive-img_wrapper article-img-wrapper"><canvas class="progressive-img_tiny progressive-img_filter-blur article-img-tiny" width="1386" height="1216" style="background: url('https://images.viblo.asia/60/d42f6b46-51b5-4b71-8cf5-c5c01182e4c5.png') 100%/100%"></canvas><img class="progressive-img_full progressive-img_hidden article-img" width="1386" height="1216" data-full-src="https://images.viblo.asia/d42f6b46-51b5-4b71-8cf5-c5c01182e4c5.png" alt="Screen Shot 2022-08-10 at 23.27.15.png" data-tiny-src="https://images.viblo.asia/60/d42f6b46-51b5-4b71-8cf5-c5c01182e4c5.png" data-zoom-src="https://images.viblo.asia/full/d42f6b46-51b5-4b71-8cf5-c5c01182e4c5.png" data-srcset="https://images.viblo.asia/retina/d42f6b46-51b5-4b71-8cf5-c5c01182e4c5.png 2x" data-wrapper-class="article-img-wrapper" data-tiny-class="article-img-tiny" data-full-class="article-img"></span></p>
<ul>
<li>Vòng lặp for này sẽ duyệt từ đầu đến hết mảng với giá trị <code>i</code> bằng giá trị của phần tử vị trí tương ứng với vòng lặp đó.</li>
<li>Ví dụ trong vòng lặp đầu tiên thì giá trị của <code>i</code> bằng với giá trị của phần tử đầu tiên của mảng là 1.</li>
</ul>
</div> <!----></div> <!----> <div data-v-4365a2a0="" class="tags d-flex flex-wrap align-items-center"> <a data-v-19d5ce29="" data-v-4365a2a0="" href="/tags/vong-lap-for" class="el-tag tag el-tag--info el-tag--medium">
        vòng lặp for
    </a><a data-v-19d5ce29="" data-v-4365a2a0="" href="/tags/java-core" class="el-tag tag el-tag--info el-tag--medium">
        java core
    </a><a data-v-19d5ce29="" data-v-4365a2a0="" href="/tags/java" class="el-tag tag el-tag--info el-tag--medium">
        Java
    </a> </div> <br> <p title="People cannot distribute, remix, adapt, and build upon this workwithout author's permission (or as permitted by fair use)." class="license-text text-muted">
    All rights reserved
</p> <div class="post-footer d-flex align-items-center justify-content-end mb-2"><div data-v-235dd1c0="" class="social-sharing mr-1 social-sharing--vertical social-sharing--medium"><a data-v-235dd1c0="" tooltip-placement="bottom" rel="noopener" class="link link--muted link--muted" data-tippy="" data-original-title="Chia sẻ liên kết đến trang này trên Facebook"><i data-v-235dd1c0="" aria-hidden="true" class="fa fa-facebook"></i></a> <a data-v-235dd1c0="" tooltip-placement="bottom" rel="noopener" class="link link--muted link--muted" data-tippy="" data-original-title="Chia sẻ liên kết đến trang này trên Twitter"><i data-v-235dd1c0="" aria-hidden="true" class="fa fa-twitter"></i></a></div> <div class="post__menu"><div class="el-dropdown"><button type="button" class="el-button p-0 el-button--text text-muted el-dropdown-selfdefine" data-tippy="" data-original-title="Hiển thị các hành động" aria-haspopup="list" aria-controls="dropdown-menu-4923" role="button" tabindex="0"><!----><i class="post__menu__more el-icon-more-outline"></i><!----></button> <ul class="el-dropdown-menu el-popper el-dropdown-menu--medium" id="dropdown-menu-4923" style="display: none;"><!----> <li tabindex="-1" class="el-dropdown-menu__item"><!----><i aria-hidden="true" class="fa fa-flag-o pr-0 mr-05"></i>
                Báo cáo
            </li> <li tabindex="-1" class="el-dropdown-menu__item"><!----><i aria-hidden="true" class="fa fa-plus-square-o pr-0 mr-05"></i>
                Thêm vào series của tôi
            </li> <!----> <!----> <!----> <!----> <!----> <!----></ul></div> <!----> <!----> <!----> <!----> <!----></div></div></article>