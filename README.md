# Headroom

[headroom.js](http://wicky.nillia.ms/headroom.js/) 和 [animate.css](http://daneden.github.io/animate.css/) 

## Installation

添加下面代码到 Gemfile:

```ruby
gem 'headroom'
```

执行:

    $ bundle

或者是执行:

    $ gem install headroom

## Usage

在application.js中引用:

```
//= require headroom #这里的headroom可以根据自己的情况选择 angular.headroom 、 angular.headroom.min 、headroom.min 、 jQuery.headroom 、jQuery.headroom.min
```

在application.css中引用:

```
//= require animate
```

或者

在application.coffee中引用:

```
#=require headroom #这里的headroom可以根据自己的情况选择 angular.headroom 、 angular.headroom.min 、headroom.min 、 jQuery.headroom 、jQuery.headroom.min
```

在application.scss中引用:

```
#=require animate
```

headroom.js配置和初始化:

```
<script type="text/javascript">
	$(function(){
		var elem = document.querySelector("header");
		var headroom = new Headroom(elem, {
		  "offset": 202,
		  "tolerance": 3,
		  "classes": {
		    "initial": "animated",
		    "pinned": "zoomIn",
		    "unpinned": "zoomOut"
		  }
		});
		headroom.init();
	})
</script>
```
[官网例子](http://wicky.nillia.ms/headroom.js/playroom/) 

[animate.css的使用方法](https://github.com/daneden/animate.css#usage)

## Contributing

1. Fork it ( https://github.com/[my-github-username]/headroom/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
