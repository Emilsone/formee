<!-- eslint-disable no-mixed-spaces-and-tabs -->
<template>
	<section class="text-gray-600 body-font relative">
		<div class="container px-5 py-24 mx-auto flex sm:flex-nowrap flex-wrap">
			<div
				class="lg:w-2/3 md:w-1/2 bg-gray-100 rounded-lg overflow-hidden sm:mr-10 p-10 flex items-end justify-start relative">
				<img class="object-cover object-center rounded" alt="hero" src="../assets/contact-image.png">
			</div>
			<div class="lg:w-1/3 md:w-1/2 bg-white flex flex-col md:ml-auto w-full md:py-8 mt-8 md:mt-0">
				<h2 class="text-gray-900 text-2xl mb-1 font-bold title-font">Send us a Message now</h2>
				<p class="leading-relaxed mb-5 text-gray-600 text-md">You are only a few steps away from obtaining the
					information
					you
					require. However, if you send the message now, our team will contact you right away</p>

				<form name="contact" method="POST" data-netlify="true" data-netlify-honeypot="bot-field">
					<input type="hidden" name="form-name" value="Contact" />
					<input type="text" name="name" placeholder="Name" />
					<input type="email" name="email" placeholder="Email" />
					<textarea name="message" placeholder="Message"></textarea>
					<div class="form-btn"><button type="submit">SUBMIT</button></div>
				</form>
			</div>

		</div>
	</section>
</template>


<script>

export default {
	name: 'App',
	components: {},

};
</script>

<style>
.btn-sign {
	background-color: #3A54AA
}

.btn-bg {
	background-color: #1D1D1D;
}
</style>

