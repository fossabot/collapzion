# collapzion.js (v 1.0)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Ft3zz%2Fcollapzion.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Ft3zz%2Fcollapzion?ref=badge_shield)

Lightweight jQuery plugin that help to create and Floating Action Buttons  for your mobile or dekstop application

<img src="https://image.ibb.co/fJqbao/channasmcs_Floating_Action_Buttons.jpg" id="image-img" class="image-framed" style="max-width: 1275px;">

## Getting Started

## manually
`git clone git@github.com:channasmcs/collapzion.git`

## How use collapzion.js
```javascript
jQuery(function($){
	$('#btncollapzion').Collapzion({
        _child_attribute:[
          	{
              'label':'Create new Document',
              'url':'/Create',
              'icon':'&#xE150;'
          	},
          	{
              'label':'Manage My Document',
              'url':'/manage',
              'icon':'&#xE873;'
          	},
          	{
              'label':'My Profile',
              'url':'/profile',
              'icon':'&#xE7FD;'
          	},
      	],
      	_main_btn_color:'#4285f4;',
      	_child_btn_color:'#f4645f;',
	});
});
```

```html
<div id="btncollapzion" class=" btn_collapzion"></div>
```
## Import font Icon

in this time collapzion.js use , [Google material Icon](https://material.io/icons/). you can import icon using following URl
```html
<link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
```

## License
Copyright &copy; Channa Bandara<br>
Licensed under the  GNU GENERAL PUBLIC LICENSE.


[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Ft3zz%2Fcollapzion.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Ft3zz%2Fcollapzion?ref=badge_large)