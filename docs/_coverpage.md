![logo](_media/java_icon.svg)

# 北省的Java开发文档 <small>1.3.2</small>

> 🌈先选一个你喜欢的主题吧

<div class="demo-theme-preview" >
  <a data-theme="vue">vue</a>
  <a data-theme="buble">buble</a>
  <a data-theme="dark">dark</a>
  <a data-theme="pure">pure</a>
</div>


<style>
  .demo-theme-preview a {
    padding-right: 10px;
  }

  .demo-theme-preview a:hover {
    cursor: pointer;
    text-decoration: underline;
  }
</style>

<script>
  var preview = Docsify.dom.find('.demo-theme-preview');
  var themes = Docsify.dom.findAll('[rel="stylesheet"]');

  preview.onclick = function (e) {
    var title = e.target.getAttribute('data-theme');

    themes.forEach(function (theme) {
      theme.disabled = theme.title !== title;
    });
  };
</script>



[GitHub](https://github.com/Beisheng8888/Beisheng8888.github.io)
[开始](#🎁readme)
[V2.0](https://beisheng8888.github.io/blog/)

