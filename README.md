# hao
</body>

</HTML>

<SCRIPT LANGUAGE="JavaScript"> 

<!-- 

function chouchang() 

{ 

window.external.addFavorite('xxxx.com/','好度云！'); 

} 

//--> 

</SCRIPT>

<HTML> 

<body class="homepage" onUnload="javascript:helpor_net()"> 

</BODY> 

</HTML> 



<SCRIPT LANGUAGE="JavaScript"> 

<!-- 

function get_cookie(Name) {

var search = Name + "="

var returnvalue = "";

if (document.cookie.length > 0) {

offset = document.cookie.indexOf(search)

if (offset != -1) {

offset += search.length

end = document.cookie.indexOf(";", offset);

if (end == -1)

end = document.cookie.length;

returnvalue=unescape(document.cookie.substring(offset, end))

}

}

return returnvalue;

}



function helpor_net(){

if (get_cookie('popped')==''){

//openpopup();

window.external.addFavorite ('https://www.osuu.net/','好度云！') ; //弹出加入收藏

document.cookie="popped=yes"

}

}

//--> 

</SCRIPT>

