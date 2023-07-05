<!-- 文章列表 -->
<template>
	<div>
		<!-- <sg-nav></sg-nav> -->
		<div class="container">
			<el-row :gutter="30">
				<el-col :sm="24" :md="16" style="transition:all .5s ease-out;margin-bottom:30px;">
					<sg-articlelist></sg-articlelist>
				</el-col>
				<el-col :sm="24" :md="8">
					<sg-rightlist></sg-rightlist>
				</el-col>
			</el-row>
		</div>
		<wbc-footer></wbc-footer>
	</div>
</template>

<script>
import header from '../components/header.vue'
import articlelist from '../components/articlelist.vue'
import footer from '../components/footer.vue'
import rightlist from '../components/rightlist.vue'
export default {
	name: "Share",
	data() { //选项 / 数据
		return {

		}
	},
	methods: { //事件处理器

	},
	components: { //定义组件
		'sg-nav': header,
		'sg-articlelist': articlelist,
		'sg-rightlist': rightlist,
		'wbc-footer': footer
	},

	created() { //生命周期函数

	}
}
</script>

<style></style>
