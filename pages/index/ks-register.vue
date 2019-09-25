<template>
	<view class="dl">
		<view>
			<text class="reg">快速登录</text>
		</view>
		<view class="sh">
			<input type="text" maxlength="11" placeholder="输入手机号码" placeholder-class="pcolor" class="input"/> 
		</view>
		<view class="yzm">
			<input type="text" maxlength="6" placeholder="验证码" placeholder-class="pcolor" class="input"/>
			<image src="../../static/register-images/button_huoquyanzhengma_ksdl.png" mode="" class="captcha"></image>
		</view>
		
		
		<view>
			<view class="button">
				<button style="" class="denglu">登录</button>
			</view>
		</view>
		
	</view>
</template>

<script>
	
</script>

<style>
	input {
	    -webkit-appearance: none;
	}
	.dl {
		/* margin-top: 100upx; */
	}
	
	.reg {
		font-size: 34upx;
		font-family: "黑体";
		font-weight: 700;
		display: block;
		margin: 80upx 0 92upx 60upx;
	}
	
	.sh, .ps {
		width: 580upx;
		height: 66upx;
		border-bottom: 1upx solid #f4f4f4;
		padding: 0upx 0 0 50upx;
	}
	.sh {
		background: url(../../static/register-images/icon_shouji_dl.png) no-repeat left 10upx;
		margin: 0 auto 60upx;
	}
	.yzm {
		background: url(../../static/register-images/icon_yanzhengma_ksdl.png) no-repeat left 10upx;
		margin: 0 auto;
		position: relative;
		
	}
	
	.input {
		font-size: 26upx;
	}
	.captcha {
		width: 142upx;
		height: 42upx;
		position: absolute;
		top: 8upx;
		right: 0;
	}
	
	.button {
		width: 640upx;
		margin: 270upx auto 0;
	}
	.denglu {
		background-color: #47a8ec;
		border-radius: 50upx;
		color: #fffffd;
	}
	
</style>
