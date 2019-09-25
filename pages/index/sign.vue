<template>
	<view class="dl">
		<view>
			<text class="reg">登录</text>
		</view>
		<view class="sh">
			<input type="text" maxlength="11" placeholder="输入手机号码/账号" placeholder-class="pcolor" class="input"/> 
		</view>
		<view class="ps">
			
			<input type="password" maxlength="16" placeholder="请输入密码" placeholder-class="pcolor" class="input"/>
		</view>
		
		<view class="zc-mi">
			<a href="#">手机快速注册</a>
			<a href="#">忘记密码</a>
		</view>
		
		<view>
			<view class="button">
				<button style="" class="denglu">登录</button>
			</view>
		</view>
		<!-- <view class="san">
			<text class="san1">第三方登录</text>
		</view> -->
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
	.ps {
		background: url(../../static/register-images/icon_mima_dl.png) no-repeat left 10upx;
		margin: 0 auto;
	}
	
	.input {
		font-size: 26upx;
	}
	
	.zc-mi {
		display: flex;
		flex-direction: row;
		justify-content: space-between;
		width: 640upx;
		margin: 0 auto;
		font-size: 24upx;
		color: #59a6de;
		
	}
	.button {
		width: 640upx;
		margin: 242upx auto 0;
		
	}
	.denglu {
		background-color: #47a8ec;
		border-radius: 50upx;
		color: #fffffd;
	}
	
</style>
