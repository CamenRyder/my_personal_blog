---
title: "Bài 7 - Cấu trúc điều khiển if - else, switch - case trong Java"
date: 2024-12-28T02:54:01+05:30
author: Minh Hiếu
description: Mô tả
tags:
  - log
---
<article class="post-content"> <div class="d-md-flex align-items-top justify-content-between"><div data-v-4365a2a0="" class="tags d-flex flex-wrap align-items-center">  </div> <div class="post__menu"><div class="el-dropdown"><button type="button" class="el-button p-0 el-button--text text-muted el-dropdown-selfdefine" data-tippy="" data-original-title="Hiển thị các hành động" aria-haspopup="list" aria-controls="dropdown-menu-9315" role="button" tabindex="0"><!----><i class="post__menu__more el-icon-more-outline"></i><!----></button> <ul class="el-dropdown-menu el-popper el-dropdown-menu--medium" id="dropdown-menu-9315" style="display: none;"><!----> <li tabindex="-1" class="el-dropdown-menu__item"><!----><i aria-hidden="true" class="fa fa-flag-o pr-0 mr-05"></i>
                Báo cáo
            </li> <li tabindex="-1" class="el-dropdown-menu__item"><!----><i aria-hidden="true" class="fa fa-plus-square-o pr-0 mr-05"></i>
                Thêm vào series của tôi
            </li> <!----> <!----> <!----> <!----> <!----> <!----></ul></div> <!----> <!----> <!----> <!----> <!----></div></div> <!----> <div><div role="alert" class="el-alert mt-1 el-alert--warning is-light"><i class="el-alert__icon el-icon-warning is-big"></i><div class="el-alert__content"><!----><p class="el-alert__description">
            Bài đăng này đã không được cập nhật trong 2 năm
        </p><!----><i class="el-alert__closebtn el-icon-close"></i></div></div></div> <div class="article-content__body my-2 flex-fill"><div class="md-contents" style="font-size: 18px; line-height: 1.75;"><h3 id="_1-if---else-0">1. if - else</h3>
<h4>1.1 Khái niệm</h4>
<ul>
<li>Trong hầu hết các ngôn ngữ lập trình cấu trúc điều khiển if - else sẽ kiểm tra kết quả của 1 điều kiện và dựa vào kết quả đó để thực hiện các hành động tương ứng.</li>
</ul>
<h4>1.2 Cấu trúc</h4>
<ul>
<li>Ta có cấu trúc if - else đầy đủ như sau:</li>
</ul>

            <div style="position:relative" onclick="this.removeAttribute('class');this.querySelectorAll('.v-markdown-it-show-more').forEach(el => el.remove());" onmouseenter="this.getElementsByClassName('v-markdown-it-show-more')[0] ? this.getElementsByClassName('v-markdown-it-show-more')[0].style.display='block' : null" onmouseleave="this.getElementsByClassName('v-markdown-it-show-more')[0] ? this.getElementsByClassName('v-markdown-it-show-more')[0].style.display='none' : null">
                <pre class="language-none" data-filename=""><code class="language-none">// Cấu trúc if - else đầy đủ.

if(điều kiện) {
    hành động 1
} else {
    hành động 2
}
</code></pre>

                <button class="v-markdown-it-code-copy" data-clipboard-text="// Cấu trúc if - else đầy đủ.

if(điều kiện) {
    hành động 1
} else {
    hành động 2
}
" delay="2000" title="Sao chép">
                    <span class="tooltiptext" style="display:none">Đã sao chép ✔️</span>
                    <span class="v-markdown-icon el-icon-document-copy"></span>
                </button>
                
            </div>
        <ul>
<li>Ở đây <code>điều kiệu</code> bên trong if là một biểu thức toán học có kết quả là kiểu boolean (true/false)</li>
<li>Nếu <code>điều kiện</code> đúng (true) thì thực hiện <code>hành động 1</code>, ngược lại, điều kiện sai (false) thì thực hiện <code>hành động 2</code>.</li>
</ul>
<p><span class="progressive-img_capturer progressive-img_wrapper article-img-wrapper"><canvas class="progressive-img_tiny progressive-img_filter-blur article-img-tiny" width="1486" height="930" style="background: url('https://images.viblo.asia/60/122aa7c0-7d0b-4ecd-a120-a4989a581f62.png') 100%/100%"></canvas><img class="progressive-img_full progressive-img_hidden article-img" width="1486" height="930" data-full-src="https://images.viblo.asia/122aa7c0-7d0b-4ecd-a120-a4989a581f62.png" alt="Screen Shot 2022-08-10 at 16.50.52.png" data-tiny-src="https://images.viblo.asia/60/122aa7c0-7d0b-4ecd-a120-a4989a581f62.png" data-zoom-src="https://images.viblo.asia/full/122aa7c0-7d0b-4ecd-a120-a4989a581f62.png" data-srcset="https://images.viblo.asia/retina/122aa7c0-7d0b-4ecd-a120-a4989a581f62.png 2x" data-wrapper-class="article-img-wrapper" data-tiny-class="article-img-tiny" data-full-class="article-img"></span></p>
<ul>
<li>Tương tự, ta có cấu trúc if - else if - else:</li>
</ul>

            <div style="position:relative" onclick="this.removeAttribute('class');this.querySelectorAll('.v-markdown-it-show-more').forEach(el => el.remove());" onmouseenter="this.getElementsByClassName('v-markdown-it-show-more')[0] ? this.getElementsByClassName('v-markdown-it-show-more')[0].style.display='block' : null" onmouseleave="this.getElementsByClassName('v-markdown-it-show-more')[0] ? this.getElementsByClassName('v-markdown-it-show-more')[0].style.display='none' : null">
                <pre class="language-none" data-filename=""><code class="language-none">// Cấu trúc if - else if - else.

