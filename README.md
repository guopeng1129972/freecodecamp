# freecodecamp
freecodecamp练习心得
55=
注意：在 HTML 中这些 class 如何排序是无所谓的。

然而，在 <style> 部分中 class 声明的顺序却非常重要，第二个声明总是比第一个具有优先权。因为 .blue-text 是第二个声明，它覆盖了 .pink-text 属性。
56=
注意：你声明的这个 CSS 在 pink-text类选择器的上面还是下面是无所谓的，因为 id 属性总是具有更高的优先级。
106 107 108 没弄 主要是需要完成几个国外网站的关注
111 jq中加入按钮弹回操作  $(document).ready(function() {
    $("button").addClass("animated bounce");

  });
  我们已经在后台为你引入了jQuery库和Animate.css库，这样你就可以在编辑器里直接可以使用这两个库，进而通过jQuery给button元素添加bounce回弹动画效果。
 117 总结 清空
 122 比如，如果我想把target2从left-well拷贝到right-well，我们可以这样写:

$("#target2").clone().appendTo("#right-well");
你有没有发现两个jQuery方法合在一起使用了？这就叫方法链function chaining，使用起来很方便。
