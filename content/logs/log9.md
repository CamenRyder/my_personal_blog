---
title: "Bài 9 - Vòng lặp while, do-while trong java"
date: 2024-12-28T02:54:01+05:30
author: Minh Hiếu
description: Mô tả
tags:
  - log
---

<article class="post-content"> <div class="d-md-flex align-items-top justify-content-between"><div data-v-4365a2a0="" class="tags d-flex flex-wrap align-items-center">  </div> <div class="post__menu"><div class="el-dropdown"><button type="button" class="el-button p-0 el-button--text text-muted el-dropdown-selfdefine" data-tippy="" data-original-title="Hiển thị các hành động" aria-haspopup="list" aria-controls="dropdown-menu-900" role="button" tabindex="0"><!----><i class="post__menu__more el-icon-more-outline"></i><!----></button> <ul class="el-dropdown-menu el-popper el-dropdown-menu--medium" id="dropdown-menu-900" style="display: none;"><!----> <li tabindex="-1" class="el-dropdown-menu__item"><!----><i aria-hidden="true" class="fa fa-flag-o pr-0 mr-05"></i>
                Báo cáo
            </li> <li tabindex="-1" class="el-dropdown-menu__item"><!----><i aria-hidden="true" class="fa fa-plus-square-o pr-0 mr-05"></i>
                Thêm vào series của tôi
            </li> <!----> <!----> <!----> <!----> <!----> <!----></ul></div> <!----> <!----> <!----> <!----> <!----></div></div> <!----> <div><div role="alert" class="el-alert mt-1 el-alert--warning is-light"><i class="el-alert__icon el-icon-warning is-big"></i><div class="el-alert__content"><!----><p class="el-alert__description">
            Bài đăng này đã không được cập nhật trong 2 năm
        </p><!----><i class="el-alert__closebtn el-icon-close"></i></div></div></div> <div class="article-content__body my-2 flex-fill"><div class="md-contents" style="font-size: 18px; line-height: 1.75;"><h3 id="_1-vong-lap-while-0">1. Vòng lặp while.</h3>
<h4>1.1 Khái niệm</h4>
<ul>
<li>Vòng lặp while được dùng để thực hiện một lệnh hay một khối lệnh với số lần lặp chưa xác định trước.</li>
<li>Với vòng lặp while thì điều kiện lặp được kiểm tra trước khi thực hiện thân của vòng lặp.</li>
</ul>
<h4>1.2 Cú pháp</h4>

            <div style="position:relative" onclick="this.removeAttribute('class');this.querySelectorAll('.v-markdown-it-show-more').forEach(el => el.remove());" onmouseenter="this.getElementsByClassName('v-markdown-it-show-more')[0] ? this.getElementsByClassName('v-markdown-it-show-more')[0].style.display='block' : null" onmouseleave="this.getElementsByClassName('v-markdown-it-show-more')[0] ? this.getElementsByClassName('v-markdown-it-show-more')[0].style.display='none' : null">
                <pre class="language-none" data-filename=""><code class="language-none">while (điều_kiện_lặp) {
    // Các lệnh

}
</code></pre>

                <button class="v-markdown-it-code-copy" data-clipboard-text="while (điều_kiện_lặp) {
    // Các lệnh

}
" delay="2000" title="Sao chép">
<span class="tooltiptext" style="display:none">Đã sao chép ✔️</span>
<span class="v-markdown-icon el-icon-document-copy"></span>
</button>

            </div>
        <ul>