if (điều kiện 1) {
    hành động 1
} else if (điều kiện 2) {
    hành động 2
} else {
    hành động 3
}
</code></pre>

                <button class="v-markdown-it-code-copy" data-clipboard-text="// Cấu trúc if - else if - else.

if (điều kiện 1) {
    hành động 1
} else if (điều kiện 2) {
    hành động 2
} else {
    hành động 3
}
" delay="2000" title="Sao chép">
                    <span class="tooltiptext" style="display:none">Đã sao chép ✔️</span>
                    <span class="v-markdown-icon el-icon-document-copy"></span>
                </button>
                
            </div>
        <ul>
<li>
<p><code>điều kiệu 1</code> bên trong if là một biểu thức toán học có kết quả là kiểu boolean (true/false)</p>
</li>
<li>
<p>Nếu <code>điều kiện 1</code> đúng (true) thì thực hiện <code>hành động 1</code>, ngược lại, <code>điều kiện 1</code> sai (false) thì thực hiện kiểm tra <code>điều kiện 2</code></p>
</li>
<li>
<p>Nếu <code>điều kiện 2</code> đúng (true) thì thực hiện <code>hành động 2</code>, ngược lại, <code>điều kiện 2</code> sai (false) thì thực hiện <code>hành động 3</code>.</p>
</li>
<li>
<p>Tương tự, chúng ta có thêm 2 cấu trúc khác như sau:</p>
</li>
</ul>

            <div style="position:relative" onclick="this.removeAttribute('class');this.querySelectorAll('.v-markdown-it-show-more').forEach(el => el.remove());" onmouseenter="this.getElementsByClassName('v-markdown-it-show-more')[0] ? this.getElementsByClassName('v-markdown-it-show-more')[0].style.display='block' : null" onmouseleave="this.getElementsByClassName('v-markdown-it-show-more')[0] ? this.getElementsByClassName('v-markdown-it-show-more')[0].style.display='none' : null">
                <pre class="language-none" data-filename=""><code class="language-none">// Cấu trúc if khuyết else.

if(điều kiện) {
    hành động 1
}
</code></pre>

                <button class="v-markdown-it-code-copy" data-clipboard-text="// Cấu trúc if khuyết else.

if(điều kiện) {
    hành động 1
}
" delay="2000" title="Sao chép">
                    <span class="tooltiptext" style="display:none">Đã sao chép ✔️</span>
                    <span class="v-markdown-icon el-icon-document-copy"></span>
                </button>
                
            </div>
        
            <div style="position:relative" onclick="this.removeAttribute('class');this.querySelectorAll('.v-markdown-it-show-more').forEach(el => el.remove());" onmouseenter="this.getElementsByClassName('v-markdown-it-show-more')[0] ? this.getElementsByClassName('v-markdown-it-show-more')[0].style.display='block' : null" onmouseleave="this.getElementsByClassName('v-markdown-it-show-more')[0] ? this.getElementsByClassName('v-markdown-it-show-more')[0].style.display='none' : null">
                <pre class="language-none" data-filename=""><code class="language-none">// Cấu trúc if - else lồng nhau.

if(điều kiện 1) {
    if (điều kiện 2) {
        hành động 1
     } else {
         hành động 2
      }
} else {
    hành động 3
}
</code></pre>

                <button class="v-markdown-it-code-copy" data-clipboard-text="// Cấu trúc if - else lồng nhau.

if(điều kiện 1) {
    if (điều kiện 2) {
        hành động 1
     } else {
         hành động 2
      }
} else {
    hành động 3
}
" delay="2000" title="Sao chép">
                    <span class="tooltiptext" style="display:none">Đã sao chép ✔️</span>
                    <span class="v-markdown-icon el-icon-document-copy"></span>
                </button>
                
            </div>
        <h3 id="_2-switch---case-1">2. switch - case</h3>
