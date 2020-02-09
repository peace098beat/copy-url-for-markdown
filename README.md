# copy-url-for-markdown
Markdown形式でリンクをコピーするブックマークレット

<a href="javascript:(function(){var copy_clipboard_for_md=function(){var target_text='['+document.title.replace(/([¥[¥]])/g,'¥¥$1')+']'+'('+location.href+')';var copy_clipboard=function(text){var ta=document.createElement('textarea');ta.value=text;document.body.appendChild(ta);ta.select();document.execCommand('copy');ta.parentElement.removeChild(ta)};copy_clipboard(target_text);var show_alert=function(target_body,t_msec){var p=document.createElement('p');p.innerHTML=target_body;document.querySelector('body').appendChild(p);p.style.width='100%';p.style.height='auto';p.style.position='fixed';p.style.top='0';p.style.left='0';p.style.backgroundColor='#009900';p.style.color='white';p.style.padding='20px';p.style.display='block';p.style.zIndex='9998';setTimeout(function(){p.parentNode.removeChild(p)},t_msec)};show_alert(target_text,500)};copy_clipboard_for_md();copy_clipboard_for_md=null})()">ブックマークレット</a>

