# note
//Giữ nguyên màn hình ở vị trí 320px
@media screen and (max-width: 767px) 
{
	min-width: 320px;
}

<!-- Thuộc tính clearfix -->
.clear {
    clear: both;
}

.clearfix:after {
    content: ".";
    display: block;
    height: 0;
    clear: both;
    visibility: hidden;
}

.clearfix {
    display: block;
}