<h4>2.1 Khái niệm</h4>
<ul>
<li>Cấu trúc điều khiển <code>switch - case</code> sẽ kiểm tra kết quả của 1 điều kiện và dựa vào kết quả đó để thực hiện các hành động tương ứng.</li>
</ul>
<h4>2.2 Cú pháp</h4>

            <div style="position:relative" class="v-markdown-content-box" onclick="this.removeAttribute('class');this.querySelectorAll('.v-markdown-it-show-more').forEach(el => el.remove());" onmouseenter="this.getElementsByClassName('v-markdown-it-show-more')[0] ? this.getElementsByClassName('v-markdown-it-show-more')[0].style.display='block' : null" onmouseleave="this.getElementsByClassName('v-markdown-it-show-more')[0] ? this.getElementsByClassName('v-markdown-it-show-more')[0].style.display='none' : null">
                <pre class="language-none" data-filename=""><code class="language-none">switch (biểu_thức) {
	case giá_trị_1:
		Lệnh 1;
		break;
	case giá_trị_2:
		Lệnh 2;
		break;
	...
	case giá_trị_n:
		Lệnh n;
		break;
	default:
        Lệnh 0;
}
</code></pre>

                <button class="v-markdown-it-code-copy" data-clipboard-text="switch (biểu_thức) {
	case giá_trị_1:
		Lệnh 1;
		break;
	case giá_trị_2:
		Lệnh 2;
		break;
	...
	case giá_trị_n:
		Lệnh n;
		break;
	default:
        Lệnh 0;
}
" delay="2000" title="Sao chép">
                    <span class="tooltiptext" style="display:none">Đã sao chép ✔️</span>
                    <span class="v-markdown-icon el-icon-document-copy"></span>
                </button>
                
        <div class="v-content-flex-center">
            <button style="display:none" class="v-markdown-it-show-more button-more">
                <span class="el-icon-bottom"></span>
                <span class="show-more-text">Xem thêm</span>
            </button>
        </div>
            </div>
        <ul>
