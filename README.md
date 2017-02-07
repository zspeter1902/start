# start
一个开始
$('img').each(function(){//替换图片
		if(($(this).attr('src')).indexOf('.')<0) $(this).attr('src','.jpg');					   
});	