<li>điều_kiện_lặp: là điều kiện để xác định điều kiện lặp. Có giá trị là true hoặc false.</li>
<li>Các lệnh nằm trong cặp dấu {} là thân của vòng lặp.</li>
<li>Lưu ý:
<ul>
<li>Vòng lặp while kiểm tra điều kiện trước rồi mới thực hiện các câu lệnh trong thân vòng lặp nên nếu ngay từ đầu <code>điều_kiện_lặp</code> đã có giá trị false thì vòng lặp while sẽ không được thực hiện bất cứ lần nào.</li>
<li>Nếu <code>điều_kiện_lặp</code> có giá trị là true và không thay đổi thì vòng lặp while sẽ trở thành vòng lặp vô hạn.</li>
<li>Để dừng vòng lặp while thì bên trong while cần có lệnh làm thay đổi giá trị của <code>điều_kiện_lặp</code> thành false hoặc sử dụng lệnh break.</li>
</ul>
</li>
</ul>
<p><span class="progressive-img_capturer progressive-img_wrapper article-img-wrapper"><canvas class="progressive-img_tiny progressive-img_filter-blur article-img-tiny" width="1400" height="1276" style="background: url('https://images.viblo.asia/60/9a1c5af5-5f5d-47b9-8076-484ec9fe94ac.png') 100%/100%"></canvas><img class="progressive-img_full progressive-img_hidden article-img" width="1400" height="1276" data-full-src="https://images.viblo.asia/9a1c5af5-5f5d-47b9-8076-484ec9fe94ac.png" alt="Screen Shot 2022-08-12 at 14.24.29.png" data-tiny-src="https://images.viblo.asia/60/9a1c5af5-5f5d-47b9-8076-484ec9fe94ac.png" data-zoom-src="https://images.viblo.asia/full/9a1c5af5-5f5d-47b9-8076-484ec9fe94ac.png" data-srcset="https://images.viblo.asia/retina/9a1c5af5-5f5d-47b9-8076-484ec9fe94ac.png 2x" data-wrapper-class="article-img-wrapper" data-tiny-class="article-img-tiny" data-full-class="article-img"></span></p>
<h3 id="_2-vong-lap-do---while-1">2. Vòng lặp do - while</h3>
<h4>2.1 Khái niệm</h4>
<ul>
<li>Cũng giống với vòng lặp do - while được dùng để thực hiện một lệnh hay một khối lệnh với số lần lặp chưa xác định trước.</li>
<li>Nhưng khác với while, do - while chỉ kiểm tra điều kiện lặp sau khi thân vòng lặp đã được thực hiện một lần.</li>
</ul>
<h4>2.2 Cú pháp</h4>

            <div style="position:relative" onclick="this.removeAttribute('class');this.querySelectorAll('.v-markdown-it-show-more').forEach(el => el.remove());" onmouseenter="this.getElementsByClassName('v-markdown-it-show-more')[0] ? this.getElementsByClassName('v-markdown-it-show-more')[0].style.display='block' : null" onmouseleave="this.getElementsByClassName('v-markdown-it-show-more')[0] ? this.getElementsByClassName('v-markdown-it-show-more')[0].style.display='none' : null">
                <pre class="language-none" data-filename=""><code class="language-none">do {
    // Các lệnh

} while (điều_kiện_lặp);
</code></pre>

                <button class="v-markdown-it-code-copy" data-clipboard-text="do {
    // Các lệnh

} while (điều_kiện_lặp);
" delay="2000" title="Sao chép">
<span class="tooltiptext" style="display:none">Đã sao chép ✔️</span>
<span class="v-markdown-icon el-icon-document-copy"></span>
</button>

            </div>
        <ul>