<li><code>biểu_thức</code> trả về một giá trị, kết quả là một số nguyên, chuỗi hoặc một ký tự.</li>
<li>Giá_trị_1, giá_trị_2,..., giá_trị_n là các biểu thức hằng, nguyên hoặc ký tự và chúng phải khác nhau.</li>
<li>Khi mà <code>biểu thức</code> trả về một  <code>giá trị</code> thì sẽ thực hiện lệnh bên trong <code>case</code>  có giá trị tương ứng.</li>
<li>Khi mà <code>biểu thức</code> trả về  <code>giá trị</code>mà không có trong các case thì sẽ thực hiện lệnh trong <code>default</code>.</li>
</ul>
<p><span class="progressive-img_capturer progressive-img_wrapper article-img-wrapper"><canvas class="progressive-img_tiny progressive-img_filter-blur article-img-tiny" width="1556" height="1232" style="background: url('https://images.viblo.asia/60/5a4c9116-839c-4333-9cc7-c686fb945e82.png') 100%/100%"></canvas><img class="progressive-img_full progressive-img_hidden article-img" width="1556" height="1232" data-full-src="https://images.viblo.asia/5a4c9116-839c-4333-9cc7-c686fb945e82.png" alt="Screen Shot 2022-08-10 at 17.35.30.png" data-tiny-src="https://images.viblo.asia/60/5a4c9116-839c-4333-9cc7-c686fb945e82.png" data-zoom-src="https://images.viblo.asia/full/5a4c9116-839c-4333-9cc7-c686fb945e82.png" data-srcset="https://images.viblo.asia/retina/5a4c9116-839c-4333-9cc7-c686fb945e82.png 2x" data-wrapper-class="article-img-wrapper" data-tiny-class="article-img-tiny" data-full-class="article-img"></span></p>
<ul>
<li>Lệnh <code>break</code> là để nhảy ra khỏi lệnh <code>switch</code>, nếu không có lệnh này cấu trúc <code>switch</code> sẽ duyệt cả các trường hợp phía dưới cho đến hết.</li>
<li>Khi không sử dụng từ khóa <code>break</code> trong mệnh đề <code>switch-case</code>. Điều này có nghĩa là các khối lệnh sau <code>case có giá trị</code> phù hợp sẽ được thực thi.</li>
<li>Lưu ý là khối <code>default</code> là không bắt buộc có ở cấu trúc <code>switch case</code> trong Java, tức là bạn có thể viết cũng được mà không viết cũng không bị lỗi.</li>
</ul>
<p><span class="progressive-img_capturer progressive-img_wrapper article-img-wrapper"><canvas class="progressive-img_tiny progressive-img_filter-blur article-img-tiny" width="1548" height="1172" style="background: url('https://images.viblo.asia/60/a3386f8b-529b-402a-9d99-99b4732196d2.png') 100%/100%"></canvas><img class="progressive-img_full progressive-img_hidden article-img" width="1548" height="1172" data-full-src="https://images.viblo.asia/a3386f8b-529b-402a-9d99-99b4732196d2.png" alt="Screen Shot 2022-08-10 at 20.32.46.png" data-tiny-src="https://images.viblo.asia/60/a3386f8b-529b-402a-9d99-99b4732196d2.png" data-zoom-src="https://images.viblo.asia/full/a3386f8b-529b-402a-9d99-99b4732196d2.png" data-srcset="https://images.viblo.asia/retina/a3386f8b-529b-402a-9d99-99b4732196d2.png 2x" data-wrapper-class="article-img-wrapper" data-tiny-class="article-img-tiny" data-full-class="article-img"></span></p>
<h3 id="_3-khi-nao-dung-if-else-khi-nao-dung-switch-case--2">3. Khi nào dùng if-else, khi nào dùng switch-case ?</h3>
<ul>
<li>Vậy khi nào thì cần dùng <code>switch - case</code> thay vì <code>if - else</code>:
<ul>
<li>Chúng ta có số trường hợp cần xử lý lớn hơn 3 thì khi đó chúng ta nên sử dụng <code>switch - case</code> để dễ dàng kiểm tra và xử lý.</li>
<li>Khi trường hợp <code>biểu_thức</code> và <code>giá_trị</code> phải có giá trị cụ thể (số nguyên, ký tự...).</li>
</ul>
</li>
<li>Lưu ý: đối với một bài toán sử dụng  <code>switch - case</code> thì có thể thay thế bằng <code>if - else</code>, nhưng ngược lại một bài toán sử dụng  <code>if - else</code> thì chưa chắc có thể thay thế bằng  <code>switch - case</code></li>
</ul>
</div> <!----></div> <!----> <div data-v-4365a2a0="" class="tags d-flex flex-wrap align-items-center"> <a data-v-19d5ce29="" data-v-4365a2a0="" href="/tags/if-else" class="el-tag tag el-tag--info el-tag--medium">
        if else
    </a><a data-v-19d5ce29="" data-v-4365a2a0="" href="/tags/java-core" class="el-tag tag el-tag--info el-tag--medium">
        java core
    </a><a data-v-19d5ce29="" data-v-4365a2a0="" href="/tags/java" class="el-tag tag el-tag--info el-tag--medium">
        Java
    </a><a data-v-19d5ce29="" data-v-4365a2a0="" href="/tags/switch-case" class="el-tag tag el-tag--info el-tag--medium">
        switch case
    </a> </div> <br> <p title="People cannot distribute, remix, adapt, and build upon this workwithout author's permission (or as permitted by fair use)." class="license-text text-muted">
    All rights reserved
</p> <div class="post-footer d-flex align-items-center justify-content-end mb-2"><div data-v-235dd1c0="" class="social-sharing mr-1 social-sharing--vertical social-sharing--medium"><a data-v-235dd1c0="" tooltip-placement="bottom" rel="noopener" class="link link--muted link--muted" data-tippy="" data-original-title="Chia sẻ liên kết đến trang này trên Facebook"><i data-v-235dd1c0="" aria-hidden="true" class="fa fa-facebook"></i></a> <a data-v-235dd1c0="" tooltip-placement="bottom" rel="noopener" class="link link--muted link--muted" data-tippy="" data-original-title="Chia sẻ liên kết đến trang này trên Twitter"><i data-v-235dd1c0="" aria-hidden="true" class="fa fa-twitter"></i></a></div> <div class="post__menu"><div class="el-dropdown"><button type="button" class="el-button p-0 el-button--text text-muted el-dropdown-selfdefine" data-tippy="" data-original-title="Hiển thị các hành động" aria-haspopup="list" aria-controls="dropdown-menu-1744" role="button" tabindex="0"><!----><i class="post__menu__more el-icon-more-outline"></i><!----></button> <ul class="el-dropdown-menu el-popper el-dropdown-menu--medium" id="dropdown-menu-1744" style="display: none;"><!----> <li tabindex="-1" class="el-dropdown-menu__item"><!----><i aria-hidden="true" class="fa fa-flag-o pr-0 mr-05"></i>
                Báo cáo
            </li> <li tabindex="-1" class="el-dropdown-menu__item"><!----><i aria-hidden="true" class="fa fa-plus-square-o pr-0 mr-05"></i>
                Thêm vào series của tôi
            </li> <!----> <!----> <!----> <!----> <!----> <!----></ul></div> <!----> <!----> <!----> <!----> <!----></div></div></article>