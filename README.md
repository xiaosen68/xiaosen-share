＃使用方法：
import xiaosenShare from'@/components/xiaosen-share/xiaosen-share.vue'
	components:{
			xiaosenShare,
		},
    data() {
			return {
				bjList: ['../../static/share2.jpg','../../static/share3.jpg','../../static/share1.jpg','../../static/share3.jpg'],//背景图列表
				codeVal:'二维码内容',//
				codeSize:120,//二维码大小
			}
		}
