# lineclamp
-webkit-line-clamp 是一个 不规范的属性（unsupported WebKit property），它没有出现在 CSS 规范草案中。<br><br>
限制在一个块元素显示的文本的行数。 为了实现该效果，它需要组合其他外来的WebKit属性。常见结合属性：<br>
display: -webkit-box; 必须结合的属性 ，将对象作为弹性伸缩盒子模型显示 。<br>
-webkit-box-orient 必须结合的属性 ，设置或检索伸缩盒对象的子元素的排列方式 。<br>
text-overflow，可以用来多行文本的情况下，用省略号“...”隐藏超出范围的文本 。<br>

    overflow : hidden;
    text-overflow: ellipsis;
    display: -webkit-box;
    -webkit-line-clamp: 2;
    -webkit-box-orient: vertical;