<li>điều_kiện_lặp: là điều kiện để xác định điều kiện lặp. Có giá trị là true hoặc false.</li>
<li>Các lệnh nằm trong cặp dấu {} là thân của vòng lặp.</li>
<li>Lưu ý: khác với while, vòng lặp do - while thực hiện các câu lệnh trong thân vòng lặp trước rồi mới kiểm tra điều kiện nên các câu lệnh nằm trong thân vòng lặp sẽ được thực hiện ít nhất là một lần. Sau đó, tùy theo kết quả của biểu thức điều kiện, chương trình sẽ tiếp tục thực hiện hoặc thoát ra khỏi vòng lặp.</li>
<li>Ví dụ: như ví dụ dưới đây, mặc dù ngay từ đầu điều kiện đã sai nhưng lệnh in ra màn hình vẫn được thực hiện 1 lần.</li>
</ul>
<p><span class="progressive-img_capturer progressive-img_wrapper article-img-wrapper"><canvas class="progressive-img_tiny progressive-img_filter-blur article-img-tiny" width="1398" height="820" style="background: url('https://images.viblo.asia/60/d47f27ea-3f05-4336-87ef-48ea8c8ec5dc.png') 100%/100%"></canvas><img class="progressive-img_full progressive-img_hidden article-img" width="1398" height="820" data-full-src="https://images.viblo.asia/d47f27ea-3f05-4336-87ef-48ea8c8ec5dc.png" alt="Screen Shot 2022-08-12 at 16.31.00.png" data-tiny-src="https://images.viblo.asia/60/d47f27ea-3f05-4336-87ef-48ea8c8ec5dc.png" data-zoom-src="https://images.viblo.asia/full/d47f27ea-3f05-4336-87ef-48ea8c8ec5dc.png" data-srcset="https://images.viblo.asia/retina/d47f27ea-3f05-4336-87ef-48ea8c8ec5dc.png 2x" data-wrapper-class="article-img-wrapper" data-tiny-class="article-img-tiny" data-full-class="article-img"></span></p>
</div> <!----></div> <!----> <div data-v-4365a2a0="" class="tags d-flex flex-wrap align-items-center"> <a data-v-19d5ce29="" data-v-4365a2a0="" href="/tags/do-while" class="el-tag tag el-tag--info el-tag--medium">
        do while
    </a><a data-v-19d5ce29="" data-v-4365a2a0="" href="/tags/while-loops" class="el-tag tag el-tag--info el-tag--medium">
        while loops
    </a><a data-v-19d5ce29="" data-v-4365a2a0="" href="/tags/java-core" class="el-tag tag el-tag--info el-tag--medium">
        java core
    </a><a data-v-19d5ce29="" data-v-4365a2a0="" href="/tags/java" class="el-tag tag el-tag--info el-tag--medium">
        Java
    </a> </div> <br> <p title="People cannot distribute, remix, adapt, and build upon this workwithout author's permission (or as permitted by fair use)." class="license-text text-muted">
    All rights reserved
</p> <div class="post-footer d-flex align-items-center justify-content-end mb-2"><div data-v-235dd1c0="" class="social-sharing mr-1 social-sharing--vertical social-sharing--medium"><a data-v-235dd1c0="" tooltip-placement="bottom" rel="noopener" class="link link--muted link--muted" data-tippy="" data-original-title="Chia sẻ liên kết đến trang này trên Facebook"><i data-v-235dd1c0="" aria-hidden="true" class="fa fa-facebook"></i></a> <a data-v-235dd1c0="" tooltip-placement="bottom" rel="noopener" class="link link--muted link--muted" data-tippy="" data-original-title="Chia sẻ liên kết đến trang này trên Twitter"><i data-v-235dd1c0="" aria-hidden="true" class="fa fa-twitter"></i></a></div> <div class="post__menu"><div class="el-dropdown"><button type="button" class="el-button p-0 el-button--text text-muted el-dropdown-selfdefine" data-tippy="" data-original-title="Hiển thị các hành động" aria-haspopup="list" aria-controls="dropdown-menu-5095" role="button" tabindex="0"><!----><i class="post__menu__more el-icon-more-outline"></i><!----></button> <ul class="el-dropdown-menu el-popper el-dropdown-menu--medium" id="dropdown-menu-5095" style="display: none;"><!----> <li tabindex="-1" class="el-dropdown-menu__item"><!----><i aria-hidden="true" class="fa fa-flag-o pr-0 mr-05"></i>
                Báo cáo
            </li> <li tabindex="-1" class="el-dropdown-menu__item"><!----><i aria-hidden="true" class="fa fa-plus-square-o pr-0 mr-05"></i>
                Thêm vào series của tôi
            </li> <!----> <!----> <!----> <!----> <!----> <!----></ul></div> <!----> <!----> <!----> <!----> <!----></div></div></article>
