# guoqing-zhongqiu
嫦娥从无到有飘过来：@keyframes moveC{
	0%{top: 65%;left: 10%;transform: scale(0.2);opacity: 0;}
	50%{top: 57%;left: 26.5%;transform: scale(0.5);opacity: 0.5;}
	100%{top: 49%;left: 43%;transform: scale(1);opacity: 1;}
}
红旗飘动：
@keyframes showF{
	form{opacity: 0;}
	to{opacity: 1;}
}
气球上升：
@keyframes riseT{
	form{top:75%;transform: scale(0.5);}
	to{top:30%;transform: scale(1);transform: rotate(0deg);}
}
眼睛眨动：
@keyframes showEye{
	form{opacity: 0;}
	to{opacity: 1;}
}
字体根据屏幕变动：
@media screen and (max-width: 1024px){
	.glc-exp{
		font-size: 15px;
	}
	.exp-three{
		margin-top: 79%;
	}
}
@media screen and (max-width: 800px){
	.glc-exp{
		font-size: 15px;
		line-height: 30px;
	}
	.bottom2{
		margin-top: 50px;
	}
}
