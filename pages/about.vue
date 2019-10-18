<template>
	<div>
		<h1>About Us</h1>
		<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an </p>
	</div>
</template>

<script>
	export default{
		head() {
			return {
				title: 'About',
				meta: [
				 {
                  hid: 'description',
                  name: 'description',
                  content: 'about us'
              }
				]
			}
		}
	};
</script>