<template >
    <div id="photo">
      	<div id="slider" class="mui-slider">
				<div id="sliderSegmentedControl" class="mui-scroll-wrapper mui-slider-indicator mui-segmented-control mui-segmented-control-inverted">
					<div class="mui-scroll">
						<a class="mui-control-item mui-active" href="#item1mobile" data-wid="tab-top-subpage-1.html">
							推荐
						</a>
						<a class="mui-control-item" href="#item2mobile" data-wid="tab-top-subpage-2.html">
							热点
						</a>
						<a class="mui-control-item" href="#item3mobile" data-wid="tab-top-subpage-3.html">
							北京
						</a>
						<a class="mui-control-item" href="#item4mobile" data-wid="tab-top-subpage-4.html">
							社会
						</a>
						<a class="mui-control-item" href="#item5mobile" data-wid="tab-top-subpage-5.html">
							娱乐
						</a>
                        <a class="mui-control-item" href="#item5mobile" data-wid="tab-top-subpage-5.html">
							科技
						</a>
					</div>
				</div>

			</div>
    </div>
</template>
<script>
import mui from '../../assets/mui/js/mui.js'
mui('.mui-scroll-wrapper').scroll({
   deceleration: 0.0005 // flick 减速系数，系数越大，滚动的越慢，滚动的距离越小，默认值0.0006")//100毫秒滚动到顶
})

export default {
    name: 'photo',
    data() {
        return {
            
        }
    },
    methods: {
        
    },
}
</script>
<style lang="scss">
</style>